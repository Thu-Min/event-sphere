# Phase 1 Discussion

## Goal

Scaffold the EventSphere project with Next.js, TypeScript, and dev tooling so that the team has a working development environment and a deployable baseline.

## Requirements

- Next.js app initialized with TypeScript (App Router)
- Next.js API routes configured for backend endpoints
- Project structure established: `app/` for pages, `app/api/` for API routes
- ESLint and Prettier configured with sensible defaults
- Dev scripts work: `pnpm dev` starts the Next.js app
- Basic health-check API route at `/api/health` returns 200

## Assumptions

- **Package manager:** pnpm
- **Styling:** Tailwind CSS (create-next-app default)
- **Router:** App Router (Next.js default since v13+)
- **TypeScript:** Strict mode enabled
- **ESLint:** Next.js default config (`eslint-config-next`)
- **Prettier:** Standard config with defaults
- **Node version:** 20+ (LTS)
- **Database:** SQLite (configured in a later phase, F-002)
- **Hosting target:** Vercel (per PR-FAQ)

## Unknowns

- None significant for scaffolding — this is a standard Next.js setup with well-known defaults.

## Decisions

### Package manager
- **Decision:** Use pnpm
- **Context:** User prefers pnpm over npm/yarn/bun
- **Alternatives considered:** npm (default), yarn, bun

### Project structure
- **Decision:** Use create-next-app defaults with App Router
- **Context:** Modern Next.js conventions, no custom structure needed at scaffolding phase

### Styling
- **Decision:** Tailwind CSS
- **Context:** Default option in create-next-app, widely adopted for 2025/2026 projects

### Linting & formatting
- **Decision:** ESLint (Next.js defaults) + Prettier (standard config)
- **Context:** User wants modern defaults, no custom strict rules at this stage
