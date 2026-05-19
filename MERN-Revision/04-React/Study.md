# React Study Notes

React is a JavaScript library for building component-based user interfaces.

Important topics:

- Components
- JSX
- Props
- State
- Events
- Conditional rendering
- Lists and keys
- Forms
- Controlled and uncontrolled components
- Hooks: `useState`, `useEffect`, `useMemo`, `useCallback`, `useRef`
- Context API
- Routing
- Virtual DOM
- Reconciliation
- Lifecycle
- Redux basics

Why React:

- Reusable components
- Declarative UI
- Strong ecosystem
- Efficient UI updates
- Better state-driven development

Internal working:

```txt
State/props change -> component re-renders -> virtual DOM created -> diffing -> minimal DOM update
```

Real-world example:

- Product card component reused across e-commerce pages.
- Cart count updates using state.
- User auth data shared using Context.

Common mistakes:

- Mutating state directly.
- Missing dependency array in `useEffect`.
- Using index as key for dynamic lists.
- Overusing Context for frequently changing data.
- Using `useMemo` and `useCallback` everywhere without need.

Mini task:

- Build a Todo app with add, delete, complete, filter, and localStorage persistence.

