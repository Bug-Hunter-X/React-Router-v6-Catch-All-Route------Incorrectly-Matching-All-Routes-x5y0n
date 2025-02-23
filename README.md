# React Router v6 Catch-All Route Issue

This repository demonstrates a bug in React Router v6 where the catch-all route (`/*`) incorrectly matches all routes, even those defined above it.  This prevents the other routes from working correctly.  The solution shows how to fix this issue by carefully ordering and using the catch-all route as the last route defined.