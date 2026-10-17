# NURI_PROJECT_MEMORY.md — Nuri Shirt Store

## Identity
- Project name: Nuri Shirt Store
- Display name: Nuri
- Subtitle: Shirt Store
- Slug: nuri (target identity; existing codebase uses hscenglishlasthour — migration in progress)
- New Supabase: gukpfmidfhzlidrefvmv (https://gukpfmidfhzlidrefvmv.supabase.co)
- Publishable key (public): sb_publishable_pqV29rgLwsyN6SmmLzJcmQ_w0DPtJFs
- Bucket: book-assets (existing; review for shirt assets)

## Paths
- Website: /Users/mohaiminul/Desktop/bookproject
- Admin: /Users/mohaiminul/Desktop/bookproject-admin
- Git repo (target): https://github.com/nurihome007-cmd/nuri.git
- Collab: https://github.com/mohaiminulislamazim-tech

## Architecture (current)
- Next.js 16.4.0 (App Router, Turbopack), React 19.3, Tailwind v4, TypeScript strict
- Supabase (@supabase/supabase-js + @supabase/ssr), pdf-lib, zod, react-pdf+pdfjs-dist, react-pageflip
- cacheComponents true; page.tsx exports instant=false (dynamic). Realtime live refresh.

## Environment vars
- NEXT_PUBLIC_SUPABASE_URL (use new https://gukpfmidfhzlidrefvmv.supabase.co)
- NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY (sb_publishable_pqV29rgLwsyN6SmmLzJcmQ_w0DPtJFs)
- SUPABASE_SECRET_KEY (server-only; not set)
- SUPABASE_BOOK_BUCKET (book-assets; review)

## Current identity refs
- Display: "HSC English Last Hour"
- Slug: hscenglishlasthour (books.id, storage paths, routes, docs, tests)

## Admin (separate)
- /Users/mohaiminul/Desktop/bookproject-admin; origin https://github.com/mohaiminulislamazim2025-hash/hscenglishlasthour-admin.git

## Status
- Website: 123 tests/13 files pass; lint/typecheck/build clean; commit 76fd49a
