---
name: jtbd-interview
description: Structure, conduct, or analyse Jobs-to-Be-Done customer interviews to uncover the functional and emotional outcomes customers are hiring a product to achieve. Extracts switching barriers, success criteria, and desired outcomes. Use when preparing customer interview questions, analysing interview transcripts, or when the user wants to understand why customers really buy (not just what they say).
---

# JTBD Interview

## Philosophy

People don't buy products — they hire them to make progress in their life. A patient doesn't buy "chiropractic" — they hire it to get back on the golf course, sleep through the night, or stop feeling like they're 80 years old. Understanding the *job* reveals the real headline, the real CTA, and the real reason to believe.

## Two Modes

**Mode A: Preparing for interviews**
Generate a customised interview script for your specific product/service. Ask user for: product category, customer type, and any known pain points.

**Mode B: Analysing transcripts**
Extract JTBD structure from an existing interview. Tag: functional job, emotional job, social job, trigger event, switching barriers, success criteria, desired outcomes.

## Core Interview Structure

Chronological interview — start at the decision moment, work backwards.

1. **First thought** — "When did you first realise you had this problem?"
2. **Passive looking** — "What did you try to do about it before actively searching for a solution?"
3. **Active looking** — "What made you start actively searching?"
4. **Decision** — "Walk me through how you chose this solution."
5. **First use** — "What did you expect to happen? What actually happened?"
6. **Outcome** — "What does success look like for you?"
7. **Switching** — "What would make you stop using this?"

See [INTERVIEW-SCRIPT.md](INTERVIEW-SCRIPT.md) for the full question bank with probes.

## JTBD Tagging Framework

| Tag | Question to answer | Example |
|-----|--------------------|----------|
| `FUNC` | What task are they trying to complete? | "Reduce lower back pain" |
| `EMOT` | How do they want to feel? | "Stop feeling like an old man" |
| `SOCIAL` | How do they want to be seen? | "Want to keep up with my kids" |
| `TRIGGER` | What caused them to act now? | "Couldn't sleep for the 3rd night running" |
| `BARRIER` | What almost stopped them? | "Worried it would be too expensive" |
| `SUCCESS` | How will they know it worked? | "When I can play 18 holes without stopping" |

## Output Format

For each interview or transcript:

```
Functional job: Help me [verb] [object]
Emotional job: So I feel [emotion]
Social job: So others see me as [identity]
Trigger: [specific event or moment]
Switching barriers: [what almost stopped them]
Success criteria: [how they'll measure success]

Top verbatim quotes:
- TRIGGER: "..."
- EMOT: "..."
- SUCCESS: "..."
```

## Output Checklist
- [ ] Functional, emotional, and social jobs identified
- [ ] Trigger event captured verbatim
- [ ] Switching barriers listed (= objection inventory seeds)
- [ ] Success criteria defined (= benefit headlines)
- [ ] Copy implications noted for each JTBD
