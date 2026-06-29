# ⚡ TripCost — Gas vs. EV Trip Calculator

Compare the real cost of any trip across multiple vehicles — gas or electric — factoring in weather, terrain, traffic, and local fuel prices.

## Features
- Multi-stop trip planning
- EV range degradation modeling (temperature, terrain, weather)
- Regional gas & EV charging price estimates by ZIP code
- Saved car profiles (persisted in localStorage)
- Cost per trip, per mile, annual projection
- Break-even calculator with 10-year TCO chart
- AI-powered trip analysis

## Tech Stack
- React 18 + Vite
- Anthropic Claude API (for AI analysis)

## Local Development

```bash
npm install
npm run dev
```

## Deploy
Deployed via Vercel. Push to `main` branch to trigger auto-deploy.
