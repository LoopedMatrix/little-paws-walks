# Little Paws Walks

A mobile-first, single-page static website for Little Paws Walks, a local dog-walking service in the City of Boroondara, Melbourne.

## Files

- `index.html` — page structure and copy
- `styles.css` — responsive layout, colours, typography, and components
- `assets/` — downloaded Unsplash images

Open `index.html` directly in a browser to preview it. No build step is required.

## Editing the site

- To change prices, edit the two `price` blocks in `index.html` (currently `$30 AUD` and `$50 AUD`). Update the matching service descriptions if needed.
- To change wording, edit the text in the relevant section of `index.html`.
- The Instagram CTA and handle currently point to `https://www.instagram.com/littlepawswalks/` and `@littlepawswalks`. The Instagram account will be created; update these links when it is live.
- The booking form opens an email draft to the placeholder address `hello@littlepawswalks.com`. To replace the placeholder email later, search for `hello@littlepawswalks.com` and update every occurrence in `index.html` and this README.
- Colours, spacing, and responsive breakpoints live in `styles.css`.

## Hosting later

This is plain HTML/CSS and can later be hosted on any static host (for example, GitHub Pages, Netlify, Cloudflare Pages, or a basic web server). Upload the contents of this folder with `index.html` at the site root.

## Photo attributions

Photos were downloaded from Unsplash and saved locally in `assets/` so the page does not depend on remote image loading:

- `assets/dog-on-walk.jpg` — Unsplash image ID `photo-1558788353-f76d92427f16`; source: https://images.unsplash.com/photo-1558788353-f76d92427f16
- `assets/happy-dog.jpg` — Unsplash image ID `photo-1518717758536-85ae29035b6d`; source: https://images.unsplash.com/photo-1518717758536-85ae29035b6d
- `assets/leafy-park.jpg` — Unsplash image ID `photo-1441974231531-c6227db76b6e`; source: https://images.unsplash.com/photo-1441974231531-c6227db76b6e

Images are used under the Unsplash license. The unused `happy-dog.jpg` is included as an optional extra image if the page is expanded later.
