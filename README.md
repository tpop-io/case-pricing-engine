**Problem:** Pricing proposals took ~30 min to benchmark; win-rate visibility was low.
**Outcome headline:** (fill after launch)
**Role:** Product Manager. Drove discovery → strategy → delivery → analytics.
**Skim links:** [One-pager](SUMMARY-ONEPAGER.md) · [Outcomes](OUTCOMES.md) · Repo map below.

## Repo map
- /discovery — problem, personas, research, insights
- /strategy — NSM, KPIs, PRD, roadmap, prioritization, risks
- /design — wireframes, journeys, prototypes
- /delivery — architecture, data model, API, NFRs, security
- /experiments — plan, scripts, results & decisions
- /analytics — event spec, dashboards, snapshots (anonymized)
- /metrics — metric log, ROI calc, retention/adoption
- /retro — weekly status, retro, next-iteration plan
- /samples — sanitized data/code for reviewers
- /evidence — decision log, approvals, PRs/commits, redacted notes# case-pricing-engine

## Use and stack
V0: import historical proposals → fast filter → percentile fee suggestion → CSV export.
Stack: Next.js (App Router), Postgres (Supabase), Tailwind, shadcn/ui.

## Dev
npm i
npm run dev

## Migrations
See /sql (ordered). Add a simple runner in /scripts or use your favorite tool.

## Env
Copy .env.example → .env and fill Postgres + NextAuth + Supabase keys.
