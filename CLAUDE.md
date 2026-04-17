# Prepwise — Project Context for Claude Code

## What is Prepwise?
A mobile-first meal prep app (iOS/Android vision) that combines:
- **Finanzguru** (expense tracking) + **Yazio** (nutrition tracking)
- Users scan grocery receipts → prices get matched to recipes automatically
- AI chatbot answers "What should I eat today?" based on budget + nutrition goals

## Tech Stack
- Single HTML file: `index.html` (no framework, vanilla JS)
- Hosted on GitHub Pages: https://pink-leo-uni.github.io/prepwise
- Repository: https://github.com/Pink-Leo-uni/prepwise

## Design System
- Primary color: #2ECC8A (green)
- Secondary: #FFD93D (yellow), #FF6B6B (red/orange), #4ECDC4 (teal)
- Background: #F2F1EE
- Font: DM Sans (Google Fonts)
- Style: Clean, energetic, mobile-first

## Logo
Green apple with white bar chart bars inside + wordmark:
- "Prep" bold (#111111) + "wise" light (#2ECC8A)
- SVG path for apple body:
  M36 20 C24 20 14 29 14 41 C14 55 23 64 36 64 C41 64 44 61 49 61 C54 61 57 64 62 64 C75 64 84 55 84 41 C84 29 74 20 62 20 C57 20 54 23 49 23 C44 23 41 20 36 20Z

## App Screens (5 tabs)
1. **Home** — Calories + weekly budget overview, macros (protein/carbs/fat), today's meals
2. **Recipes** — Recipe list with real local prices from receipts, ingredients breakdown
3. **Week Plan** — 7-day meal schedule with budget tracker
4. **Scan Receipt** — Camera scan of grocery receipts, auto price matching
5. **AI Chat** — "What should I eat?" chatbot with quick replies

## Add Recipe Flow
1. "+ Add recipe" button → modal opens
2. Choice: **Auto Import** or **Manual**
3. Auto Import → source selection (Website/YouTube/TikTok/Instagram)
4. Clicking a source → iPhone keyboard animates up → link types itself over 4 seconds
5. Import button turns green → loading animation → Manual Edit screen pre-filled
6. Manual: empty form (name, servings, nutrition, ingredients + prices)

## Target Users
Students, young professionals, fitness-conscious people with limited budget

## Current Status
- Working interactive mockup (not a real app yet)
- No backend, no database — pure frontend demo
- GitHub Pages live

## Competition Context
Red Bull Basement 2026 Austria — Top 30 finalist
Video pitch deadline: Tuesday 21.04.2026 12:00
National Final: 29.04.2026 in Graz

## How to Work on This Project
- Always edit index.html directly
- After changes: git add . && git commit -m "description" && git push
- Test locally by opening index.html in browser
- The app must work on mobile (iPhone Safari)

## Key Rules
- Keep everything in ONE index.html file
- No external dependencies except Google Fonts + DM Sans
- All screens navigate via bottom nav tabs
- Modals slide up from bottom (sheet style)
- Colors must stay consistent with design system above

## Core Value Proposition
"Prepwise is the only app that tells you what a meal really costs — and whether you can afford it today."
- Not just recipes, not just nutrition, not just budget — the intersection of all three
- Priority order: Cost per meal + nutrition + budget overview → receipt scanner → AI chat → everything else

## Product Roadmap

### Phase 1 — MVP (now)
Cost per meal + nutrition values + weekly budget overview. One app, one clear benefit.

### Phase 2 — Receipt & Prices (Month 2-3)
- Receipt scanner for personal prices
- Prices from major supermarket chains integrated (Rewe, Lidl, Aldi, etc.)

### Phase 3 — B2B Monetization (Month 4-6) [PARKED — do not build yet]
> ⚠️ Intentionally parked. Do not implement until Phase 2 is complete.
- Supermarket chains promote products inside the app
- Users scan receipt as proof of purchase → cashback credited
- Prepwise earns commission per verified purchase
- Business model: B2B with supermarket chains, not B2C with users

### Phase 4 — Data & Insights (long-term) [PARKED]
> ⚠️ Parked. Long-term vision only.
- Anonymized purchase data as second revenue stream for supermarket chains
