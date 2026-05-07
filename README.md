# Cannes 2026 Schedule Planner

Interactive schedule planner for the 79th Cannes Film Festival, May 20–23, 2026.

Click any film to instantly see which other screenings you can still catch, factoring in travel time between venues.

## Features

- 🔍 Search by title, director, venue, or section
- 📅 Filter by day (Wed 20 → Sat 23)
- 🚶 / 🛴 Toggle between walking and scooter/bike
- ⏱ Adjustable buffer time (5–30 min)
- 🟢🟠🔴 Color-coded conflicts: doable / tight / won't make it
- 📱 Mobile-friendly

## Deploy to GitHub Pages

1. Create a new repository on GitHub (public).
2. Upload `index.html` to the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Source**, select branch **main** and folder **/ (root)**.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute.

That's it — no build step, no dependencies. Everything runs client-side.

## Notes

- Travel times are straight-line (Haversine) estimates: walking at 5 km/h, scooter at 15 km/h plus a 2-min unlock/park buffer.
- The official festival shuttle bus to Cineum is **not** modelled — with the shuttle, the Palais ↔ Cineum trip is faster than the walking estimate suggests.
- Inside the Palais des Festivals (Lumière, Debussy, Buñuel, Agnès Varda, Bazin) and inside Cineum (IMAX, Aurore, Screen X, Salle 3) we count 3 minutes per transfer to allow for re-entry queues.

Source data: official *Horaires des projections* guide of the Festival de Cannes 2026.
