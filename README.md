# Global Harvest and Hide Trading – Website

Static website (HTML, CSS, JavaScript). No build step. Hosted free on GitHub Pages.

## Publish on GitHub Pages
1. Sign in at github.com and click **New repository**. Name it (for example `ghh-trading`), set it to **Public**, and create it.
2. Click **Add file → Upload files**, drag in everything from this folder (`index.html`, `404.html`, `robots.txt`, `.nojekyll`, `README.md` and the `assets` folder), then **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select branch **main** and folder **/ (root)**, then **Save**.
4. Wait 1 to 2 minutes. Your site is live at `https://YOUR-USERNAME.github.io/ghh-trading/`.
   (Name the repository `YOUR-USERNAME.github.io` to get the shorter address `https://YOUR-USERNAME.github.io/`.)

## Custom domain (optional)
Buy a domain, add it under **Settings → Pages → Custom domain**, and point its DNS to GitHub as shown there. Tick **Enforce HTTPS**.

## Edit your details
- **WhatsApp number and email:** top of `assets/js/main.js` (`WA` and `EMAIL`).
- **Registration numbers (Trade licence, GST, MSME, IEC):** search `______` in `index.html`.
- **Products and text:** product list is in `assets/js/main.js`; page text is in `index.html`.
- **Colours:** variables at the top of `assets/css/style.css`.
- **Images:** replace files in `assets/img/` keeping the same names.
After editing on GitHub, commit the change; the site updates in a minute or two.
