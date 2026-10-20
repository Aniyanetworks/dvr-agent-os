# dvr-agent-os

Product website for **DV Agent OS**, the real estate operating system for Dream Valley Realty agents.

A single static page (no build step), deployed on Netlify.

## Files
- `index.html`: the website
- `404.html`: page-not-found screen that returns to the homepage
- `netlify.toml`: Netlify settings (publish folder, security headers, no caching on the homepage)

## Deploy
Connect this repo in Netlify (**Add new site → Import an existing project**). No build command is needed; the publish directory is the repo root.

## Editing
- Booking buttons link to `https://link.dvrealty.ca/widget/booking/OGmMikOxrh82G37KMN6Q`
- Pricing shows `$XX` placeholders in the Pricing section of `index.html`
