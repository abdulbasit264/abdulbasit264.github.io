# abdulbasit264.github.io

[![check](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml/badge.svg)](https://github.com/abdulbasit264/abdulbasit264.github.io/actions/workflows/check.yml)
[![site](https://img.shields.io/website?url=https%3A%2F%2Fabdulbasit264.github.io&label=site)](https://abdulbasit264.github.io)

Source of my portfolio, live at **[abdulbasit264.github.io](https://abdulbasit264.github.io)**.

One hand-written `index.html`, with no framework and no build step. It includes two live demos from the ledger I built:

- **Floats are not money:** shows why `(19.99 * 10000)` truncates to `199899` and how parsing the digits keeps it exact.
- **A journal that notices edits:** a SHA-256 hash chain where editing any entry breaks the chain from that point on.

The core ideas behind both are open-sourced in [exact-ledger](https://github.com/abdulbasit264/exact-ledger).

## Checks

[`check.yml`](.github/workflows/check.yml) runs on every push, on pull requests and weekly:

- **html:** validates the page with [html-validate](https://html-validate.org) (rules in [`.htmlvalidate.json`](.htmlvalidate.json))
- **links:** finds broken links with [lychee](https://github.com/lycheeverse/lychee). The weekly run catches links that die after publishing.

GitHub Pages deploys straight from `main`.

---

[LinkedIn](https://www.linkedin.com/in/imabdulbasit) · [GitHub](https://github.com/abdulbasit264)
