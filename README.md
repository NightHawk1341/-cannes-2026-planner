# Cannes 2026 Schedule Planner

> ⚠️ **Unofficial planner** — not affiliated with the Festival de Cannes or its organisers.

Interactive schedule planner for the 79th Cannes Film Festival, May 20–23, 2026.

Click films to build your daily plan. The planner automatically locks any screening that conflicts with what's already in your plan, factoring in travel time between venues.

## Features

- 🔍 Search by title, director, venue, or section
- 📅 Filter by day (Wed 20 → Sat 23)
- 🎯 Filter by festival section (Compétition, Un Certain Regard, Directors' Fortnight, Critics' Week, ACID, Cannes Classics, Cinéma de la Plage…)
- 🏛 Filter by individual venue (checkbox list)
- ➕ Multi-select: build a plan with several films at once
- 🔒 Conflicting screenings are auto-locked — the planner won't let you book impossible combinations
- 🚶🛴🚌 Three transport modes: walking, scooter/bike, festival shuttle (Palais ↔ Cineum)
- ⏱ Adjustable buffer time (5–30 min)
- 🎩 Black-tie indicator for evening Lumière galas and the closing ceremony
- 📱 Mobile-friendly

## Deploy to GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html` (and optionally this `README.md`) to the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Source**, select branch **main** and folder **/ (root)**.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute.

That's it — no build step, no dependencies. Everything runs client-side.

## Notes on data and accuracy

- **Travel times** are straight-line (Haversine) estimates: walking at 5 km/h, scooter at 15 km/h plus a 2-min unlock buffer. The festival shuttle is modelled at ~18 min including average wait time, and only between the Palais and Cineum.
- **Inside the Palais** (Lumière, Debussy, Buñuel, Agnès Varda, Bazin) and inside Cineum (IMAX, Aurore, Screen X, Salle 3) we count 3 minutes per transfer to allow for re-entry queues.
- **Black tie** is applied to evening sessions in the Grand Théâtre Lumière and the festival closing ceremony.
- **Source data**: official *Horaires des projections* guide of the Festival de Cannes 2026.
