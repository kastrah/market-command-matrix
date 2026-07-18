---
name: market-command-matrix
description: >
  Classify competitors by market mindshare and resource strength, then choose
  whether to attack, monitor, harvest, ignore, or partner. Structured competitor
  judgement for market mapping, campaign planning, positioning, go-to-market
  prioritisation, content strategy, or partnership decisions.
version: 2.0.0
author: Kastrah
license: MIT
tags: [competition, strategy, positioning, market-intelligence, go-to-market]
metadata:
  hermes:
    tags: [competition, strategy, positioning, market-intelligence, go-to-market]
---

# Market Command Matrix

## Overview

Use this skill when you need structured competitor judgement. The goal is to build judgement, then decide what to do about each player. Intelligence is upstream of action.

This skill classifies competitors on two axes (market mindshare and resource strength), assigns a strategic category (attack, monitor, harvest, ignore, partner), selects a playbook, and identifies whitespace. It produces decisions, not descriptions.

## Source scope

The Market Command Matrix is condensed from Patrick Campbell's Competitor Research and Strategy (2023): https://patticus.com/2023/12/16/competitive-research-playbook/


This skill is a decision framework that uses customer-led evidence to classify competitors and prescribe action.

## When to use this skill

Use market-command-matrix when the user asks to:

- map the competitive landscape for a market, category, or niche
- decide which competitors to attack, monitor, harvest, ignore, or partner with
- prioritise competitive responses for campaign planning or go-to-market
- identify whitespace and positioning opportunities
- build battlecards, comparison pages, or wedge campaign targets
- evaluate whether a new entrant changes the competitive picture
- decide whether to partner with or compete against a specific player
- refresh an existing competitor map with current signals

Do not use it for:

- **Tactical competitor content** (what they posted last week, their latest ad) — use web monitoring or the signal monitor source map
- **Product feature comparison** — that's a feature matrix, not a command matrix
- **Internal strategy without competitive context** — this skill requires external evidence
- **One-off competitor lookups** — this is for building a structured map, not answering "what does X do?"
- **Content strategy without a competitive angle** — use the content pipeline or blog-audit instead

## Inputs to collect before running

Before starting the analysis, gather:

1. **Your brand/product** — what you sell, who it's for, what job it does
2. **The market or category** — the specific space you're mapping (not "all of tech" — be narrow)
3. **Customer view** — if available: unaided recall data, survey results, review mining, social listening. If not available, say so and flag it as the first gap to fill.
4. **Competitor signals** — for each known player: website, messaging, pricing, social presence, hiring, funding, partnerships, app store reviews, press mentions
5. **Your own resource level** — honest score on the same 1-5 scale you'll use for competitors
6. **Strategic context** — what decision this map needs to inform (launch? reposition? partnership? content theme?)

If critical details are missing (especially customer view), proceed with what's available and flag gaps. Do not invent customer data.

## The model

Classify each player using two axes:

### 1. Market mindshare

How aware is the market of this player?

- Do customers mention them unprompted?
- Do they own search, social, press, community, or category conversation?
- Are they the default comparison when buyers think about the problem?
- Score 1-5: 1 = invisible, 5 = category default

**Critical rule:** Market mindshare must come from customer evidence, not internal anxiety or boardroom repetition. If you have no customer data, say so and score with low confidence.

### 2. Resource strength

How many resources are they dedicating to winning this specific market?

- Funding, team size, distribution, technical capability, partnerships, operational depth, focus
- Score relative to market dedication, not company size alone
- A large company with a broad product may be resource-weak in your niche
- A small company focused entirely on the market may be resource-strong
- Score 1-5: 1 = minimal investment, 5 = all-in

**Critical rule:** Score your own company first on the 1-5 scale, then score others relative to your market focus and execution capacity. This calibrates your judgement.

## Decision categories

Map each player to one category based on their mindshare + resource position:

| Category | Mindshare | Resources | What to do |
|---|---|---|---|
| **All-out attack** | High | High | Sharp wedge, clear proof, channel discipline. Build comparison pages, battlecards, wedge campaigns. Expect retaliation. |
| **Monitor** | Low | High | Track until their signal changes. Do not overreact early. |
| **Harvest** | High | Low | Use their awareness to educate the market, create doubt around their gaps, make switching easy. |
| **Ignore** | Low | Low | Do not spend strategic energy unless they reveal a useful customer signal or move quadrant. |
| **Partner** | Complementary | Complementary | Explore integration, referral, co-marketing, bundling, or distribution. |

