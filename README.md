# Glyn Dwfn Wireframes

Design exploration for the Barony of Glyn Dwfn website rebuild. Nineteen wireframes across three layers — landing, magazine, dashboard — narrowed to a final six.

## How to read this repo

Each `.html` file is a self-contained, browser-openable wireframe. Open `index.html` to start at the landing-page exploration.

Three kinds of files live here:

**Landing-page options** — five distinct hero treatments, intentionally varied so trade-offs would surface in review.
- `option1-fullwidth-hero.html` — hero takes full viewport, content below the fold
- `option2-split-hero.html` — image left, copy right; familiar SaaS pattern
- `option3-immersive-hero.html` — full-bleed background image with overlaid copy
- `option4-grid-layout.html` — no hero; immediate grid of entry points
- `option5-magazine-layout.html` — editorial framing with featured story up top

**Magazine layouts** — eight iterations on how the news / officers / events content section should read. `magazine-v1-v5` are the early divergent options; `v6-v8` were the surviving direction.
- `magazine-index.html` — nav hub for the eight magazine variants
- `magazine-v1-calendar.html` through `magazine-v5-news.html` — early explorations (calendar-led, carousel, gallery, officers-first, news-first)
- `magazine-v6-hybrid.html`, `magazine-v7-timeline.html`, `magazine-v8-dashboard.html` — the three carried into final review

**Dashboard layouts** — three iterations on the logged-in member dashboard.
- `dashboard-index.html` — nav hub
- `dashboard-v9-calendar-focus.html`, `dashboard-v10-event-cards.html`, `dashboard-v11-sidebar.html`

**The final six** — `final-3-index.html` collects the curated end-state: the three dashboards (v9, v10, v11) and the three magazine layouts (v6, v7, v8) that survived the cut.

## Design constraints

- **Audience**: SCA barony members — broad age range, mixed device fluency, mobile-heavy traffic
- **Brief**: replace an aging static site with something that surfaces the calendar, current officers, and event chronicles without burying any of them
- **Constraint**: HTML/CSS only at the wireframe stage — no framework lock-in until the design was settled

## Status

Wireframes complete. Implementation lives in a separate (private) repo where the final direction is being built into the production site. This repo is preserved as the design archive: the iteration trail, not the shipped output.

## License

See [LICENSE](LICENSE) if present, otherwise: design work © Tim Allen, all rights reserved.
