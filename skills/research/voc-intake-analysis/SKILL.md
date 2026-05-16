---
name: voc-intake-analysis
description: Extract verbatim pain language, JTBD, functional limitations, failed solutions, and trigger events from customer intake forms or surveys. Outputs a structured VoC report with ranked phrases, awareness stage distribution, and copy-ready assets. Use when analysing patient intake forms, onboarding questionnaires, survey responses, or any structured customer feedback dataset.
---

# VoC Intake Analysis

## Philosophy

The prospect's words are the copy. Your job is extraction, not invention. Every headline, every benefit, every objection response should trace back to a verbatim phrase in this analysis. If you can't cite the source, don't write it.

## Workflow

### 1. Prepare the data
- [ ] Strip all PHI (names, DOB, contact info, MRN, location specifics)
- [ ] Number each response for reference (R001, R002...)
- [ ] Note total response count

### 2. Extract and categorise

Read every response. Tag each phrase with a category:

| Tag | What to capture | Example |
|-----|----------------|----------|
| `PAIN` | Exact physical/emotional descriptors | "Shooting pain down my leg" |
| `LIMIT` | What they can't do (JTBD reverse) | "Can't pick up my kids" |
| `FAIL` | Previous treatments that didn't work | "PT helped for a week then it came back" |
| `TRIGGER` | Why they sought help *now* | "Vacation in 6 weeks" |
| `DESIRE` | The outcome they're buying | "Want to sleep through the night again" |
| `OBJECTION` | Fears, concerns, hesitations | "Worried about it being permanent" |

### 3. Rank by frequency
For each category, count occurrences. Top 10 per category become your copy priorities.

### 4. Map awareness stages
For each response, assign a stage (Unaware / Problem Aware / Solution Aware / Product Aware / Most Aware). Calculate distribution %. See [awareness-map](../../strategy/awareness-map/SKILL.md).

### 5. Generate report
See [REFERENCE.md](REFERENCE.md) for full report structure and [EXAMPLES.md](EXAMPLES.md) for a worked chiropractic example.

## Output Checklist
- [ ] Top 10 pain phrases (verbatim, with frequency)
- [ ] Top 5 functional limitations (JTBD)
- [ ] Failed solutions list (with implied objections)
- [ ] Trigger events ranked
- [ ] Awareness stage distribution (%)
- [ ] 5 draft headlines using only verbatim language
