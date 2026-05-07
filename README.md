# Cannes 2026 Schedule Planner

Interactive schedule planner for the 79th Cannes Film Festival, May 20–23, 2026.

Click any film to instantly see which other screenings you can still catch, factoring in travel time between venues.

## Features

- 🔍 Search by title, director, venue, or section
- 📅 Filter by day (Wed 20 → Sat 23)
- 🚶🛴🚌 Three transport modes: walking, scooter/bike, or the official festival shuttle (Palais ↔ Cineum)
- ⏱ Adjustable buffer time (5–30 min)
- 🟢🟠🔴 Color-coded conflicts: doable / tight / won't make it
- 🎨 Each section has its own colour stripe and tag (Compétition, Un Certain Regard, Directors' Fortnight, etc.)
- 🎩 Black-tie indicator for gala premieres in the Grand Théâtre Lumière
- 📱 Mobile-friendly

## Deploy to GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html` (and optionally this `README.md`) to the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Source**, select branch **main** and folder **/ (root)**.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute.

That's it — no build step, no dependencies. Everything runs client-side.

## Notes on data and accuracy

- **Travel times** are straight-line (Haversine) estimates: walking at 5 km/h, scooter at 15 km/h plus a 2-min unlock buffer. The festival shuttle is modelled at ~18 min including average wait time, and only between the Palais and Cineum (the only campus-to-campus route it serves).
- **Inside the Palais des Festivals** (Lumière, Debussy, Buñuel, Agnès Varda, Bazin) and inside Cineum (IMAX, Aurore, Screen X, Salle 3) we count 3 minutes per transfer to allow for re-entry queues.
- **Black tie (gala) marker** is applied to the headline 19:00 / evening-time premieres in the Grand Théâtre Lumière. This is a heuristic — for any specific screening, check the festival's official guidelines.
- **Source data**: official *Horaires des projections* guide of the Festival de Cannes 2026.
