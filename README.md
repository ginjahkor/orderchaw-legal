# OrderChaw — Legal Pages

Public legal pages for **OrderChaw**, a product of **QuoNord Technology**.

Published at **https://privacy.orderchaw.com**

| Page | Path | Purpose |
|---|---|---|
| Privacy Policy | `/` (`index.html`) | Required by Google Play. Discloses all data collection, sharing, third parties and retention. |
| Terms of Service | `/terms.html` | Wallet rules, ordering terms. |
| Delete Your Account | `/delete-account.html` | Required by Google Play — a web-accessible account deletion route. |

## Why this repo exists separately

Google Play requires the privacy policy to be at a **publicly accessible URL** that loads in a browser without a login and is not a downloadable file. This repo is deliberately kept **outside** the Firebase/Google Cloud project so hosting never depends on that project's billing state.

## Hosting

Static HTML. No build step, no dependencies. Deployable via GitHub Pages or Vercel.

- **GitHub Pages:** Settings → Pages → Source `main` / root. The `CNAME` file sets the custom domain.
- **Vercel:** import this repo, framework preset "Other", no build command, output directory `.`

## Editing

Plain HTML with inline CSS. Update the "Last updated" date at the bottom of any page you change.

---
Contact: support@orderchaw.com
