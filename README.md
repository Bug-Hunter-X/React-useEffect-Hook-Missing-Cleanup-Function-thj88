# React useEffect Hook Missing Cleanup Function

This example demonstrates a common error in React's `useEffect` hook: omitting the cleanup function.  The `useEffect` hook, when used without a cleanup function, can cause memory leaks or unexpected behavior if the component unmounts before the effect completes.

The provided `bug.js` shows the incorrect implementation, while `bugSolution.js` offers the corrected version, highlighting the importance of cleanup.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` or `yarn install` to install dependencies.
3. Run `npm start` or `yarn start` to start the development server.
4. Observe the console logs.  You'll notice issues when navigating away from the component or when the component unmounts.