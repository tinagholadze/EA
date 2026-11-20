# Entrepreneurs Association — Website

Single-page static site for the Entrepreneurs Association (EA), a non-profit, membership-based organization founded in 2012 in Georgia.

## Preview locally

No build step is needed. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Works on any static host:

- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, root folder.
- **Netlify / Vercel:** import this repository; no build command, output directory is the root.

## Notes

- Fonts: Playfair Display and Poppins (Google Fonts) — the page needs internet access to render as designed.
- Colour palette: Creative Pink & Cyan (plum, pink and cyan on a soft pink background).
- Accessibility: skip link, visible focus rings, keyboard-accessible mobile menu, reduced-motion support, 44px touch targets.
- Membership applications link to the external Google Form in the "Become a member" section.

## Content to keep up to date

- Address, email and phone in the Contact section.
- Team and advisory board in the Team section.
- Projects list.
