# Hi, I'm William

I build applications that help people. Most of my projects start with a real problem someone around me is dealing with: wheelchair users who can't tell if a building has a step-free entrance, or a 100+ member volunteer organization tracking service hours by hand in spreadsheets.

I'm a Computer Science student at Georgia Tech focused on frontend and full-stack web development. I care about building interfaces that are fast, clear, and easy for anyone to use, and about shipping tools that people actually keep using after launch, usually connecting by a personal experience.

## Projects

### [AccessWay — Crowdsourced Accessibility Map](https://github.com/Elliptication/hackgt-13)

A map of ramps, elevators, and accessible entrances, seeded with OpenStreetMap data and grown through user-submitted, peer-verified photos. Built at HackGT 13, where I led the frontend: the interactive map, place search, and a wheelchair-aware trip planner that routes around stairs and steep inclines. [Live site →](https://www.accessway.tech)

`Next.js` · `React` · `TypeScript` · `Leaflet` · `OpenStreetMap`

### NHS Service Hours Dashboard

My high school's National Honor Society has 100+ members who each need a set number of service hours, logged across 300+ events. Members had no easy way to see where they stood, and officers spent time answering the same questions.

I built a dashboard that syncs events straight from the society's existing Google Sheets, so officers keep working the way they already did while every member can check their own hours at any time. The board adopted it as the standard way members track their hours.

`React` · `TypeScript` · `Tailwind` · `Firebase`

### [Code Redeemer](https://github.com/Willzr9/redeemer)

International Night is one of my school's biggest events, with 1,200+ attendees and 50+ performers. Handling tickets on via invidiual email made the process slow and tedious, so I built a ticket-redemption tool where performers could redeem their code in a centralized place.

`React` · `TypeScript` · `Tailwind` · `Firebase`

### [Notestack Editor](https://github.com/Willzr9/nestly)

I wanted a notes app that let me nest pages as deeply as I needed when I was making various ideas for projects/games. However, I couldn't find one that quite matched my needs so this is my attempt at making one. I learned how to model trees in a relational database. Notestack stores pages in a self-referencing Postgres schema with recursive traversal, so whole sections can be moved or duplicated at once.

It also includes Supabase auth with Row-Level Security so each user only sees their own notes, a rich-text editor with color-coded tags, and type-safe migrations across a 7-table schema. Deployed on Cloudflare Workers. [Video Demo →](https://youtu.be/xgVeL_7mfCo)

`SvelteKit` · `TypeScript` · `PostgreSQL` · `Drizzle ORM` · `Supabase` · `Cloudflare`

### Cooking Simulator

A cooking game built in one week with a data-driven recipe system, so new foods, recipes, and appliances can be added with minimal code changes. [Video Demo →](https://youtu.be/1t7nooqjcDc)

`Unity` · `C#`
