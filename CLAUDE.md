# CLAUDE.md — Next.js + SQLite Project Guide

## Stack & versions

Use this baseline for a new project:

- Next.js 15+ with App Router
- React 19+
- TypeScript with strict mode enabled
- Node.js 20+
- SQLite
- Drizzle ORM with `better-sqlite3`
- Zod for validation
- ESLint

Prefer Server Components by default. Add `"use client"` only when browser APIs, client-side state, effects, or event handlers are required.

## Development commands

```bash
npm install
npm run dev
npm run lint
npm run build
npx drizzle-kit generate
npx drizzle-kit migrate

