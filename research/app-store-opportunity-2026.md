# What app should we build? — App Store opportunity research (July 2026)

Research notes to pick our next app project, aimed at realistic revenue for a first-time solo developer.

## 1. Reality check first

"Large amounts of money" and "first app" rarely go together. Worth knowing before picking an idea:

- The App Store has ~1.8M+ apps; the median app makes close to nothing. Almost all App Store revenue concentrates in the top ~1% of apps (mostly games and a handful of subscription giants like TikTok, YouTube, Tinder, ChatGPT).
- Solo developers *do* build real income, but the realistic path is a **niche subscription app earning low-to-mid five figures a month**, not a "billion-dollar app" outcome — and it usually takes several tries.
- Sebastian Roehl made $602K in 2025 from apps built alone — but from 25,100 subscribers each paying $1–2/month across a portfolio, not one hit.
- A 30-year-old solo dev hit $77K/month, but only after shipping **35** micro-SaaS products (power-law: a couple of the 35 drive nearly all the revenue).
- Max Artemov hit $22K/month from a **portfolio of 30 apps** built over a year, not from one idea.

**Implication:** the winning strategy for a beginner isn't "find the one perfect idea," it's "pick a narrow, real problem, ship an MVP fast, see if anyone pays, and be willing to repeat." Plan for a portfolio mindset even if we start with one app.

## 2. What the data says about where the money is

**Category ARPU (12-month blended, 2026):**
| Category | ARPU |
|---|---|
| Dating | $9.18 |
| Fintech | $7.62 |
| Gaming (broad) | $4.21 |
| Hyper-casual games | $0.87 |

- Subscription apps retain 2.6x better at Day 30 and earn 3–4x the ARPU of ad-monetized apps.
- Health & wellness subscriptions make up ~25% of total consumer app subscription spend — the single largest subscription vertical.
- Global subscription-app spend: ~$190B in 2025, trending to ~$200B in 2026.
- Generative-AI apps: downloads doubled YoY in 2025, in-app-purchase revenue crossed $5B. ChatGPT is now the #1 grossing app on iPhone — proof that people now pay for AI subscriptions readily, which is new as of the last two years.

**Takeaway:** games have the biggest total pie but need a studio and big UA budgets to compete. For a solo beginner, the better risk/reward sits in **subscription utility apps in health, productivity, or AI-assisted niches**, where retention (not virality) drives revenue.

## 3. What actually works for solo/indie developers right now

- **Distribution, not building, is the bottleneck.** AI + no-code tooling has made MVPs cheap to build in days/weeks; the differentiator is getting users (ASO, TikTok/Reels organic content, Reddit/niche-community presence, App Store search ads for a narrow keyword).
- **"Boring" niches beat exciting ones.** The best opportunities are specific, unglamorous workflows where a professional will happily pay $10–50/month to save hours: therapist session notes + billing, real-estate listing marketing kits, small-business compliance checklists, etc. Low competition because big players ignore them; high willingness to pay because it's tied to someone's income.
- **Thin "AI wrapper" apps with no differentiation struggle.** Free-to-paid conversion is often under 5% when the product is just a UI on top of a shared model. The wrapper needs a genuinely narrow workflow, data, or integration moat, not just "ChatGPT with a nicer UI."
- **Pick a niche audience you can reach cheaply** — a community, hobby, profession, or health condition you already understand — since organic/community distribution is far cheaper than paid UA for a first app.

## 4. Three concrete app directions (ranked by fit for a first-time solo dev)

### Option A — Niche health/habit subscription app (recommended starting point)
Pick one specific, underserved health or habit niche (e.g., a tracker for a specific chronic condition, a recovery/sobriety companion, a niche fitness style) rather than a generic habit tracker.
- **Why:** Health & wellness is the largest subscription category (~25% of spend); underserved sub-niches have real Reddit/Facebook-group communities to launch into for free distribution.
- **Monetization:** $5–15/month subscription, free trial.
- **MVP scope:** achievable in a few weeks solo (tracking, reminders, simple insights). No AI required to start.
- **Risk:** must validate the community actually wants a paid app, not just a spreadsheet/free tracker.

