# Smart Reply

AI-powered iMessage reply assistant. Reads your conversations, generates reply options in your voice, and lets you send with a tap.

## Deploy

```bash
# Install Vercel CLI (one time)
npm i -g vercel

# Deploy
vercel --prod
```

## Update

Push changes to the repo. Vercel auto-deploys on every push.

## Local Dev

```bash
npm run dev
# Open http://localhost:3000
```

## How It Works

1. The Cowork Smart Reply skill reads your Messages app
2. Generates reply options in your voice
3. Updates `public/index.html` with real conversation data
4. Pushes to repo → Vercel auto-deploys
5. Open the app on your phone and tap to reply
