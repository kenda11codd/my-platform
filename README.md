# My Personal Production Platform

This repository contains my personal production platform, a full-stack portfolio application that will be developed and operated throughout the senior capstone.

## Current Status

The repository structure and Git/GitHub development workflow have been established.

The frontend is a single-page portfolio site built with React, TypeScript, Vite, and Tailwind CSS.

The backend, database, and other production capabilities will be added incrementally during the course.

## Running the Frontend Locally

```bash
cd frontend
npm install
npm run dev
```

Other useful commands, also run from `frontend/`:

- `npm run build` — type-check and create a production build in `dist/`
- `npm run lint` — run ESLint

## Editing the Site

- Site text (experience, skills, projects, contact details): `frontend/src/data/portfolio.ts`
- Design tokens (colors, fonts, shadows, shapes): `frontend/src/index.css`
- Hero photo: add `frontend/src/assets/headshot.jpg` and it replaces the initials placeholder

## Repository Structure

- `frontend/` — React frontend
- `backend/` — application backend
- `docs/` — engineering and production documentation
- `requirements/` — implementation requirements and completion evidence for production-platform capabilities

## Development Workflow

Development is performed from WSL/Linux.

Changes are developed on focused branches and merged into protected `main` through pull requests.

## Engineering Conventions

Project conventions are documented in:

`docs/style-guide.md`
