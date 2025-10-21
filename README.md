# Oak HR Solutions (Vercel-ready ZIP)

Sleek corporate build (Vite + React + Tailwind) prepared for GitHub -> Vercel deployment.

## Quick deploy (no terminal)
1. Unzip this archive.
2. Go to GitHub -> New Repository -> name it `oak-hr-solutions`.
3. In the new repo, click 'Add file' -> 'Upload files'. Drag the *contents* of the unzipped folder (don't upload the zip file itself).
4. Commit to `main`.
5. Go to https://vercel.com/new -> Import Project -> choose your GitHub repo -> Deploy.

## Local (optional)
- Install: `npm install`
- Dev server: `npm run dev`
- Build: `npm run build` (output goes to `dist`)

Forms use Formspree for email forwarding. Replace the endpoint in `src/App.jsx` with your own Formspree URL when ready.
