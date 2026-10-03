# TripPulse

TripPulse is an AI-powered Sri Lanka travel planning and safety companion.

It helps users plan route-based group trips, discover places along the route, generate realistic itineraries, collaborate with friends, and access safety tools such as emergency calling, nearest hospital/police search, SOS alerts, and location sharing.

## Current Stage

Frontend UI prototype using HTML, CSS, and vanilla JavaScript.

## Run the prototype

Open `prototypes/html-ui/index.html` directly in a modern browser. No installation,
server, internet connection, or build step is needed. The complete prototype lives
in `index.html`, `styles.css`, and `script.js` in that folder.

The dashboard links to the welcome screen, three-step trip builder, trip workspace,
route recommendations, itinerary, illustrated map, simulated AI assistant, Safety
Center, and profile settings. Desktop uses a sidebar; phones use bottom navigation.

Trip details, selected stops, profile preferences, and light/dark mode are saved in
this browser's local storage when available. Use **Save Offline** in the itinerary
to download a text copy of the plan. Illustrations and icons are included locally.

All travel data uses the Kandy–Trincomalee sample route. Custom route names can be
saved, but they do not generate new routing data. AI replies, invitations, calls,
locations, facilities, and SOS alerts are explicitly simulated. SOS always asks
for confirmation; no call, message, or alert is sent. There is no authentication,
backend, analytics, or external API connection.

## Project Structure

```txt
trippulse/
├── docs/
├── prototypes/
│   └── html-ui/
├── apps/
│   ├── mobile/
│   └── admin-web/
├── services/
│   └── api/
└── assets/
```
