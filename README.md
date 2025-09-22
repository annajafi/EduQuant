# Pathway Academy (Khan-style SPA)

A single-file educational site inspired by Khan Academy’s layout. No build tools required — just open `index.html`.

## Run locally
- Open `index.html` in your browser, **or**
- In VS Code, install the **Live Server** extension → right-click `index.html` → **Open with Live Server**.

## Deploy to GitHub Pages
1. Create a new repo (public or private).
2. Upload `index.html` (and this README).
3. Go to **Settings → Pages**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`) and `/ (root)`
4. Wait for Pages to build; your site will be served at the URL shown on that page.

## Features
- Locked progression: complete the **Foundations Track** (4 parts) to unlock six more courses.
- Each lesson requires: **video (simulated)**, **quiz (2/3 to pass)**, **drag‑and‑drop practice**.
- Certificates:
  - **Foundations**: awarded only after all 4 parts are complete.
  - Each additional course awards its own certificate upon completion.
- Progress is persisted in `localStorage`.

## Customize
- Edit titles and unit/lesson counts in `initialData()`.
- Replace the simulated video timer with a real `<video>` and gate completion on watch progress.
- Load quizzes from JSON instead of inline questions.

## License
MIT © 2025
