# Svelte Login UI

A focused login experience built with Svelte and Vite, featuring an accessible form, client-side validation, and a responsive layout designed for modern SaaS dashboards.

## Structure

- `src/main.js`: Application entry point that mounts the app and loads shared styles.
- `src/App.svelte`: Layout with a descriptive intro and the login panel.
- `src/lib/components/LoginForm.svelte`: Encapsulated login form with validation, feedback, and helper links.
- `src/lib/styles/global.css`: Theme tokens, global resets, and background treatments.

## Getting started

```bash
npm install
npm run dev -- --host
```

Open the URL reported by the dev server (usually `http://localhost:5173`) to preview the login page.

## Build

```bash
npm run build
```
