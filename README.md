# abdulbasit264.github.io

[![check](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml/badge.svg)](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml)
[![site](https://img.shields.io/website?url=https%3A%2F%2Fabdulbasit264.github.io&label=site)](https://abdulbasit264.github.io)

Source of my portfolio, live at **[abdulbasit264.github.io](https://abdulbasit264.github.io)**.

One hand-written `index.html` plus a headshot, with no framework and no build step. The visuals are HTML, CSS and SVG:

- **Hero:** portrait in an animated gradient ring, with floating capability chips and mouse parallax.
- **What I can do for you:** a bento grid of capabilities (AI, n8n automation, SaaS, ERP, operations, leadership).
- **See it work:** an animated walkthrough of the platform's core flow. A waybill is scanned, fields are extracted, the email drafts itself and the ledger posts. It uses sample data and respects `prefers-reduced-motion`.
- Project case studies with animated mock-ups, how I work, [exact-ledger](https://github.com/abdulbasit264/exact-ledger), experience and skills.

## Checks

[`check.yml`](.github/workflows/check.yml) runs on every push, on pull requests and weekly:

- **html:** validates the page with [html-validate](https://html-validate.org) (rules in [`.htmlvalidate.json`](.htmlvalidate.json))
- **links:** finds broken links with [lychee](https://github.com/lycheeverse/lychee). The weekly run catches links that die after publishing.

GitHub Pages deploys straight from `main`.

---

[LinkedIn](https://www.linkedin.com/in/imabdulbasit) · [GitHub](https://github.com/abdulbasit264)
