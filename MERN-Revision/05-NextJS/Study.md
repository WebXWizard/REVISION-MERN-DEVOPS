# Next.js Study Notes

Next.js is a React framework for production apps. It provides routing, rendering strategies, API routes, server components, and optimizations.

Important topics:

- App Router
- File-based routing
- Dynamic routes
- Layouts
- Server Components
- Client Components
- API routes / route handlers
- SSR
- SSG
- CSR
- ISR basics
- Middleware
- Image optimization
- Metadata and SEO

Rendering:

```txt
CSR: page renders in browser
SSR: HTML generated on server for each request
SSG: HTML generated at build time
ISR: static page regenerated after interval
```

Internal working:

- Server Components render on server and reduce client JS.
- Client Components are needed for hooks, browser events, and interactivity.
- App Router maps folders to routes.

Common mistakes:

- Using hooks inside Server Components.
- Putting secrets in Client Components.
- Overusing client components.
- Not understanding caching behavior.
- Confusing API routes with Express APIs.

Mini task:

- Build a blog app with dynamic post route, metadata, and one API route.

