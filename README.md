# Oak HR Solutions (GitHub-ready ZIP)

This is a Vite + React + Tailwind project prepared for quick deployment to Vercel.

## Quick deploy (no terminal)
1. Go to GitHub -> New Repository -> name it `oak-hr-solutions`.
2. Click 'Add file' -> 'Upload files'. Drag the **contents** of this zip (do not upload the zip itself).
3. Commit to `main`.
4. Go to https://vercel.com/new -> Import Project -> choose your GitHub repo -> Deploy.

## If using locally
- Install dependencies: `npm install`
- Run dev server: `npm run dev`
- Build for production: `npm run build`

Forms are wired to Formspree (https://formspree.io). Update the endpoint in `src/App.jsx` if you want emails to go somewhere else.
