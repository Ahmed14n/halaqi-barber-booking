# حلاقي — Barber Booking App

An English mobile-first booking app with the brand name **حلاقي**, a centered startup logo, customer and barber accounts, and a server-backed booking flow.

## Run it

1. Install Node.js 18 or newer.
2. Double-click `Start-Halaqi.bat`.
3. It starts the local server and opens `http://localhost:4173`.

## Install it on the laptop

With the server running, open the address in Chrome or Edge and choose **Install حلاقي** or **Install app** from the browser menu. The browser may show an install icon beside the address bar. It then opens in its own app window. Double-click `Start-Halaqi.bat` whenever you need to start the server again.

## Data and sharing

On this laptop, accounts, services, and appointments are stored in `data.json`. The server must stay running to use the app. A customer and barber on different devices need a public HTTPS address and a shared hosted database; these are not configured yet. `localhost` on the laptop does not open the laptop's app on a phone.

Hair & Beard appointments take 90 minutes. Other services take 60 minutes. The server rejects overlapping appointments.