## Competitor set mapping

Organise the market into four buckets. Matrix placement must be based on what customers know, use, and can easily find — not internal org charts.

1. **Direct competitors** — same buyer, same job-to-be-done, similar promise
2. **Adjacent competitors** — solve part of the same problem or own a neighbouring workflow
3. **Substitute behaviours** — manual, informal, or existing behaviours customers use instead
4. **Ecosystem actors** — media, communities, platforms, regulators, service providers, agencies, distribution partners, infrastructure players

## Step-by-step process

### Step 1: Define the market boundaries

- What category or problem you're mapping
- Who the buyer is
- What job-to-be-done the product fulfils
- Geographic or segment scope

If this is vague, the matrix will be vague. Tighten before proceeding.

### Step 2: Sweep for competitors

Use a customer-led approach. The core question is unaided recall:

> When you think of [CATEGORY], what is the first product that comes to mind?

Then add aided questions for recognition, usage, recommendation, and value/dissatisfaction.

**Survey sources (easiest to hardest):**
1. Customers and prospects in your database (anonymous to reduce bias)
2. Paid market panelists
3. Prospects outside your database (subject to compliance)
4. Competitor customers from public logos, case studies, reviews, social proof
5. Targeted ads sending respondents to the survey

**Bias controls:**
- Unaided questions before aided questions
- No anchoring around your brand or a named competitor
- Neutral or anonymous research framing
- No raffle incentives unless each respondent is directly paid

If you cannot run a survey, use proxy signals: search data, social listening, review mining, app store rankings, press coverage, community mentions. Flag that you're using proxy data.

**Survey send best practices:**

- Plain text emails get roughly 30% higher response rates than designed emails
- Send early morning based on recipient timezone
- Send a follow-up bump 3 days after initial send for non-openers
- Schedule a thank-you message for survey completers
- Do not use raffle prizes to incentivise responses — it rarely works unless each respondent is directly paid

### Step 3: Collect signals for each player

For each priority competitor, gather:

- Website and landing-page messaging
- Product pages and feature claims
- Social profiles and recent themes
- Visible ads or campaign pushes
- App store listings and reviews (if relevant)
- Pricing and onboarding flow
- Press mentions and partnerships
- Hiring, funding, and expansion signals
- SEO and blog topics
- Customer comments, FAQs, repeated objections

**People-level signals** (go deeper than company-level):

- Key employee social media — junior employees say too much, executives telegraph strategy, disgruntled staff signal internal problems
- Departing employees — tend to be loose-lipped; reach out for conversations
- Glassdoor reviews — not a quality signal, but a treasure trove of internal strategy shifts, culture problems, and leadership issues
- Job postings — shifts in descriptions reveal strategic priorities; titles of new director/VP/C-level hires show where resources are moving
- Board member communications — board advice cascades into companies; track what they share publicly

**Separate verified evidence from assumptions.** State the source and date for each signal. If you're guessing, say so.

### Step 4: Score and place on the matrix

For each player:

1. Score market mindshare (1-5) with evidence and confidence level
2. Score resource strength (1-5) with evidence and confidence level
3. Assign category: attack, monitor, harvest, ignore, or partner
4. Write a one-line rationale
5. State what would change the placement (trigger)

**Score your own company first.** Then score competitors relative to your position.

### Step 5: Build the Attack Vector Grid

Before selecting playbooks, distil your research into a structured vulnerability document for each priority competitor. Answer two sets of questions:

**How the customer views the product:**

- What are the top product weaknesses customers complain about? (these become pressure points for attack playbooks)
- What are the top strengths customers praise? (you need to match or reframe these)
- What do customers want that you solve (or could solve) that the competitor treats as an afterthought? (these expose vectors of attack)

**How the competitor's leadership team views the product:**

- Which features or strengths do leaders care about most? (knowing what they think is their strength lets you threaten it or align with it for partnerships)
- What makes them feel insecure? (people act erratically when minimising insecurity — rushing, overspending, overcorrecting)
- Who are your joint enemies? (everyone fears someone; joint enemies create openings for conversations and attacks)

