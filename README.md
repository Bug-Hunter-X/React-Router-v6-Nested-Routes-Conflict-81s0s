# React Router v6 Nested Route Conflict

This repository demonstrates a common issue encountered when using nested routes in React Router v6.  Specifically, it shows how conflicting route definitions can lead to unexpected rendering behavior.

The problem lies in defining a parent route (`/about`) and then a nested wildcard route (`/about/*`).  These routes conflict, and the wildcard route may unexpectedly override the parent route, leading to incorrect component rendering or unexpected route matches. 

This example shows how to identify and solve this problem. The solution involves carefully reviewing the route definitions to avoid overlapping paths.