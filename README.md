# Leo Club of Mumbai Carter Road — Monthly Planner

A standalone, view-only calendar for Leo Club of Mumbai Carter Road (Leo District 3231 A3).
Members browse events; the club owner unlocks editing with a PIN.

## Files
- **`index.html`** — the entire app (self-contained: HTML + CSS + JS, logo embedded as a data URI). This is the file that gets served.
- `deploy/` — a local copy of `index.html` for manual drag-and-drop deploys (git-ignored).

## What's inside
- Monthly calendar grid with month/year dropdowns + arrow navigation
- Six cards: Top Priorities, Service / Leadership / Fellowship Events, Birthdays, Important Dates
- Club event schedule, recurring club events (Pitch Saturday, BoD Meeting, Carter Khabar, etc.),
  national/international observances, and member birthdays 🎂
- View-only by default; owner edit mode is unlocked with a PIN (see `OWNER_PIN` in `index.html`)
- On phones, events show as colored dots — tap a day for full details

## Editing
Open `index.html` and edit directly. Everything is in that one file:
- Club events: `DEFAULT_DATA`
- Recurring club events: `RECUR`
- Observances: `ANNUAL`
- Birthdays: `BIRTHDAYS`

## Hosting
Deployed as a static site on Netlify. If this repo is connected to Netlify,
pushing to the default branch auto-deploys `index.html`.
