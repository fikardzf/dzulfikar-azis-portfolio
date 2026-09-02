# Dzulfikar Azis Portfolio v4.8 — Section Scroll Reveal

## Scope
Adds staged section-level scroll animations on desktop and mobile without changing the existing content, project archive behavior, or hero composition.

## Behaviour
- Hero remains the opening section and is still revealed by the preloader sequence.
- Every following main section starts visually hidden.
- A section becomes visible only when it approaches the viewport.
- Section entrance combines:
  - opacity fade-in,
  - vertical slide-up,
  - subtle blur removal,
  - light clip reveal,
  - gentle scale normalization.
- Content inside the newly revealed section enters with a short stagger.
- Mobile uses shorter distances and slightly faster timing for a more responsive feel.
- Sections that have already passed remain visible and are not repeatedly hidden/replayed.
- `prefers-reduced-motion` is respected: all staged effects are disabled for users requesting reduced motion.

## Sections Covered
- Project Archive
- Marquee divider
- About
- Selected IT Achievements
- Experience + Education
- Contact

## Regression Guard
- 10 project cards preserved.
- 4 experience entries preserved.
- Existing mobile one-project-per-swipe carousel preserved.
- Existing hero and portrait composition preserved.
- Existing assets preserved.

## Local Run (VS Code + Git Bash)
```bash
python -m http.server 8000
```
Or on Windows:
```bash
py -m http.server 8000
```
Open:
```text
http://localhost:8000
```
