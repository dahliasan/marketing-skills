---
name: message-mine
description: Extract and categorise verbatim customer language from reviews, support tickets, sales call transcripts, social media comments, or forum posts. Produces a ranked phrase library by theme. Use when analysing Google reviews, Trustpilot, Reddit threads, Facebook group posts, or any text corpus from customers talking about their problem or your category.
---

# Message Mining

## Philosophy

Customers write your best copy — unprompted, unfiltered, and searingly specific. A single 1-star review can contain 3 headlines. A Reddit thread is a focus group you didn't have to pay for. Your job is to find the signal in the noise and preserve the exact words.

## Workflow

### 1. Collect sources
Priority order for quality:
1. Your own reviews (Google Business, Healthgrades, RateMDs)
2. Competitor reviews (same category — same customer language)
3. Reddit / Facebook groups (unguarded, high emotion)
4. Q&A sites (questions = objections)
5. Amazon reviews for related books/products
6. Support tickets and chat logs

See [SOURCES.md](SOURCES.md) for source-specific search strategies.

### 2. Tag each phrase
Use the same tagging system as `voc-intake-analysis`:
`PAIN` / `LIMIT` / `FAIL` / `TRIGGER` / `DESIRE` / `OBJECTION`

Add two more for review-specific content:
- `PROOF` — results or outcomes they describe (gold for testimonials)
- `SWITCH` — why they left a competitor or previous solution

### 3. Filter for specificity
Keep: "Shooting pain down my left leg when I sit for more than 20 minutes"
Discard: "Great service" / "Very professional" / "Would recommend"

Rule: if the phrase could apply to any business in any industry, discard it.

### 4. Cluster and rank
- Group identical/near-identical phrases
- Count cluster frequency
- Rank top 10 per tag

### 5. Flag competitor intel
From `SWITCH` and `FAIL` tags:
- Why people left competitors (positioning opportunity)
- What competitors claim that customers don't believe (sophistication signal)

## Output Checklist
- [ ] Ranked phrase library (top 10 per tag category)
- [ ] Competitor gaps identified (from SWITCH tags)
- [ ] 3 draft headline angles from PAIN + DESIRE combos
- [ ] 5 objections for FAQ (from OBJECTION tags)
- [ ] Sophistication level signal (how worn-out are the claims?)
