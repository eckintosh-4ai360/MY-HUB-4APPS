# The Hub Mumford — Next.js Website

A full Next.js 15 website for The Hub Mumford lifestyle compound.

## Pages

- `/` — Homepage with hero, services overview, and quick links
- `/services` — All 5 services with full descriptions and pricing
- `/gaming` — Gaming lounge pricing plans, hour calculator, extras & game titles
- `/menu` — Full chop bar menu (breakfast, mains, sides, drinks) with prices
- `/book` — Barbershop booking form with service selector and WhatsApp confirmation
- `/contact` — Contact info, message form, and map placeholder

## Tech Stack

- **Next.js 15** (App Router)
- **TypeScript**
- **Tailwind CSS v4**
- **Lucide React** (icons)

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Deploy to Vercel (recommended)

```bash
npm install -g vercel
vercel
```

## Customise content

All business data lives in one file: `lib/data.ts`

- Update prices, menu items, game titles, contact info there
- No need to touch individual page files for content changes

## Before going live, update:

1. `lib/data.ts` — real phone number, address, email, Instagram handle
2. `app/layout.tsx` — meta description and keywords
3. `app/menu/page.tsx` — WhatsApp link (replace `233XXXXXXXXX` with real number)
4. Replace map placeholder in `/contact` with a real Google Maps embed

# MY-HUB-4APPS
