# bagrupe.github.io

Public support and privacy pages for the App Store apps of the workspace family, served by
GitHub Pages from `main` at the repository root (`.nojekyll`: files are served as they are).

| Page | URL |
|---|---|
| Privacy (en) | `https://bagrupe.github.io/en/privacy.html#<app>` |
| Datenschutz (de) | `https://bagrupe.github.io/de/privacy.html#<app>` |
| Support (en) | `https://bagrupe.github.io/en/support.html#<app>` |
| Support (de) | `https://bagrupe.github.io/de/support.html#<app>` |

`<app>` is the lowercase app name (`airportcontrol`, `carmanager`, …). Each app's
`Store/privacy-url.{en,de}.txt` and `Store/support-url.{en,de}.txt` point here.

## Rules

- Static HTML only: no scripts, cookies, analytics, web fonts or third-party assets.
- This repository is the single source of truth for the public texts; app repositories hold only
  the URLs.
- English and German are updated together; German uses the informal "du".
- When an app changes how it stores or transmits data, update its section on both privacy pages
  and the "Last updated" / "Stand" date in the same change (see `AppArchitecture`, STO-04).
- A new App Store app gets a section on all four pages before its first submission.
