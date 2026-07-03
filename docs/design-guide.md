# Design Guide

Internal reference for Claude Code and future contributors.
Not rendered or imported by the website.

## Typography

- Headings: `Manrope`, weight 600, `letter-spacing: -1px`
- Body text: `Inter`, weight 400
- Trip card text: `Inter` (titles weight 600 for hierarchy, rest weight 400)
- Buttons / navigation links: `Inter`, weight 500
- No serif fonts anywhere — no Georgia, Times New Roman, Garamond.

## Color

- Background: `#fafafa`
- Primary text: `#14151a`
- Secondary text: `#6b6d78` / `#8b8d98`
- Card border: `#eceef1`

## Visual direction

This is a structured personal travel archive — not a blog, not a portfolio
showcase, not a SaaS landing page. Clean, minimal, readable hierarchy.
References: Linear, Airbnb, Notion.

- Generous whitespace
- Rounded cards (16px radius)
- Soft, subtle shadows — no heavy drop shadows
- No italics, no decorative/editorial letter-spacing

## Layout rules

- `/index.html` + `/style.css` own the homepage only. The homepage lists
  trips but must not contain detailed itinerary logic.
- Each `/trips/<trip-slug>/` folder is self-contained: its own `index.html`
  and its own `trip.css`. Trip pages must not depend on the root `style.css`.
- `/assets/images` and `/assets/icons` hold static files only — no build
  pipeline, no dynamic loading system.
