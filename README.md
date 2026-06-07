# Indonesia 2026 — Trip Tracker

A personal, offline-friendly trip planner: itinerary, bookings, budget tracking and a wishlist.
Runs entirely in your browser. Your data is stored on your own device — nothing is sent anywhere.

## Put it online (free, ~3 minutes)

1. Make sure this repository is **Public** (Settings → General → scroll to "Danger Zone" → Change visibility, if needed). GitHub Pages won't serve a private repo for free.
2. Upload these three files to the repository (drag them into **Add file → Upload files**):
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
3. Commit the upload.
4. Go to **Settings → Pages**.
5. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
6. Wait about a minute, then refresh. Your app is live at:
   `https://<your-username>.github.io/<repository-name>/`

## Install it on your phone

- **iPhone:** open the URL in Safari → Share button → **Add to Home Screen**.
- **Android:** open the URL in Chrome → menu (⋮) → **Install app** / **Add to Home screen**.

It opens fullscreen like a normal app and works offline once loaded.

## Notes

- Data lives in the browser of the device you use it on. It does not sync between devices.
- The "Stays / Flights / Explore" buttons open Booking.com, Google Flights and Google Maps
  pre-filled for each stop. You book on those sites, then log the cost back in the app.
- To edit the app itself, edit `index.html`.
