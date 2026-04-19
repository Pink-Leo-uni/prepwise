# Prepwise — Claude Code Context

> Full project knowledge (roadmap, business model, competitive analysis, parked ideas) → GitHub Wiki

## USP
"Prepwise is the only app that tells you what a meal really costs — and whether you can afford it today."
Tagline: *Eat smart. Spend less.*

## Status
- Red Bull Basement Austria 2026 — Top 30 Finalist
- Video Pitch Deadline: **Di. 21.04.2026, 12:00**
- National Final: **29.04.2026, Graz**
- Live Mockup: https://pink-leo-uni.github.io/prepwise
- Repo: https://github.com/Pink-Leo-uni/prepwise

## What Prepwise Is
Mobile-first meal prep app combining Finanzguru (budget) + Yazio (nutrition).
Core loop: scan grocery receipt → prices matched to recipes → AI chat answers "What should I eat?" based on budget + calories + fridge contents.

## Tech Stack
- Single `index.html` — vanilla JS, no framework
- Hosted on GitHub Pages (public repo required for free Pages)
- Font: DM Sans (Google Fonts)

## Design System
| Token | Value |
|---|---|
| Primary green | `#2ECC8A` |
| Yellow | `#FFD93D` |
| Red | `#FF6B6B` |
| Teal | `#4ECDC4` |
| Background | `#F2F1EE` |
| Text | `#111111` |

## Logo
Green apple with white bar chart inside. Wordmark: **Prep** (bold, #111) + wise (regular, #2ECC8A).

## App — 5 Screens
| Tab | Content |
|---|---|
| Home | Calories + weekly budget bars, macros, today's meals |
| Recipes | Recipes with price per serving + ingredient price breakdown |
| Week Plan | 7-day plan with running budget total |
| Scan | Receipt scanner → auto price matching |
| AI Chat | "What should I eat?" with budget + calorie context |

## Add Recipe Flow
Auto Import → source picker (Website / YouTube / TikTok / Instagram) → keyboard animates up → URL types over 4s → Import turns green → loading steps → form pre-filled.
Manual → empty form (name, servings, nutrition, ingredients + prices).

## Pitch Video — Supermarkt Script (final)
Setting: Supermarkt. Person A verwirrt vor dem Regal → Person B zeigt Prepwise → alter zerknitterter Kassenbon aus Hosentasche → scannt ihn → KI-Chat: "Chicken/rice/broccoli noch da, max €3 mehr, was kochen?" → KI antwortet Chicken Rice Bowl €2.80 + nur Olivenöl & Zitrone kaufen → verlässt Supermarkt mit Mini-Tüte. Closing: "Eat smart. Spend less. Prepwise."
Format: 16:9 horizontal · Englisch · max. 60 Sek.

## Goals Before Graz (29.04.)
- [ ] Video Pitch fertig + uploaded (bis 21.04. 12:00)
- [ ] Onboarding Screen (Name, Kalorienziel, Wochenbudget)
- [ ] Kassenbon-Scan Animation (grüne Scan-Linie, Preis-Tags)
- [ ] "Saved this week" Badge auf Home Screen
- [ ] Logo Splash Screen für Video-Closing

## Key Rules for Claude Code
- Always edit `index.html` directly
- After every change: `git add . && git commit -m "…" && git push`
- Mobile-first — must work on iPhone Safari
- One file, no external dependencies except Google Fonts
- Modals slide up from bottom (sheet style)
- Colors stay consistent with design system above
