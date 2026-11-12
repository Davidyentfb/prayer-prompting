# Prayer Prompting — Team Summary

**What it is.** Prayer Prompting is the rebuilt prayer service for prayerprompting.com, operated as a charitable trust. Its promise: "When words fail, we help you find them." A visitor says what is on their heart; the site shapes it into a prayer or affirmation in the visitor's own tradition, draws on a curated library called the Brain, or places the request with a real human being who will pray for them. Every tradition is honoured, and help in crisis is always free.

**Design.** Astra — luminous gold (#D4AF37) and champagne (#F0D98C) on deep black, bone text. Gold-only. Two founder-chosen art plates carry the visuals: the gold orb over a marble temple hall (hero) and six illuminated niches holding sacred objects (the Brain header).

## What is on the page

- **The intake** — a five-step guided flow: (1) what brings you here; (2) which tradition speaks to you; (3) what form you want — a prayer written for you, an affirmation, a teaching or story, or a real human to pray for you; (4) routing to one of five care archetypes — the Grieving Heart, the Grateful Heart, the Healing Heart, the Seeking Heart, the Heavy Heart — each with a tailored room and a prayer; (5) an optional, clearly consented email or push sign-up. A safety branch stands first: signs of crisis surface the helplines immediately, before anything else.
- **The Brain** — a searchable library of attributed prayers, affirmations, teachings, and stories across twelve traditions, plus the canon of great books, the teachers, Neville Goddard, Reverend Ike, and the seven principles of universal law. House rule: every item is attributed or it does not ship; public domain first, modern works licensed or paraphrased; no closed or initiatory material.
- **The Human Prayer Portal** — ask a real person to pray for you, or join the prayer circle. Code of conduct: pray as asked, in the requester's tradition or in silence; never preach or proselytize; never contact anyone outside the portal; never attempt to handle a crisis — route it to the helplines.
- **Help Now** — verified helplines (verified November 11, 2026): 988 and Crisis Text Line (US), Samaritans 116 123 (UK & Ireland), Lifeline 13 11 14 (Australia), Canada 988, and findahelpline.com worldwide. One tap from every screen; always free; never behind a tier.
- **Membership** — Sanctuary (free forever), Supporter $5/month, Guardian $12/month (funds free access for someone in crisis), Congregations (partner tier, price at intake). Prayer, human prayer, and crisis help are never charged. Operated by a charitable trust with a published annual statement of receipts and charitable spend.

## What is live and what is not

The complete front end is built and verified: design, copy, intake, Brain, portal, helplines, tiers. In this static build the forms are demonstrations — no data leaves the page. The production build (specified in `docs/blueprint.md`) adds the server side: real push and email delivery per request, the live prayer-partner queue with moderation, payments, the consent-first data system, and the learning loop — which may improve the Brain only through human-approved additions. Prayer disclosures are never sold or shared; that is design law.

## Files in this repository

- `index.html` — the whole site in one self-contained file.
- `README.md` — the package explained.
- `docs/blueprint.md` — the full system blueprint (Brain canon and curation law, intake specification, portal rules, data system, notifications, tiers, machine-learning loop).
- `docs/team-summary.md` — this summary.

## Open decisions (founder's)

1. Where prayerprompting.com is hosted today, for the production deployment.
2. Confirmation of the tier prices ($5 / $12 are the working figures).
3. Confirmation that "Robert Neval" means Neville Goddard (the Brain is built on that reading).
4. The sending domain identity for email and push, under the trust.
