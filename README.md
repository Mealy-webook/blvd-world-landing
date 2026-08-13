# BLVD World — Landing Page

Interactive landing page for BLVD World, implemented from Figma.

**Live demo:** https://mealy-webook.github.io/blvd-world-landing/

## What's in it

A single-file static site (`index.html`) with no build step — open it or serve the folder.

| Section | Highlights |
|---|---|
| Preloader | Real asset-load progress, tears away into the hero intro |
| Hero | Landmark collage, animated logo, ticket pricing row |
| Zones | Story rings that open a full-screen story viewer; clickable park map |
| Map explorer | Pan/zoom map, clickable zones, typed POI pins with tooltips + detail cards, search & filters |
| Rides | Ticket-shaped cards in a draggable rail |
| Experiences / Restaurants | Product carousels with favorites |
| Gallery | Opposing marquee rows |
| Venue rules / FAQ | Rule cards, accordion |
| Global | Custom cursor, floating quick-actions dock, scroll reveals |

## Running locally

```bash
python3 -m http.server 8482
```

Then open http://localhost:8482.

## Notes

- Animation via GSAP + ScrollTrigger (CDN). All motion respects `prefers-reduced-motion`.
- The page is authored at the Figma frame width (1920px) and scales proportionally to fit narrower windows; below 900px a responsive layout takes over.
- Images and icons are exported from the source Figma file.
