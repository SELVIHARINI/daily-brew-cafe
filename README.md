# Daily Brew Cafe website

A warm, modern, mobile-friendly café website built with plain HTML, CSS and JavaScript. No framework, package manager, or build step is required.

## Preview locally

1. Download and unzip the project folder.
2. Open `index.html` in a modern browser.
3. For a local web-server preview, open a terminal in this folder and run:
   - Python: `python -m http.server 8000`
   - Then visit `http://localhost:8000`

## Personalize before publishing

Search the project files for the sample details and replace them:

- **Cafe name and branding:** `Daily Brew`, `daily brew`, and `CAFE · CHENNAI` in `index.html`.
- **Phone number:** Replace `+919876543210` in the `tel:` links and `919876543210` in both `https://wa.me/` links. Use international digits only in the WhatsApp URL, with no `+`, spaces, or punctuation.
- **WhatsApp greeting:** Edit the `text=` part of the `wa.me` URL. URL-encode spaces and punctuation, or use a URL encoder.
- **Address and map:** Update the address in `index.html` and the Google Maps search URL so it points to the actual business.
- **Opening hours:** Edit the three rows in the `.hours-list` section.
- **Menu and prices:** Edit the six menu cards in `index.html`. Keep each card's `data-category` set to `coffee`, `food`, or `bakes` so the category filters work.
- **Photos:** Replace the Unsplash image URLs in `index.html` with your own image URLs. Use images you own or have permission to use.
- **Colors and spacing:** Adjust the CSS custom properties at the top of `styles.css`.

## Contact links

- `tel:+919876543210` opens the phone dialer on supported devices.
- `https://wa.me/919876543210` opens a WhatsApp conversation when WhatsApp is available.
- The Google Maps link opens a location search in Maps.

The phone, address, menu, prices, hours, and branding are examples. Update them before sharing the site with customers.

## Deploy it

This is a static site. You can publish the three website files (`index.html`, `styles.css`, and `script.js`) using GitHub Pages, Netlify, Cloudflare Pages, or any standard static web host. Keep all three files together in the same directory.

## Notes

- Google Fonts and the sample food photography are loaded from external URLs, so those images/fonts require an internet connection.
- The site uses semantic HTML, keyboard-visible focus states, responsive layouts, reduced-motion preferences, and an accessible menu filter.
- The map panel is a visual placeholder; the “Get directions” link opens Google Maps.
