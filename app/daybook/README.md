# Daybook

A private, single-user shift companion for living-skills instructors and direct-care aides. Log a client's routine, day plan, and goal outcomes as the shift happens, then export a clean summary to speed up writing the official record afterward.

It is **not** a system of record. Behavior/incident data with real legal or reporting weight (IRs, state-reportable incidents) still belongs in your agency's official system — this is a personal memory aid, not a replacement for it. See the in-app note on the Today tab.

## What it does

- **Today** — pick a client from your caseload, log morning routine (hygiene, breakfast, support level), build the day's schedule, mark goals accomplished / declined / not attempted, note fun activities, and jot personal notes for yourself.
- **Clients** — add, edit, archive, or delete clients and their goal lists. Archived clients keep their shift history.
- **History** — past shifts grouped by day; tap into any entry for the full detail.
- **Export** — from Today or from any History entry: a formatted summary you can copy as plain text or print / save as a PDF, to make writing your official notes faster. Personal notes are included by default and can be toggled off before printing something you'd hand to someone else.

## Data and privacy

Everything is stored **only in your browser's local storage** on the device you open it on — there is no account, no backend, no sync between devices. Nothing is sent anywhere. Client entries are meant to use initials or a made-up label, not full names, since this is meant to stay low-stakes even as a personal tool.

Clearing your browser's site data for this page will erase everything, so don't rely on it as your only copy of anything that matters.

## Running it

It's a single self-contained `index.html` — no build step, no dependencies.

**Locally:** open `index.html` directly in a browser, or serve the folder (e.g. `python3 -m http.server` from this directory) and visit it.

**On your phone, via GitHub Pages:**
1. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch.**
2. Branch: this branch, folder `/ (root)`. Save.
3. After it deploys (~1–2 min), the app is at `https://<your-username>.github.io/<repo>/app/daybook/`.
4. On your phone, open that URL and use "Add to Home Screen" for an app-like icon.

Note: GitHub Pages sites are public to anyone with the link by default, regardless of the repo's own visibility (private Pages requires a paid GitHub Enterprise plan). Fine for now since there's no real client data in play, worth remembering if that changes.

## Status

v1, personal use only: single user, no accounts, no sharing between a parent/aide/specialist. See project chat history for the reasoning behind that scope and what a v2 might add.
