# Architecture

## Overview
- Project: GriotWeb
- Type: Monolith Nuxt 4 (web)
- Entry: `app/app.vue`
- Stack: Nuxt 4.2.2, Vue 3.5.25, Vue Router 4.6.3, ESM
- SSR-ready; currently default NuxtWelcome view.

## Current State
- No custom pages/components/layouts detected in quick scan.
- No backend/server API, no database/migrations detected.

## Responsibilities
- Client rendering via Nuxt; hydration-ready.
- Static assets served from `public/`.

## Gaps / Next Steps
- Add domain UI (pages/components) under `app/`.
- If API needed: add `server/api/*` or external client layer.
- Add deployment adapter/config once target platform is chosen.
