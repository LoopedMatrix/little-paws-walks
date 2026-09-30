# Little Paws Walks

A mobile-first, single-page static website for Little Paws Walks, a local dog-walking service in the City of Boroondara, Melbourne.

## Files

- `index.html` — page structure and copy
- `styles.css` — responsive layout, colours, typography, and components
- `assets/` — downloaded Unsplash images

Open `index.html` directly in a browser to preview it. No build step is required.

## Editing the site

- To change prices, edit the two `price` blocks in `index.html` (currently `$50 AUD` and `$80 AUD`). The site also notes `+$10 AUD per additional pet on the same walk`.
- To change wording, edit the text in the relevant section of `index.html`.
- The Instagram CTA and handle currently point to `https://www.instagram.com/littlepaws.walks/` and `@littlepaws.walks` (account claimed).
- Bookings are made through the Cal.com calendar embed (`#book`, https://cal.com/littlepawswalks). The "Contact us" form is for general enquiries: it opens an email draft to `hello@littlepawswalks.au` with name, email, optional phone, and message. To change the email later, search for `hello@littlepawswalks.au` and update every occurrence in `index.html` and this README.
- Images: each photo has a resized JPEG fallback plus WebP versions (`-600.webp`, `-1000.webp`) served via `<picture>`/`srcset`. If you swap a photo, regenerate all sizes.
- SEO: title/description, LocalBusiness JSON-LD (bottom of `index.html`), `sitemap.xml` and `robots.txt`. Update `lastmod` in the sitemap when content changes.
- Colours, spacing, and responsive breakpoints live in `styles.css`.

## Hosting

Live at https://littlepawswalks.au/ (GitHub Pages from `main`, custom domain set via the `CNAME` file; `www` redirects to the apex). DNS is managed at VentraIP: four A records for `@` → 185.199.108.153 / 109 / 110 / 111 and `www` CNAME → loopedmatrix.github.io.

This is plain HTML/CSS, so it can also be hosted on any static host with `index.html` at the site root.

## Photo attributions

Photos were downloaded from Unsplash and saved locally in `assets/` so the page does not depend on remote image loading:

- `assets/dog-on-walk.jpg` — Unsplash image ID `photo-1558788353-f76d92427f16`; source: https://images.unsplash.com/photo-1558788353-f76d92427f16
- `assets/happy-dog.jpg` — Unsplash image ID `photo-1518717758536-85ae29035b6d`; source: https://images.unsplash.com/photo-1518717758536-85ae29035b6d
- `assets/leafy-park.jpg` — Unsplash image ID `photo-1441974231531-c6227db76b6e`; source: https://images.unsplash.com/photo-1441974231531-c6227db76b6e

Images are used under the Unsplash license. The unused `happy-dog.jpg` is included as an optional extra image if the page is expanded later.
