# ryanelliott10.github.io

Public landing page for **Pawprints** — the living atlas of your dog's life.

| Page | URL | Used for |
| --- | --- | --- |
| Landing + support | `https://ryanelliott10.github.io/` | App Store Connect **Support URL** and **Marketing URL** |
| Privacy Policy | `https://ryanelliott10.github.io/privacy.html` | App Store Connect **Privacy Policy URL** |
| Terms of Use | `https://ryanelliott10.github.io/terms.html` | Required for the auto-renewing subscription (App Review 3.1.2) |

Static HTML, no build step. Each page is self-contained — styles inline, no
dependencies, no JavaScript except the hero tile field on the landing page.

The hero draws hexagons at the app's real tile values: one colour,
`rgb(25, 112, 51)`, with age carried entirely by alpha —
`0.65 / 0.45 / 0.25 / 0.10`. If those change in the app, change them here too
so the site keeps showing what the map actually looks like.

Icons are derived from the app icon at
`Pawprints/AppIcon.icon/Assets/icon.png` in the app repo.
