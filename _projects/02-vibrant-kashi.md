---
layout: page
title: "Vibrant Kashi"
description: "A travel guide to Varanasi in one website. My solo B.Tech final-year project."
importance: 2
category: featured
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/Vibrant-Kashi) · **Tech:** React, Vite, React Router, Node.js, Express, MongoDB, JWT, bcrypt

## The problem

Visitors to Varanasi jump between many websites to find temples, ghats, places to stay, food and directions. I wanted one website where a visitor finds everything, with the history of each place.

## What it does

- **Pages for every kind of visit:** ghats, temples, museums, historic places, hotels, restaurants, events and festivals, and adventure activities, all driven by JSON data files.
- **Embedded Google Maps** for each category, so visitors see where places are and can get directions.
- **Visitor reviews** with a star-rating form.
- **Accounts:** sign-up, login and forgot-password with an Express and MongoDB backend, passwords hashed with bcrypt and sessions with JWT, shared across the app with React Context.

## What I learned

- Structuring a large React app: reusable cards, sliders and detail pages fed by data files instead of copy-pasted markup.
- React Hooks in practice: useState for forms and UI, useEffect for loading data, useContext for the logged-in user, useNavigate for routing.
- How login really works end to end: hashing passwords, issuing a JWT, storing it, and protecting routes.
- Planning and finishing a project alone, from idea to working app.

## Next

A 3D scrolling experience and a live deployment.
