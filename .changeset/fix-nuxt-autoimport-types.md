---
"evlog": patch
---

Fix Nuxt auto-import types for `useLogger`, `log`, `parseError`, and related helpers. The Nuxt module now ships explicit type templates that resolve through `evlog` / `evlog/client` package exports instead of Nitro's extensionless `dist/` paths, which typed as `any`.
