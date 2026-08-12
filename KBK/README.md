# KreatedByKeora — Website

Front-end build for **KreatedByKeora**, a nail artistry studio based in
Kibler Park, Johannesburg South. Built to match the approved WEDE5020
Website Project Proposal (Part 1) and its low-fidelity wireframes.

## Structure

```
KreatedByKeora/
├── index.html          Homepage — hero, quick categories, featured/popular nail art
├── about.html           About Us — Keora's story, background, mission & vision
├── services.html        Services — filterable price list with portfolio images
├── enquiry.html          Booking form — validated client-side, policies, POPIA note
├── contact.html          Map, WhatsApp/call, socials, small contact form
├── art_work.html         Nail art samples that were completed by Keora
├── css/
│   └── style.css        Design tokens, layout, components
├── js/
│   ├── main.js           Mobile nav drawer, services filter, active nav state
│   └── form-validation.js Required-field / email / phone validation
├── images/
│   ├── hero/             Logo
│   ├── portfolio/         Nail art photography
│   └── icons/             (reserved for future iconography)
└── README.md
```

## Design system

- **Colour:** blush pink (`#f1c4d6`) and rose-gold (`#c79a7b`) on a
  charcoal base (`#18131a`), per the proposal's Design & UX brief.
- **Type:** Fraunces (serif, headings) paired with Manrope (sans-serif,
  body/UI).
- **Layout:** mobile-first, single column, with a sticky top header and
  a sticky bottom thumb-nav bar for one-handed browsing — the desktop
  breakpoint (≥860px) swaps in a conventional top nav.

## Notes

- Forms are validated client-side only (no backend/API yet) — this
  matches the Part 1/2 scope in the proposal timeline; server-side
  handling and JavaScript enhancements continue in Part 3.
- WhatsApp/call numbers and social links use placeholder values —
  swap `+27000000000` and the Instagram/TikTok handles for the real
  ones before publishing.
- The contact page map uses a keyless Google Maps embed centred on
  Kibler Park; replace with the exact studio address once available.
