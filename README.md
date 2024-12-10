# Inefficient useEffect in React Component

This repository demonstrates a common React bug where the `useEffect` hook is used inefficiently, causing unnecessary re-renders.

## Bug Description
The `useEffect` hook in `MyComponent` is configured to run on every render because it's missing the dependency array. This can lead to performance issues, especially in complex applications.