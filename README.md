# Switch Management & Security Development — MVP 0.1

Arabic, mobile-first, static educational prototype. Includes first lesson, interactive MAC learning lab, 3-question quiz, progress tracking and IPv4 subnet calculator. No backend, dependencies, or build step required.

## Run locally
Use a static web server (service workers need localhost or HTTPS): `python3 -m http.server 8000` then open `http://localhost:8000`.

## Deploy to Vercel
Import the folder as a project or upload the files to a Git repository and import into Vercel. Framework preset: **Other**; output directory: **.** (project root). No build command required.

## Scope
This is an educational model, not a Cisco IOS emulator. MAC table learning is simplified; ARP is assumed completed before each simulated frame. Future levels are placeholders. LocalStorage saves quiz completion on the current device/browser only.