You will not be certain about all of this. You do not need to be. The grid surfaces themes of vulnerability. Those themes are enough to exploit. You will iterate over time as revenue data tells you what is working.

### Step 6: Select playbooks

Choose one primary motion per priority player. Use your Attack Vector Grid to select playbooks that press on the vulnerabilities you identified.

**Attack playbooks:**

- **Comparison page** — for every high-mindshare competitor, build a landing page that compares you head-to-head. Include customised hero, feature tables, pricing comparison, customer testimonials from switchers, and something good about the competitor (builds trust). These become your highest-converting pages when done right.
- **Search campaigns** — bid on competitor brand names in paid search (10-35% of their traffic comes from people searching their name instead of typing the URL). Build organic landing pages for "[competitor] alternative" queries. High ROI, low volume, very targeted.
- **Wedge campaign** — see Wedge Strategy below.
- **Sales battlecards** — internal slides for each competitor covering: who uses them, why you win, why you lose, common objections and responses. Consider proactive advisory-driven sales: share your competitive research in the sales process to become a trusted advisor rather than just another vendor.
- **Target competitor customer lists** — identify competitor customers through firmographic tools, conference sponsors, forums, and review sites. Run targeted outbound or ad campaigns that implant doubt about the competitor, then alleviate that doubt with your product.
- **Ad campaigns** — targeted ads that press on competitor weaknesses without necessarily naming them. Dove's "deserve better" campaign never mentions competitors but reframes the category. Be aggressive but honest — stretching the truth damages your brand.

**Defend playbooks:**

Choose your defensive posture based on the attacker's relative mindshare:

- **Above the fray** (attacker has less mindshare) — do not give them oxygen by responding publicly. Keep conversations private. Maintain a paper trail of your reasonableness. Respond publicly only if they escalate, and only to show you offered to resolve it privately.
- **All-out counterattack** (similar mindshare) — match their energy. Use all attack playbooks. Deploy legal counsel if they misrepresent your product. Do not hide behind unnamed references — customers know who you are talking about. Lean into the directness.
- **Play the victim** (attacker has far more mindshare) — rally your customers and community against the bully. Use traditional and social media. The goal is not to win a debate about merits — it is to make the competitor look unreasonable and apply public pressure. Humans do not like being associated with bullies.

Additional defend playbooks:

- Retention messaging and customer education
- Objection handling and proof bank
- Switching-cost reinforcement

**Harvest playbooks:**

- **Partnership** — forge partnerships with high-mindshare, low-resource competitors. Find the plane of partnership that aligns with their incentives (often revenue or gap-filling). Incept the idea through customer demand, not your own pitch. Start small, prove value, expand.
- **Mini-product** — build a small free tool targeted at a specific competitor vulnerability. The tool acts as a trojan horse: it solves one problem, captures the user, and creates a path to your full product.
- **Migration services** — make switching effortless. Build automated import tools or offer manual migration services. Remove every objection related to data continuity, setup effort, and learning curve. If a competitor's contract is a barrier, offer contract buyouts: match their remaining contract length with free time on your product.
- **Gap content** — create content that exposes the gap between what the competitor promises and what customers actually experience.
- **Integration strategy** — build integrations with the competitor's product to make switching easier and get listed in their app store.

**Monitor playbooks:**

- Monthly watchlist and trigger tracking
- Funding, hiring, partnership alerts
- Messaging change log

**Partner playbooks:**

- Ecosystem integration plan
- Referral path, joint campaign, audience swap
- Co-branded trust proof

### Step 7: Identify whitespace and positioning

Extract the gap. Look for:

- Underserved audience
- Weak or vague promise
- Missing proof
- Poor follow-through
- Confusing CTA
- Over-education without action
- Action without reassurance
- Product promise without operational depth
- Trust gap
- Channel mismatch

Convert each gap into a decision or action.

### Step 8: Interpret market shape

Identify the market shape:

- **Intensely fragmented** — no clear winner. Grow fast if the market is large or early. Reconsider if small or low-value.
- **Challenger** — one or two big players dominate. Attack the leaders; consider partnering with other challengers.
- **Ancient** — old incumbents with stagnant products or poor customer experience. Harvest aggressively.
- **Mature** — active market with entrants, exits, and competitors across quadrants. Run offensive and defensive playbooks.

