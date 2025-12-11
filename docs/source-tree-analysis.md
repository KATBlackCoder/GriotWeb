# Source Tree Analysis

## Overview
- Project: GriotWeb (Nuxt 4, monolith)
- Scan level: quick (pattern-based, minimal file reads)
- Noteworthy: no `server/`, `api/`, `components/`, `pages/`, `prisma/`, `migrations/` detected in this pass

## Annotated Tree (top-level)
- `/app/`
  - `app.vue` — Root Nuxt layout/app entry
- `/public/`
  - `favicon.ico`, `robots.txt` — Static assets served directly
- `/docs/`
  - `bmm-workflow-status.yaml` — Workflow tracking
  - `project-scan-report.json` — Current document-project state
- `/nuxt.config.ts` — Nuxt config (`compatibilityDate: 2025-07-15`, devtools enabled)
- `/package.json` — Scripts (`dev`, `build`, `generate`, `preview`, `postinstall: nuxt prepare`); deps Nuxt 4.2.2, Vue 3.5.25, Vue Router 4.6.3
- `/pnpm-lock.yaml`, `/tsconfig.json`, `/README.md`
- `/.bmad/` — BMAD assets/rules (not expanded in quick scan)
- `/.cursor/` — Cursor rules (not expanded)

## Notes
- Current footprint is minimal; content lives in `app/app.vue`.
- If UI scales, expect `app/` subfolders (`components/`, `pages/`, `layouts/`, `server/`) to appear; none yet in this quick scan.
