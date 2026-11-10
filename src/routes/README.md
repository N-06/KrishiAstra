# KrishiAstra

KrishiAstra is a farm-to-market web app prototype. We built it to explore how farmers can compare local market prices, decide whether to sell or store their harvest, and find buyers.

## Features

- **Farmer dashboard:** View crop plans, farm advisories, and estimated profit.
- **Market prices:** Browse sample mandi prices and buyer listings.
- **Sell vs. store:** Compare selling now with storing for 30, 60, or 90 days. The calculator accounts for storage costs and spoilage.
- **Buyer dashboard:** Browse farmer listings and send purchase inquiries.

## Tech stack

React, TypeScript, TanStack Start, Vite, Tailwind CSS, and Recharts. The app serves its own `/api` routes and uses a local JSON file for storage.

## Run locally

npm install
npm run dev

Open `http://localhost:8080` or the URL printed in the terminal.

## Project structure

- `src/routes/index.tsx` — Main page and dashboard navigation
- `src/components/views/` — Farmer and buyer dashboard screens
- `src/lib/api-client.ts` — Frontend requests to the API
- `src/server/api-handler.ts` — API routes
- `src/server/db.json` — Sample data and local storage

## Prototype limits

Market prices come from sample data, and the sell-vs-store calculator uses preset future prices.