# Context API

Context API shares state across components without prop drilling.

Use for:

- Theme
- Auth user
- Language
- Small global state

Avoid using Context for very frequent updates across large trees because it can cause unnecessary re-renders.

