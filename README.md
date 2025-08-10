NexGen BPO AI — Investor-ready demo (FINAL)

What's included:
- Full client (React) and server (Node/Express).
- Voice AI trial endpoint wired to ElevenLabs (uses ELEVENLABS_API_KEY from .env).
- Simulated inbound/outbound call demo UI.
- Booking form that saves to server/data/bookings.json.
- English/Dutch auto-detect (client-side with IP fallback).
- Embedded video reel (click-to-play popup) using provided YouTube shorts.
- Branding: NexGen BPO AI (white + green accent). Replace logos in client/public/assets as needed.
- Dockerfile and Procfile for Render deployment.

Quick deploy to Render (recommended: Docker):
1. Create a new Render Web Service -> Deploy from ZIP -> upload this file.
2. Build command: leave empty (Docker will be used) or use Node build if selecting Node.
3. Start command (if NOT using Docker): `npm start`
4. If using Docker, Render will use Dockerfile included.

Local dev:
1. npm install
2. cd client && npm install
3. npm run build
4. npm start (from project root)
