# React Router Dom v6 Catch All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6. The catch-all route unintentionally overrides other defined routes, even when a matching path exists.

## Problem

The provided `App.js` file contains a simple React Router setup.  The catch-all route (`/*`) is intended to handle requests that do not match any other routes. However, in this scenario, it's always triggered, regardless of whether `/about` is accessed.