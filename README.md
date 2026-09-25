# UCI GeoGuesser Frontend

Next.js app for the UCI campus guessing game. Players see a campus photo and drop a pin on the map.

Live app: [ucigeoguesser.vercel.app](https://ucigeoguesser.vercel.app/)

API repo: [UCIGeoGuesser/backend](https://github.com/UCIGeoGuesser/backend)

## Setup

```bash
npm install
```

Create `.env.local`:

```bash
NEXT_PUBLIC_BACKEND_URL=http://localhost:18080
NEXT_PUBLIC_MAX_ROUNDS=5
NEXT_PUBLIC_TIME_LIMIT=60
```

`NEXT_PUBLIC_BACKEND_URL` is required. The round and time values are optional.

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy

The app is deployed on Vercel. Set the same `NEXT_PUBLIC_*` variables in the Vercel project.
