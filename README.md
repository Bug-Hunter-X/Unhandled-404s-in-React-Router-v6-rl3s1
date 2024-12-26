# React Router v6 Unhandled 404s

This repository demonstrates a common issue in React Router v6: handling unexpected URLs and preventing 404 errors.  When a user navigates to a URL that doesn't match any defined routes, the application typically displays nothing or throws an error.

The `App.js` file shows a basic React Router setup lacking a catch-all route. The solution (`AppSolution.js`) demonstrates how to resolve this using a `Route` component with the `path="*"` attribute. This route acts as a fallback, handling any URLs that don't match other defined routes.