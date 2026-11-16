---
layout: page
title: "SourcingStudio Pro"
description: "Turns complicated LinkedIn Boolean and Google X-ray job searches into clickable building blocks."
importance: 1
category: featured
related_publications: false
---

**Live:** [open it](https://mishrashilpa-28.github.io/SourcingStudio-Pro/) · **Code:** [GitHub](https://github.com/mishraShilpa-28/SourcingStudio-Pro) · **Tech:** JavaScript, HTML, Tailwind CSS, localStorage

## The problem

As a recruiter I searched for jobs for 15-20 clients every day across healthcare, biotech, supply chain and finance. Every search meant typing long Boolean strings by hand: one missing quote or bracket broke the search, LinkedIn silently cuts off strings that are too long, and switching to another client's field meant starting again.

## What it does

- **Five-step builder:** country and city, job titles and skills, seniority to exclude, salary floor and visa rules, each switched on or off with a click.
- **Three outputs from one setup:** a LinkedIn search string with a live length meter, a Google X-ray search that reads the full text of job posts, and one-click searches on NHS Jobs, Workday, Greenhouse, Lever, Indeed and Reed.
- **Visa and clearance shield:** strips out roles that need security clearance or cannot sponsor a visa before you ever open them.
- **Saved profiles:** four ready-made domain profiles plus your own, saved in the browser and exportable as JSON.
- **Job tracker:** log good jobs and copy the table into Google Sheets or download it as CSV.

## What I learned

- Turning a messy daily task into a clear five-step flow taught me to design the interface around the user's decisions, not around the code.
- Building search strings safely: escaping quotes, grouping OR terms in brackets and measuring length before LinkedIn truncates them.
- Keeping state in a single-file app without a framework: one state object, render functions, and localStorage for saved profiles.
- Shipping something people use every day: small details like copy buttons and a length warning mattered more than extra features.
