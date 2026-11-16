---
layout: page
title: "WhisperWave"
description: "Real-time chat app with login, profile photos, user search and instant messaging."
importance: 12
category: web apps
related_publications: false
---

**Live:** [open it](https://whisperwave-g6y1.onrender.com) · **Code:** [GitHub](https://github.com/mishraShilpa-28/WhisperWave) · **Tech:** React, Redux Toolkit, Tailwind CSS, daisyUI, Node.js, Express, MongoDB, Socket.io, JWT

## The problem

Messages should appear instantly, without refreshing, and conversations should survive a reload.

## What it does

- **Real-time messaging** and online status with Socket.io.
- **Sign-up and login** with JWT and bcrypt-hashed passwords; profile photos.
- **User search** and saved conversations in MongoDB.
- **Persistent state** with Redux Toolkit and redux-persist; deployed on Render.

## What I learned

- The difference between request-response HTTP and a live WebSocket connection.
- Keeping the UI, the Redux store and the database in sync when messages arrive from the server.
- Deploying a full-stack app with a separate frontend and backend.