## Wedge Strategy

The Wedge Strategy is the highest-leverage attack playbook for All-out Attack competitors. It works by identifying an area where competitors are weak and insecure, making that area your core identity, and forcing the market to care about it through message discipline.

**Finding your wedge:**

A good wedge meets three criteria:

1. **Fundamental value** — the wedge addresses something customers consider essential to the product category, not a nice-to-have
2. **Low competitor priority** — competitor product teams are not focusing on it (often because they are busy shipping features they think matter more)
3. **Technical barrier** — achieving it requires significant effort, which prevents competitors from quickly closing the gap

Look at your Attack Vector Grid. The weaknesses customers complain about most, especially when competitors are ignoring them, are your wedge candidates.

**Forcing your wedge on the market:**

Once you choose a wedge, talk about it constantly. Every blog post, every sales message, every interview. Two axes of pressure:

1. **Sow doubt with customers** — make customers question whether their current solution is good enough on the wedge dimension. Build mini-tools that highlight what they are missing. Run accuracy audits, free assessments, or comparison tools that prove your wedge.
2. **Convince market influencers** — push your wedge into industry reports, analyst conversations, influencer reviews, and creator content. When analysts include your wedge as a comparison category, you have changed the narrative.

**Sign it is working:** competitors start addressing your wedge in their own sales and marketing. They are reacting to you. Double down. Moving a market takes 9 months to 3 years. When competitors shift resources to address your wedge, they weaken their original strengths. You are now leading.

## Monitoring and the Judgment Log

Once the matrix is built and playbooks are running, shift to monitoring. The goal is to build judgement over time by tracking changes and testing your predictions.

**Judgment Log** — for each priority competitor, record monthly or quarterly:

- What did I predict last time? What turned out right? Wrong?
- What do they seem focused on? Has that changed?
- Where do they seem strong? Weak?
- What do I think they will do next?
- Any notable conversations with people connected to them?

After six months of monthly reviews (6 hours) or four quarters (4 hours), you will understand your market better than anyone.

**Monitoring cadence:**

- Global sweep (full matrix refresh): quarterly at scale, every 6 months when starting
- Signal monitoring (dashboards, profiles, media labels): monthly or quarterly
- Judgment Log review: monthly or quarterly, same cycle as monitoring

**What to review each cycle:**

- Market Intelligence Deck — growth trends, sentiment shifts, new entrants
- Competitor Dashboard and Profiles — headcount, NPS, feature changes, customer lists
- Media Monitoring Labels — marketing messages, job postings, social media, press

## Output format

### Full analysis

1. **Strategic thesis** — one sentence on what the market map means
2. **Competitor set** — direct, adjacent, substitute behaviours, ecosystem actors
3. **Evidence table** — player, signal, source, date checked, confidence, implication
4. **Matrix placement** — mindshare score, resource score, category, rationale, trigger
5. **Whitespace and positioning** — what the market is missing, what the brand can credibly own, what not to copy
6. **Recommended actions** — action, owner, dependency, output, deadline/checkpoint
7. **Market shape** — fragmented / challenger / ancient / mature, and what it means
8. **Milestones and triggers** — what to monitor, what would change the decision, when to revisit

### One-page decision memo

When the user needs a compressed format:

- **Player:** name
- **Placement:** attack / monitor / harvest / ignore / partner
- **Evidence:** 1-2 strongest signals
- **Meaning:** what it changes strategically
- **Action:** one concrete next move
- **Trigger:** what to watch next

## Common pitfalls

1. **Scoring mindshare from internal anxiety instead of customer evidence.** "They keep showing up in our mentions" is not mindshare data. Unaided recall is. If you don't have customer data, say so and score with low confidence.

2. **Treating company size as resource strength.** A $2B company with 3 people on your niche is resource-weak there. A 10-person startup that only does what you do is resource-strong. Score market dedication, not headcount.

3. **Placing every competitor in "attack."** If everyone is high-mindshare and high-resource, your market definition is too broad or your scoring is biased. Tighten the category or recalibrate.

4. **Building the matrix without whitespace.** A matrix that classifies competitors but doesn't extract the gap is half done. The positioning insight is the payoff.

5. **Skipping the verification step.** If you can't point to a source for a mindshare or resource score, it's an assumption. Mark it as one.

