---
layout: page
title: "Find My Car"
description: "Car marketplace with AI image search, test-drive booking and an admin dashboard."
importance: 11
category: web apps
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/Find-My-Car) · **Tech:** Next.js, React, Tailwind CSS, shadcn/ui, Clerk, Prisma, Supabase, Gemini API, Arcjet

## The problem

Buyers often know the car they like by sight, not by name. The marketplace lets them search with a photo and book a test drive in one place.

## What it does

- **AI image search:** upload a car photo to find similar cars in stock (Gemini API).
- **Filters** by make, body type, fuel, transmission and price, plus saved cars.
- **Test-drive booking** with real-time slots, and reservation management.
- **Admin dashboard** for inventory, bookings and sales analytics; EMI calculator on each car page.

## What I learned

- Designing a database for bookings: slots, users and cars, and avoiding double bookings.
- Role-based access: what a buyer and an admin can each see and do.
- Image upload pipelines: storing files and sending them to an AI model.
