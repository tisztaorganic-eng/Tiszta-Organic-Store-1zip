# TISZTA Organic — Vercel Deployment

## Deploy to Vercel

### Option A: Drag & Drop (easiest)
1. Run `npm install && npm run build` locally to verify the build
2. Go to [vercel.com](https://vercel.com) → New Project → drag this entire folder

### Option B: GitHub (recommended for future updates)
1. Push this folder to a new GitHub repository
2. Import the repo in Vercel — it will auto-detect the config

### Environment Variable (required)
In your Vercel project settings → **Environment Variables**, add:

| Name | Value |
|------|-------|
| `GMAIL_APP_PASSWORD` | Your Gmail App Password (16 chars, no spaces) |

### Custom Domain
In Vercel project → **Domains** → add your domain and follow the DNS instructions.

## Local Development
```bash
npm install
npm run dev
```
