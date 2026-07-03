# Build Tohoku 2026 Trip Page

(For Claude Code)

Repository:

https://github.com/weinsting/Travel-Plans

Current project already has homepage.

Now build the first actual trip page.

Target file:

```text
/trips/tohoku-2026/index.html
```

Optional stylesheet:

```text
/trips/tohoku-2026/trip.css
```

Do NOT use frameworks.

Only:

* HTML
* CSS
* Optional vanilla JavaScript

---

# Project Goal

Build a detailed trip page for our August 2026 Japan Tohoku self-drive trip.

This page is NOT a travel blog.

This page is NOT a tourism marketing page.

This page is a beautifully organized personal travel archive.

Priorities:

* Beautiful layout
* Easy to review itinerary
* Clear logistics
* Pleasant reading experience
* Mobile responsive

Design should match existing homepage style.

Keep consistent with:

* Modern minimal design
* Sans-serif typography
* Premium but practical

---

# Typography

Use existing site typography.

Heading:

```css
font-family: Manrope, sans-serif;
font-weight: 600;
```

Body:

```css
font-family: Inter, sans-serif;
font-weight: 400;
```

No serif fonts.

---

# Page Structure

Build page in this order.

---

# Section 1 — Hero Banner

Use temporary travel image background.

Large banner.

Text overlay:

```text
Tohoku Summer Road Trip
```

Subtext:

```text
August 5 – August 12, 2026

8 Days | Couple Travel | Self Drive

Aomori • Akita • Iwate
```

Add subtle dark overlay.

---

# Section 2 — Trip Overview

Create route overview section.

Visual vertical route.

Display:

```text
Hanamaki (花卷)

↓

Kakunodate (角館)

↓

Lake Towada (十和田湖)

↓

Hachinohe (八戶)

↓

Aomori (青森)
```

Add label:

```text
Estimated total driving distance: ~500km
```

Keep minimalist.

---

# Section 3 — Accommodation Summary

Create table.

Use clean card style.

Content:

| Date     | Location    | Hotel                     |
| -------- | ----------- | ------------------------- |
| 8/5      | Hanamaki    | Hotel Grand Ciel Hanamaki |
| 8/6      | Kakunodate  | Machiya Hotel Kakunodate  |
| 8/7–8/8  | Lake Towada | Lakeside Inn Nagomi       |
| 8/9–8/10 | Hachinohe   | APA Hotel Honhachinohe    |
| 8/11     | Aomori      | Daiwa Roynet Hotel Aomori |

No heavy borders.

Minimal design.

---

# Section 4 — Daily Itinerary

Create separate card for each day.

Spacing is important.

Each day should have:

* Day number
* Date
* Route
* Activities
* Accommodation

Format:

---

Day 1 — August 5

Taoyuan → Hanamaki

Activities:

* Tigerair IT258
* Arrive Hanamaki Airport
* Immigration
* Dinner at Yoraiso
* Check in hotel

Stay:

Hanamaki

---

Day 2 — August 6

Hanamaki → Kakunodate

Activities:

* Pick up rental car
* Marukan Cafeteria
* Lake Tazawa
* Goza no Ishi Shrine
* Drive to Kakunodate

Stay:

Kakunodate

---

Day 3 — August 7

Kakunodate → Lake Towada

Activities:

* Kakunodate Samurai District
* Lunch in town
* Drive north
* Check in at Lake Towada

Stay:

Lake Towada

---

Day 4 — August 8

Lake Towada

Activities:

* Oirase Gorge Walk
* Lunch nearby
* Towada Shrine
* Lake walk

Stay:

Lake Towada

---

Day 5 — August 9

Lake Towada → Hachinohe

Activities:

* Check out
* Jogakura Bridge
* Scenic drive
* Check in Hachinohe
* Dinner at Miroku Yokocho

Stay:

Hachinohe

---

Day 6 — August 10

Hachinohe

Activities:

* Hasshoku Center
* Seafood lunch
* Kabushima Shrine
* Free evening

Stay:

Hachinohe

---

Day 7 — August 11

Hachinohe → Aomori

Activities:

* Drive to Aomori
* Return rental car
* A-FACTORY
* Apple products shopping
* Port area walk

Stay:

Aomori

---

Day 8 — August 12

Aomori → Taoyuan

Activities:

* Breakfast
* Last shopping
* Airport transfer
* EVA Air BR121

Trip ends

---

# Section 5 — Trip Highlights

Create simple grid.

6 highlights.

Display as visual cards.

Items:

* Kakunodate Samurai District
* Lake Tazawa
* Oirase Gorge
* Hasshoku Center
* Kabushima Shrine
* A-FACTORY

Can use placeholder images.

Do NOT use actual copyrighted images.

Use free stock placeholders.

---

# Section 6 — Preparation Checklist

Simple checklist section.

Items:

Flights

```text
Tigerair IT258
EVA Air BR121
```

Rental Car

```text
Hanamaki pickup
Aomori return
```

Need to confirm:

* Rental car reservation
* ETC card
* International driving permit
* Hotel reservations
* Travel insurance

Use checklist style.

---

# Footer

Display:

```text
August 2026

Designed and curated by TY & W
```

Below:

```text
Collect moments, not things.
```

---

# Design Requirements

Avoid:

* Blog style
* Long paragraphs
* Dense tables
* Generic tourism website design

Prefer:

* Large spacing
* Beautiful typography
* Card based sections
* Minimal clean layout
* Mobile responsive

---

# Navigation

Add top navigation.

Simple.

Left:

```text
Travel Plans
```

Right:

```text
Back to Home
```

Link:

```text
../../index.html
```

---

# Implementation

Create:

```text
/trips/tohoku-2026/index.html
```

If needed:

```text
/trips/tohoku-2026/trip.css
```

Commit changes after implementation.

Commit message:

```bash
git add .
git commit -m "build tohoku 2026 trip page"
git push origin main
```