### Option B — Narrow AI-powered workflow tool for one profession
Example: session-note-to-billing assistant for solo therapists, listing-to-marketing-kit generator for solo real-estate agents, or similar for another profession you have access to.
- **Why:** High willingness to pay (ties to income), low competition (too niche for big players), natural lock-in once a professional's workflow depends on it.
- **Monetization:** $20–100/month — much higher ARPU per user than consumer apps, so you need far fewer paying users to hit meaningful revenue.
- **MVP scope:** more build effort (needs real workflow integration, possibly compliance considerations e.g. HIPAA for health-adjacent data) — good second project once you've shipped once.
- **Risk:** requires domain access/credibility to sell into a profession you're not already part of.

### Option C — Consumer utility with an AI feature, aimed at a specific fandom/hobby community
Example: a tool solving one annoying, specific task for a community you're personally part of (a hobby, game, sport, local scene).
- **Why:** cheapest distribution (you already know where the audience lives), fastest feedback loop, lowest financial risk to test the "will anyone pay" question.
- **Monetization:** freemium, small one-time purchase or low subscription.
- **Risk:** ceiling is lower unless the community is large; best treated as a fast, low-cost first rep to learn shipping + ASO + monetization before a bigger swing.

## 5. Recommended path

1. Ship a small, real MVP in a niche you personally understand (Option A or C) within 2–4 weeks — optimize for learning distribution and payment conversion, not perfection.
2. Instrument it properly (RevenueCat or StoreKit for subscriptions, basic analytics) so we get real signal on trial-to-paid conversion.
3. If it doesn't take off, that's expected — most solo-dev portfolios need several attempts before one clicks. Reuse the shipping pipeline for the next idea.
4. Once one app has proven people will pay, consider Option B-style higher-ARPU professional tools, which have a better revenue ceiling per user.

## Sources
- [Top-Earning Apps in 2026: Which App Categories Make the Most Money](https://asoworld.com/blog/top-earning-apps-in-2026-which-app-categories-make-the-most-money/)
- [What apps make the most money in 2026? — MobileAction](https://www.mobileaction.co/blog/what-apps-make-the-most-money/)
- [50 Top-Grossing Apps (2026 Ranking) — Udonis](https://www.blog.udonis.co/mobile-marketing/mobile-apps/top-grossing-apps)
- [$602K Solo Indie Hacker App Revenue Breakdown 2026](https://www.buildmvpfast.com/blog/602k-revenue-solo-indie-hacker-app-portfolio-breakdown-2026)
- [Solo Dev 35 Micro SaaS Apps $77K Month: Case Study](https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026)
- [Indie Developer Market 2026: Complete Industry Analysis — Fungies.io](https://fungies.io/indie-developer-market-analysis-2026-5/)
- [State of Subscription Apps 2026 — RevenueCat](https://www.revenuecat.com/state-of-subscription-apps)
- [The State of Subscription Apps in 10 minutes — RevenueCat](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026/)
- [Mobile App Monetization Statistics in 2026 — App Verticals](https://www.appverticals.com/blog/mobile-app-monetization-statistics/)
- [Top 50 App Niches to Look for in 2026 — Idea Usher](https://ideausher.com/blog/top-50-app-niches/)
- [12 Low Competition SaaS Niches for 2026 — Trend Seeker](https://trend-seeker.app/blog/low-competition-saas-niches-2026)
- [6 AI Wrapper Strategies That Print $10k/Month — Startup Stash](https://blog.startupstash.com/6-ai-wrapper-strategies-that-print-10k-month-even-if-you-arent-a-dev-f76ff5691ed3)
- [AI Wrapper Business Model: How to Price and Monetize AI Apps in 2026 — Dodo Payments](https://dodopayments.com/blogs/ai-wrapper-business-model-monetization)
