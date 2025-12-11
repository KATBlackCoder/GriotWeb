# Deployment Guide

## Status
- No deployment-specific files detected in quick scan.
- Use Nuxt standard deployment flow once target platform is selected.

## Generic Nuxt Deployment (baseline)
1) Build: `pnpm build`
2) Preview locally: `pnpm preview`
3) Deploy the `.output/` (Nitro) bundle to your target (Node, serverless, edge) per Nuxt docs.

## To Define
- Target platform (e.g., Node hosting, Vercel, Netlify, Cloudflare, container).
- Environment variables and secrets.
- CDN/assets strategy for `public/` if needed.
- CI/CD pipeline steps (build/test/deploy).

## Next Actions
- Choose platform and add its adapter/config.
- Add CI workflow file once platform decided.
- Update this guide with platform-specific steps.
