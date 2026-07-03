# Build: Tohoku Page

Working notes for filling in `trips/tohoku-2026/index.html` once the
itinerary is finalized. Internal instructions only — not part of the site.

## Known trip facts

- Route: Aomori → Akita → Iwate
- Duration: 8 days
- Style: self drive
- Month: August 2026

## Content to include

Places confirmed for the itinerary so far:

- Kakunodate Samurai District
- Oirase Gorge
- Hasshoku Seafood Market
- Kabushima Shrine
- Aomori apple products
- Marukan Cafeteria, Hanamaki

## Constraints

- Keep the folder self-contained: only `index.html` + `trip.css` live in
  `trips/tohoku-2026/`. No dependency on the root `style.css`.
- Reuse the same typography system as the rest of the site (Manrope
  headings / Inter body) for visual consistency, even though the stylesheet
  file itself stays separate from the homepage.
- Replace the current "Coming soon" placeholder once itinerary content is
  ready — do not leave dead sections.
