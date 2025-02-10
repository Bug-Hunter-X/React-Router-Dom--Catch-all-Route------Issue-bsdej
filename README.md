This repository demonstrates a common issue encountered when using the catch-all route `/*` in React Router Dom. The `/*` route is designed to handle any unmatched routes, but it sometimes triggers even when other routes match, leading to incorrect page rendering.

The solution involves understanding the order of routes and implementing a more precise catch-all mechanism.