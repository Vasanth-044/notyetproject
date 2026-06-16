# notyetproject

A production-oriented MVP starter for **NOT YET**, an adaptive learning and recruiter-trust platform built with **Next.js** and **Supabase**.

## Stack
- Next.js
- React
- Supabase Auth
- Supabase Postgres
- Server Actions
- Vercel-ready deployment

## Included
- Landing page
- Signup page
- Login page
- Protected dashboard
- Student progress page
- Diagnostic test flow
- SQL schema
- SQL migration for diagnostic engine
- Seed data

## Setup
1. Copy `.env.example` to `.env.local`
2. Add Supabase credentials
3. Run SQL in this order:
   - `supabase/schema.sql`
   - `supabase/diagnostic_migration.sql`
   - `supabase/seed.sql`
4. Install dependencies with `npm install`
5. Start locally with `npm run dev`

## Deploy
- Push this repo to GitHub
- Import it into Vercel
- Add environment variables in Vercel
- Set Supabase Auth redirect URLs

## Environment variables
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `SUPABASE_SERVICE_ROLE_KEY`
