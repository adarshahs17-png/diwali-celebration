# Exide Energy Solutions – Diwali Experience

A responsive, single-page festive greeting website with a diya-lighting interaction, personalised name, CSS rangoli/courtyard effects, fireworks-style animation, and shareable URL.

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```
The production site is generated in `dist/`.

## Public deployment (Vercel)
1. Create a Git repository and push this project.
2. Sign in to Vercel and import the repository.
3. Framework preset: Vite.
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy and test the public URL on mobile.

Netlify alternative: import the repository, use build command `npm run build` and publish directory `dist`.

## Personalised greeting
Append `?to=Employee%20Name` to the deployed URL. The visitor can also enter a name on the welcome screen and use Share.

## Branding
The current mark is a text-based placeholder, not an official Exide logo. Replace it only with an approved company logo and obtain company approval before public publishing.

## Notes
- No backend or employee database is used.
- Name data is kept in the browser URL only when the visitor shares a personalised link.
- Sound is intentionally minimal and browser interaction-triggered.
- This initial version uses CSS effects rather than heavyweight downloaded 3D assets, for faster mobile loading.
- Google Fonts are loaded from Google Fonts when network access permits; system fallbacks are provided.
