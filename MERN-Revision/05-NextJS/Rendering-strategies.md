# Rendering Strategies

Next.js multiple rendering strategies support karta hai.

Summary:

```txt
CSR: browser renders
SSR: server renders per request
SSG: build-time HTML
ISR: static page revalidates after interval
```

How to choose:

- SEO + fresh data: SSR
- SEO + static data: SSG
- Interactive private UI: CSR
- Mostly static with updates: ISR

Mini task:

- Choose strategy for blog, dashboard, product page, and news page.

