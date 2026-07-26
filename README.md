# Informa Egypt — CS Knowledge Base

A lightweight, self-contained **Customer Service knowledge base** for Informa Markets exhibitions in Egypt. Static HTML/CSS/JS — no build step, no dependencies.

## Events

| Page | Event | Theme |
|------|-------|-------|
| [`home.html`](home.html) | **Animated landing** — orbiting event constellation, `EVENTS` opens the list | Dark |
| [`events.html`](events.html) | **All events** — card grid with filters (Egypt / International / Next up) | Shared |
| [`index.html`](index.html) | **Pharmaconex 2026** — 1–3 Sep 2026, EIEC | Blue |
| [`sahara.html`](sahara.html) | **Sahara Expo 2026** — 22–24 Sep 2026, EIEC | Green |
| [`templates.html`](templates.html) | **Response Templates** — 191 EN/AR reply templates | Shared |

An event switcher in each hero cross-links every event and links back to `home.html`.

## Features

- 🔎 Instant search across links, contacts, timetables and stand rules
- 📇 Contacts & routing with one-click copy
- 🗂️ 191 customer-service response templates (98 English + 93 Egyptian-colloquial Arabic) with inline-editable `[PLACEHOLDER]` fields (saved locally) and copy-to-clipboard
- 🌗 Light / dark theme (remembered)
- 📱 Responsive, section-navigated layout

## Run locally

```bash
python3 -m http.server 8788
# then open http://127.0.0.1:8788/index.html
```

## Notes

- Content classification: **General**.
- Built as a cleaner, single-file successor to the original multi-file KB.
