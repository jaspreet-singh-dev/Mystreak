MY STREAK — HTTPS HOSTING

This is a static installable PWA. It needs HTTPS hosting for service workers and reliable installation.

EASIEST FREE OPTION: GitHub Pages
1. Sign in to GitHub and create a new public repository, e.g. my-streak.
2. Upload index.html, manifest.json, sw.js and icon.svg to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch; choose main and /(root), then Save.
5. Wait for GitHub Pages to publish. Your URL will look like https://YOUR-USERNAME.github.io/my-streak/
6. Open that URL in Chrome on Android → ⋮ → Add to Home screen / Install app.

Alternative: Cloudflare Pages (direct upload)
1. Sign in to Cloudflare, open Workers & Pages → Create → Pages → Direct Upload.
2. Upload the four files (or the extracted folder contents).
3. Deploy, then open the provided https://...pages.dev URL on Android Chrome.
4. Use Chrome menu → Install app / Add to Home screen.

Your streak data is stored locally in the browser on your device. It is not synced across devices.
Export a JSON backup from the app before clearing browser data. Do not publish private data in the hosting repository.
