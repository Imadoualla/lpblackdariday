# Rendy Black Friday landing page (dark)

A static page: `index.html` plus the `assets` folder. No build step.

## Deploy

1. Create a GitHub repository and upload everything in this folder (keep `assets` next to `index.html`).
2. Host it from that repository:
   - **GitHub Pages:** Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
   - **Vercel or Netlify:** import the repository; framework "Other", no build command, output folder `/`.

## Before going live

- Both "Get Started" buttons link to `#checkout`; replace that `href` in `index.html` with the checkout URL (and remove the click handler near `checkout URL is not set yet` in the script).
- Footer links point to `#`; set their real URLs.
- The logo and "How are people selling Rendy?" link go to https://rendy.io/.
