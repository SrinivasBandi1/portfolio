# Srinivas Bandi — QA Automation Engineer · Portfolio

Single-page portfolio for an AI-driven quality engineering practice spanning
web, mobile, API, and performance automation.

**Live:** https://srinivasbandi1.github.io/portfolio/

## Why the page is built the way it is

A QA engineer's portfolio should survive its own review. This page is held to
the same bar I hold test frameworks to:

- **Zero dependencies, zero build step** — one HTML file. Nothing to break, nothing to patch.
- **Testable by design** — every interactive element carries a `data-testid`. Point Playwright at it.
- **Accessible** — semantic landmarks and heading hierarchy, skip link, visible focus states,
  `prefers-reduced-motion` support, labels on every form field, `aria-live` on form feedback.
- **Degrades gracefully** — no JavaScript? All content still renders (scroll-reveal is opt-in via an
  `html.js` class). Form endpoint down? Falls back to `mailto:`. Web fonts blocked? System stacks take over.
- **Honest content** — no percentage skill bars, no inflated numbers. Outcomes over output,
  and a competency matrix that admits what's still on the learning curve.
- **Search & share ready** — meta description, Open Graph / Twitter cards, JSON-LD `Person` schema, favicon.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` in a browser — there is no build step, by design.

## The stack story (short version)

Python · Selenium · Playwright · Appium · RestAssured · JMeter · Jenkins · GitHub Actions —
applied across healthcare, EdTech, and health-insurance platforms. Details, case studies,
and testing philosophy are on the page.

## Contact

- Email: bandisrinivas765@gmail.com
- GitHub: [@SrinivasBandi1](https://github.com/SrinivasBandi1)
- LinkedIn: [srinivasbandi1](https://www.linkedin.com/in/srinivasbandi1)
