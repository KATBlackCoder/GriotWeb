# Project Overview

- **Project:** GriotWeb
- **Type:** Monolith Nuxt 4 (web)
- **Purpose:** GriotWeb est un site web pour présenter l'histoire et les traditions de l'Afrique (début Mali), avec citations, conseils et astuces de vie.
- **Stack (quick scan):** Nuxt 4.2.2, Vue 3.5.25, Vue Router 4.6.3, ESM, devtools enabled, compatibilityDate 2025-07-15.
- **Structure (observed):** Minimal root with `app/app.vue`; no `server/`, `api/`, `components/`, `pages/` yet.

## Current Status
- Content is still the Nuxt welcome template (`app/app.vue`).
- No backend/API, database, or migrations detected in this scan.
- No deployment configuration detected; use Nuxt deployment guides when ready.

## Next Recommendations
- Add actual UI (pages/components/layouts) under `app/`.
- Define data/API layer if needed (e.g., `server/api/` or external API client).
- Add deployment config (e.g., adapter/hosting) once target platform is chosen.
- Keep `CHANGELOG.md` and `PROGRESS.md` updated as features land.
