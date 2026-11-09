# Shree Gold Buyers website
Static site: HTML, CSS, vanilla JS. No build step.

## Run
VS Code > install **Live Server** > right-click `index.html` > **Open with Live Server**.

## Replace before launch (all in `CONFIG` at the top of `js/script.js`)
PHONE, WHATSAPP, EMAIL, ADDRESS, INSTAGRAM_URL, FACEBOOK_URL, MAP_EMBED_URL, FORM_ENDPOINT.
Until set: WhatsApp/phone show placeholders, social links are hidden, and the form validates but does **not** send anything.
No business hours, history, certifications or prices are claimed on the site.

## Assets
`assets/images/` holds crops of the client's artwork. Full originals are in `assets/images/originals/` (unused promo posters: gold loans, debt-free, transparency, services list, best-value, brand artwork). `assets/logo/emblem.png` is the leaf emblem cut from the brand artwork; supply a transparent logo file when available and swap it in.
Fonts load from Google Fonts (needs internet).

## Pages
`index.html`, `services.html`, `how-it-works.html`, `about.html`, `contact.html` share `css/style.css` and `js/script.js`.
Animations: cinematic hero, light gold dust (desktop only), scroll reveals, service-card hovers. All respect reduced-motion.
