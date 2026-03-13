# Phase 1 Plan

## Objective

Scaffold the EventSphere Next.js project with TypeScript, Tailwind CSS, ESLint, Prettier, and a health-check API route. After this phase, `pnpm dev` starts a working app with a `/api/health` endpoint returning 200.

## Tasks

### Task 1: Initialize Next.js project with create-next-app

Run `pnpm create next-app` in the repo root with TypeScript, Tailwind CSS, ESLint, and App Router enabled. Use `src/` directory: no (keep `app/` at root for simplicity). Accept other defaults.

Since the repo already has files (`.branchos/`, `PR-FAQ.md`, `.gitignore`), run create-next-app into a temp directory and move files into the repo root, or run it in-place if supported.

#### Affected Files

- `package.json`
- `pnpm-lock.yaml`
- `tsconfig.json`
- `next.config.ts`
- `tailwind.config.ts`
- `postcss.config.mjs`
- `app/layout.tsx`
- `app/page.tsx`
- `app/globals.css`
- `public/`

#### Dependencies

- None (first task)

#### Risks

- create-next-app may conflict with existing repo files — handle by running in temp dir and merging

### Task 2: Configure Prettier

Add Prettier with standard config. Add a `.prettierrc` config file and install the prettier package.

#### Affected Files

- `.prettierrc`
- `package.json`

#### Dependencies

- Task 1 (package.json must exist)

#### Risks

- None — straightforward config addition

### Task 3: Update .gitignore

Ensure `.gitignore` covers Next.js build output, node_modules, env files, and IDE files. Merge with existing `.gitignore` content.

#### Affected Files

- `.gitignore`

#### Dependencies

- Task 1

#### Risks

- None

### Task 4: Create health-check API route

Create `app/api/health/route.ts` that returns a JSON response with `{ status: "ok" }` and HTTP 200.

#### Affected Files

- `app/api/health/route.ts`

#### Dependencies

- Task 1 (Next.js app must be initialized)

#### Risks

- None — minimal endpoint

### Task 5: Clean up boilerplate

Remove or simplify the default create-next-app landing page content. Replace `app/page.tsx` with a minimal welcome page. Clean up `app/globals.css` to keep only Tailwind directives.

#### Affected Files

- `app/page.tsx`
- `app/globals.css`

#### Dependencies

- Task 1

#### Risks

- None

### Task 6: Verify dev server and health endpoint

Run `pnpm dev` and confirm the app starts. Verify `/api/health` returns 200 with `{ status: "ok" }`.

#### Affected Files

- None (verification only)

#### Dependencies

- Tasks 1-5

#### Risks

- Port conflicts on dev machine

## Affected Files

- `package.json`
- `pnpm-lock.yaml`
- `tsconfig.json`
- `next.config.ts`
- `tailwind.config.ts`
- `postcss.config.mjs`
- `.prettierrc`
- `.gitignore`
- `app/layout.tsx`
- `app/page.tsx`
- `app/globals.css`
- `app/api/health/route.ts`
- `public/`
