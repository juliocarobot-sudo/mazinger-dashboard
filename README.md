# Mazinger Dashboard 

Retro cockpit-style personal dashboard that makes your desktop feel like you just stepped inside Mazinger Z. It tracks the “Core Four” life metrics, syncs with your existing spreadsheets/trackers, and bathes everything in chunky pixels, neon gauges, and 8-bit techno.

## Core Four Metrics (v1)
- **Power Core (Gym):** session streak + PR highlights.
- **Energy Supply Lines (Pipeline):** qualified leads added + ones moving to next stage.
- **Signal Boost (Audience):** LinkedIn follower delta, week-over-week.
- **Pilot Status (Mood):** daily 1–5 check-in with a one-word note.

## Tech Stack
- **Next.js + Tailwind** for rapid UI work.
- **Framer Motion** for cockpit animations / parallax.
- **D3-lite (Recharts/Vega)** for retro gauges.
- **Local JSON adapters** for now; pluggable adapters for Sheets/Notion/API later.

## Experience Goals
- Full-screen borderless app that can run as wallpaper on Windows (Komorebi/Wallpaper Engine) or as a kiosk window.
- CRT scanlines, parallax robot silhouette, animated rocket-punch celebrators.
- Embedded chiptune/8-bit techno loop with mute toggle.

## Roadmap
1. Scaffold Next.js app + retro design tokens (in progress).
2. Mock data + Core Four widgets.
3. Wire Google Sheet + Notion adapters.
4. Package as Windows wallpaper / kiosk app.
5. Add optional companion tablet layout.

## Dev Notes
- Keep everything modular so we can swap data sources without touching UI.
- Treat ADHD-friendliness as a requirement: minimal text, clear color coding, “next tiny action” prompts.
- Aim for <60 seconds of daily maintenance.
