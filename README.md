# Incorrect State Mutation in React useEffect Hook

This repository demonstrates a common mistake in React: directly mutating state variables within the `useEffect` hook.  Directly modifying the state variable does not trigger a re-render, leading to unexpected behavior.

The `bug.js` file shows the incorrect implementation. The `bugSolution.js` provides the correct approach.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the counter; clicking the button will not increment the counter in the buggy version.