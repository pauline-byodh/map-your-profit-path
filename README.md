# Map Your Profit Path

A single self-contained `index.html` file — no build step, no npm, no terminal required.

## How to deploy on Vercel (drag-and-drop, no account credits needed)

1. Go to https://vercel.com and sign up / log in (free Hobby plan is fine).
2. Click **"Add New..." → "Project"**.
3. Look for the **drag-and-drop upload** option (Vercel accepts a folder of static files directly, no GitHub required).
4. Drag this whole `profit-path-app` folder onto the page.
5. Click **Deploy**. Vercel will give you a live `.vercel.app` URL in about 10 seconds.

That's it — this is a 100% static HTML file (React, Tailwind, and the icons all load from public CDNs at page-load time), so there's nothing to "build" and no server-side cost. It'll run fine on Vercel's free tier indefinitely.

## Alternative: even simpler, no account at all

If you just want a link to share right now without setting up Vercel:
- https://app.netlify.com/drop — drag the folder in, get a live link in seconds, no login required.

## Notes
- Internet connection is required for visitors (it loads React/Tailwind/fonts from CDNs).
- If you ever want a custom domain, Vercel and Netlify both support connecting one for free — just no credits/billing needed for hosting itself.
