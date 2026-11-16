---
layout: page
title: "Wealth-Wise"
description: "Personal finance app with AI receipt scanning, budgets, recurring transactions and monthly email reports."
importance: 10
category: web apps
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/Wealth-Wise) · **Tech:** Next.js 15, React 19, Tailwind CSS, shadcn/ui, Clerk, Prisma, Supabase (PostgreSQL), Gemini API, Inngest, Resend, Arcjet, Recharts

## The problem

Tracking money by hand is tedious, so most people stop. The app makes logging spending fast and turns it into insight.

## What it does

- **Receipt scanning:** upload a photo and the Gemini API extracts amount, date and category.
- **Budgets with email alerts** when spending nears the limit, and **monthly reports** by email (Resend).
- **Recurring transactions** and scheduled checks as background jobs (Inngest).
- **Dashboard** with charts (Recharts), multiple accounts, secure sign-in (Clerk) and bot protection and rate limiting (Arcjet).

## What I learned

- Full-stack Next.js: server actions, protected routes and a PostgreSQL database through Prisma.
- Using an LLM API for structured extraction and validating what it returns.
- Why background jobs matter: work that runs on a schedule must not depend on a user being online.
