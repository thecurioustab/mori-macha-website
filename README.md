# mori matcha — in motion

Animated landing page for **Mori Matcha**, built from the "mori matcha" Figma design.

## What's inside
- **Scroll story hero** – pinned section: matcha powder lifts into a cloud, sifts into the cup as it rises, the headline flips sides and Origin / Grade / Notes cards pop out of the cup.
- **Choose your matcha** – flavour switcher with ingredient tiles orbiting the cup (Classic, Mint, Berry), auto-advancing.
- **Our story** – clip-reveal photos with parallax and a spinning badge.
- **Instagram** – scrolling marquee and tilt-in photo grid.
- **Footer** – newsletter (prototype only, nothing is sent) and swaying tea leaf.

No build step: plain HTML, CSS and JavaScript. Fonts load from Google Fonts (Fraunces, DM Sans).

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Notes
- The page is designed at 1512px wide and scales to the browser width.
- Images were captured from the Figma canvas; swap in the original exports in `img/` for sharper results.
- Motion respects `prefers-reduced-motion`.
