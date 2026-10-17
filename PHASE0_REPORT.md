# NURI — FULL PROJECT REBRANDING, SUPABASE MIGRATION & UI REDESIGN (Phase 0 completed)

1. Website: /Users/mohaiminul/Desktop/bookproject (commit 76fd49a, 123/13 tests passing, lint/typecheck/build clean)
2. Admin: /Users/mohaiminul/Desktop/bookproject-admin (separate repo; no supabase/; shares Supabase + book-assets)
3. Git target: https://github.com/nurihome007-cmd/nuri.git (push succeeded; remote set on website)
4. New Supabase: https://gukpfmidfhzlidrefvmv.supabase.co (ref gukpfmidfhzlidrefvmv), publishable key provided; SECRET/SERVICE_ROLE key MISSING
5. Codebase fully scanned (website + admin). Memory updated at /Users/mohaiminul/Desktop/bookproject/NURI_PROJECT_MEMORY.md
6. Identity refs: 20+ files contain "HSC English Last Hour"/"hscenglishlasthour"
7. Book features present: reader/flip/PDF, book pages, books/book_pages tables
8. Admin: full auth (Supabase Auth + admin_users), signed uploads, orders/status, catalog management
9. Critical blocker: SUPABASE_SECRET_KEY (or SERVICE_ROLE_KEY) not provided; also DB password not provided for supabase CLI migrations
10. Git permission OK now (push works). Old repos not deleted.

STATUS: Phase 0 COMPLETED. Memory + discovery done. Cannot proceed with destructive schema changes without secret key. Safe edits possible but migration to new Supabase requires service role/DB credentials.
