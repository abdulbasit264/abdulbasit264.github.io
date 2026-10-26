# abdulbasit264.github.io

[![check](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml/badge.svg)](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml)
[![site](https://img.shields.io/website?url=https%3A%2F%2Fabdulbasit264.github.io&label=site)](https://abdulbasit264.github.io)

Source of my portfolio, live at **[abdulbasit264.github.io](https://abdulbasit264.github.io)**.

One hand-written `index.html`, with no framework, no build step and no images. Everything is HTML, CSS and SVG:

- **Hero:** floating glass product cards with mouse parallax.
- **See it work:** an animated walkthrough of the platform's core flow. An air waybill is scanned, the AI extracts the fields, the pre-alert email types itself and the ledger posts the invoice. It uses sample data and respects `prefers-reduced-motion`.
- The flagship case study, the other platforms, [exact-ledger](https://github.com/abdulbasit264/exact-ledger), experience and skills.

## Checks

[`check.yml`](.github/workflows/check.yml) runs on every push, on pull requests and weekly:

- **html:** validates the page with [html-validate](https://html-validate.org) (rules in [`.htmlvalidate.json`](.htmlvalidate.json))
- **links:** finds broken links with [lychee](https://github.com/lycheeverse/lychee). The weekly run catches links that die after publishing.

GitHub Pages deploys straight from `main`.

---

[LinkedIn](https://www.linkedin.com/in/imabdulbasit) · [GitHub](https://github.com/abdulbasit264)