6. **Running this for a single tactical question.** "Should we run a comparison ad against X?" is a tactical call. This skill is for building the map that informs those calls, not for answering them individually.

7. **Forgetting to score your own company first.** Without your own position as anchor, relative scoring drifts. Score yourself honestly, then place others relative to that.

8. **Using this skill for content strategy without a competitive angle.** If the task is "write a blog post" or "plan our content calendar," use the content pipeline or blog-audit. This skill is for when competitive positioning is the actual question.

9. **Publishing the matrix without separating verified vs assumed.** Every signal needs a source and confidence level. An analysis that treats guesses the same as evidence is worse than no analysis.

10. **Re-running from scratch instead of updating.** The matrix is a living document. On refresh, re-check signals and re-score — don't rebuild the structure each time. The framework persists; the data updates.

11. **Skipping the Attack Vector Grid.** Going straight from matrix placement to playbook selection without distilling vulnerabilities means you are guessing at pressure points instead of using evidence. The grid is the bridge between research and action.

12. **Picking a wedge that needs explaining.** If you cannot state your wedge's value in one sentence without layers of context, it is not a wedge — it is a feature. A good wedge is simple enough for customers to understand immediately but valuable enough that they demand it from every product in the category.

13. **Responding to every attacker publicly.** If a competitor with minimal mindshare attacks you, responding publicly gives them oxygen they do not deserve. Match your defensive posture to the attacker's position on the matrix, not to your emotional reaction.

## Verification checklist

Before returning the final analysis:

- [ ] Market boundaries are defined (category, buyer, job-to-be-done, scope)
- [ ] Competitor set covers direct, adjacent, substitutes, and ecosystem actors
- [ ] Mindshare scores are based on customer evidence or proxy data (not internal anxiety)
- [ ] Resource scores are relative to market dedication (not company size)
- [ ] Your own company is scored first as anchor
- [ ] Every signal has a source and date
- [ ] Verified evidence is separated from assumptions
- [ ] Each priority player has a category, rationale, and trigger
- [ ] Attack Vector Grid is built for each priority player
- [ ] Playbook is selected for each priority player
- [ ] Whitespace and positioning gaps are identified
- [ ] Market shape is interpreted (if enough data exists)
- [ ] Recommended actions have owners, dependencies, and checkpoints

## Completion gate

Do not finalise unless the analysis includes:

- Competitor set classification (direct, adjacent, substitute, ecosystem)
- Matrix category for each priority player
- Rationale with evidence and confidence
- Verified vs assumed separation
- Attack Vector Grid for each priority player
- Selected playbook per priority player
- Next action per priority player
- Measurable checkpoint or trigger
- Market-shape interpretation where enough data exists

## Pairing guidance

- **After this skill:** If the output includes positioning or messaging decisions, run `copy-pass` to sharpen the copy before publishing.
- **For customer-facing competitor responses:** Use `care-review` on any direct messages about competitors.
- **For ongoing monitoring:** Feed the matrix triggers into a monitoring cadence (monthly watchlist, trigger tracking).
- **For content that references competitors:** Run the output through `humaniser` before publishing.

## Public repo packaging rule

This is a general framework. Public examples and docs must stay client-agnostic. Do not include internal workspace paths, private brand names, campaign-specific language, or examples tied to one company unless the repo is intentionally company-specific.

When publishing or updating a framework repo:
- Include a clear README usage description
- Include a Hermes-compatible `SKILL.md`
- Add a source attribution line that names the real source/author, not the packager
- Scan for private paths and client-specific language before pushing
- Verify the remote README and SKILL.md after pushing

## Compatibility aliases

This skill is the canonical class-level framework for competitive intelligence. It replaces and absorbs the following legacy skill names:

- `newsroom-famasi-competitor-intelligence` — old newsroom trigger for Famasi competitor analysis. Now handled natively: any trigger loading this name should load `market-command-matrix` instead and apply it to the current brand, product, campaign, or market.

If a cron job or routing rule references an absorbed skill name, update it to reference `market-command-matrix` directly.

## Source

Based on Patrick Campbell's Competitor Research and Strategy (2023): https://patticus.com/2023/12/16/competitive-research-playbook/

Packaged as a Hermes skill for structured market intelligence, positioning, and go-to-market decisions.
