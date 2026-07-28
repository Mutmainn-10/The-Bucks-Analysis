# Bucks Impact Lab

An interactive Milwaukee Bucks analytics dashboard for comparing individual
players with the rotation average and exploring team performance with and
without Giannis Antetokounmpo.

## Features

- Select any displayed rotation player
- Compare points, rebounds, assists, and shooting efficiency
- Interactive rotation-distribution chart
- With-Giannis and without-Giannis availability splits
- Responsive layout for desktop and mobile
- Custom Open Graph preview image

## Data

The current version is a published snapshot of the 2024–25 NBA regular season.
Player and team statistics are based on NBA Stats and Basketball Reference.
Giannis availability results and no-Giannis aggregates are based on StatMuse.

This is an exploratory project, not a live statistical feed or predictive
model. “With Giannis” means games in which he appeared; it is not a
possession-level on/off-court calculation.

## Run locally

Requires Node.js 22.13 or newer.

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Build

```bash
npm run build
```

## Main files

- `app/page.tsx` — dashboard data, interactions, and content
- `app/globals.css` — responsive visual design
- `app/layout.tsx` — title, description, icons, and sharing metadata
- `public/og.png` — social sharing preview

## Live site

[bucks-impact-lab.mutmainn10.chatgpt.site](https://bucks-impact-lab.mutmainn10.chatgpt.site)

## Technology

React, TypeScript, Tailwind CSS, Vite, and vinext.
