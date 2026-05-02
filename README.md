# WanderAI

> AI travel planner and itinerary builder

## Features
- Itinerary generation
- Budget tracker
- Hotel recommendations
- Local tips
- Packing lists

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Deployment (Vercel)
1. Push this repository to GitHub.
2. Import the project in Vercel.
3. Configure the production environment variables listed below.
4. Deploy (Vercel runs `npm run build`).

## Environment Variables
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## Pricing
| Plan | Price |
|------|-------|
| Free | $0/mo |
| Pro  | $12/mo or $99/yr |

## License
MIT (c) 2026 Aurora Rayes LLC
