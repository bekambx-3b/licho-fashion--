# Licho Fashion — HTML, JavaScript & Tailwind CSS

This version does not use React or TypeScript. It is a static website with plain HTML, CSS, and JavaScript, with Tailwind CSS loaded from its CDN.

## Run locally
Open `index.html` in a browser, or use VS Code Live Server. Internet is required for Tailwind CDN, Google Fonts, icons, and map tiles.

## Deploy to Vercel
1. Push the contents of this folder to a GitHub repository.
2. Import the repository into Vercel.
3. Set Framework Preset to **Other**.
4. Leave Build Command empty (or override it to `echo Static site`).
5. Set Output Directory to `.`.
6. Deploy.

No `npm install`, `tsc`, React, or Vite build is needed. Keep `index.html`, `app.js`, `translations.js`, `styles.css`, and `assets/` in the same root directory.

The inquiry form prepares a message to copy into Telegram; it does not send automatically. Store map marker is an approximate town-centre reference.
