---
"@collana-solutions/eslint-config": patch
---

`getConfig` and the built-in configs (`configs.flat.nextjs` etc.) are typed as ESLint's `Linter.Config[]` instead of typescript-eslint's `FlatConfig.ConfigArray`
