# Agrosmart AI

## Project overview

A farmer-facing agriculture application with login, farmer profile, and dashboard experiences.

## What it contains

- React and Vite frontend
- Farmer login screen
- Farmer profile workflow
- Dashboard route and reusable components
- Browser-based navigation and local session state
- Calls to a farmer login API currently configured at `http://localhost:5000/api/farmer/login`

## Current status

This repository currently contains the frontend application. The backend service, database, AI/agronomy capabilities, and deployment configuration are not present at the repository root. The existing UI stores a login flag and farmer identifier in `localStorage`; that is suitable only as prototype state and is not a secure server-controlled session.

## Local development

```bash
npm install
npm run dev
```

## Recommended next work

- Define the exact farming problems the product solves.
- Add a documented backend/API and environment-based API URL.
- Replace prototype login state with authenticated, expiring server sessions.
- Define consent, farmer-data privacy, offline/low-connectivity behavior, and Marathi/English UX.
- Document which “AI” recommendations are implemented, their evidence sources, and safety limitations.
