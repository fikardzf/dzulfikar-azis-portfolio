# Dzulfikar Azis Portfolio v4.2 — Mobile Compact Hero & Focused Project Carousel

## Changes
- Mobile hero spacing reduced for a more compact first viewport.
- Hero heading resized and constrained so it no longer feels clipped on narrow screens.
- Profile visual reduced and positioned beside the hero heading on mobile.
- Location card hidden on mobile to keep the composition clean.
- Project Archive mobile layout changed to one focused project per swipe.
- Added scroll-snap-stop for more intentional one-by-one navigation.
- Added active / previous / next card states with subtle translate, scale, and opacity animation.
- Project counter now initializes correctly at 01 / 10 and updates as the focused card changes.
- Desktop behavior remains unchanged.

## Running
From VS Code Git Bash:

```bash
python -m http.server 8000
```

or on Windows:

```bash
py -m http.server 8000
```

Then open http://localhost:8000
