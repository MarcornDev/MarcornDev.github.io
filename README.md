# MarcornDev Portfolio

A from-scratch redesign of the original MyFolio template — rebuilt in
plain HTML, CSS and JavaScript (no Bootstrap, no jQuery, no plugins).

## Files
- `index.html` — all page content and structure
- `css/style.css` — full design system (colors, type, layout, components)
- `js/main.js` — mobile nav, scroll effects, reveal animations, contact form
- `img/favicon.svg` — placeholder mark, swap for your real unicorn logo

## Things to swap in before this goes live
1. **Logo** — the inline SVG unicorn mark in the nav/footer and
   `img/favicon.svg` are simple placeholders. Replace with your real
   logo file (SVG recommended for crispness at any size).
2. **About photo** — the dashed box in the About section
   (`.about-frame`) is a placeholder. Add an `<img>` tag with your photo.
3. **Project thumbnails** — `.project-thumb` divs currently show a
   gradient with initials. Swap in real screenshots of LATA HOUSE
   Schools, Bumi, and this portfolio.
4. **Project & contact links** — `href="#"` placeholders for Live Demo
   / GitHub buttons, and the WhatsApp/GitHub/LinkedIn links in the
   footer and contact section, need your real URLs.
5. **Contact form** — currently front-end only (shows a confirmation
   message but doesn't send anywhere). Connect it to a service like
   Formspree or EmailJS, or your own backend endpoint.
6. **Testimonials** — three placeholder cards are ready in the
   Testimonials section; drop in real quotes, names and roles as you
   get them.
7. **Open Graph image** — `img/og-cover.jpg` is referenced in the
   `<head>` but not included; add a 1200×630 preview image for link
   sharing.

## Notes
- Fonts are loaded from Google Fonts (Sora for headings, Inter for body).
- All colors are defined as CSS variables at the top of `style.css` —
  change them there to restyle the whole site.
- Layout uses CSS Grid/Flexbox only; no framework dependency at all.
