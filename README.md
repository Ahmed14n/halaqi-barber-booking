# حلاقي — Barber Booking App

An English mobile-first booking app with the brand name **حلاقي**, a centered startup logo, customer and barber accounts, and a server-backed booking flow.

## Run it

1. Install Node.js 18 or newer.
2. Double-click `Start-Halaqi.bat`.
3. It starts the local server and opens `http://localhost:4173`.

## Install it on the laptop

With the server running, open the address in Chrome or Edge and choose **Install حلاقي** or **Install app** from the browser menu. The browser may show an install icon beside the address bar. It then opens in its own app window. Double-click `Start-Halaqi.bat` whenever you need to start the server again.

## Data and sharing

Accounts, services, and appointments are stored in `data.json`. For a shared online deployment, the included `render.yaml` configures a Render web service with a persistent data disk. The server uses `DATA_DIR` so account and booking data survives redeploys. A paid Render service is required for a persistent disk; review the price shown by Render before creating the service. `localhost` on the laptop does not open the laptop's app on a phone.

Hair & Beard appointments take 90 minutes. Other services take 60 minutes. The server rejects overlapping appointments.
