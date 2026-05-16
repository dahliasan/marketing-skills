# Marketing Skills

Agent skills for marketing strategy, copywriting, and conversion optimisation — grounded in Eugene Schwartz, direct response fundamentals, and modern VoC methodology.

Small, composable, model-agnostic. Hack them. Make them yours.

## Quickstart

```bash
npx skills@latest add dahliasan/marketing-skills
```

Pick the skills you want. They work with Claude, GPT-4, and any agent that reads markdown instructions.

## Why These Skills Exist

Most AI-assisted marketing copy fails for the same reason most human copy fails: the writer started writing before understanding the prospect.

Eugene Schwartz spent 80% of his time on research and 20% writing. These skills encode that discipline — forcing research before frameworks, frameworks before writing, and validation before publishing.

### The Core Failure Modes These Skills Fix

**#1 — Writing before researching**: Agents default to generic pain points and fabricated desires. The fix is `voc-intake-analysis` and `message-mine` — extract the prospect's actual language before a single word of copy is written.

**#2 — Messaging the wrong awareness stage**: An ad written for a "Most Aware" prospect will bounce off someone who doesn't know chiropractic exists. The fix is `awareness-map` — classify your audience first.

**#3 — Claiming in a fatigued market**: If your market has seen 50 "fixes back pain" claims, another one will be invisible. The fix is `sophistication-level` — find the mechanism or identity angle that cuts through.

**#4 — Writing to a vague "target audience"**: Personas built from assumptions are useless. The fix is `icp-persona-builder` — build segments from actual intake form data.

**#5 — Skipping the belief sequence**: Prospects don't convert from sceptical to convinced in one leap. The fix is `gradualization` — map every belief step before writing.

## Skill Reference

### Research & Discovery

- **[voc-intake-analysis](./skills/research/voc-intake-analysis/SKILL.md)** — Extract verbatim pain language, JTBD, trigger events, and objections from customer intake forms or surveys.
- **[message-mine](./skills/research/message-mine/SKILL.md)** — Mine customer language from reviews, support tickets, sales calls, and transcripts.
- **[jtbd-interview](./skills/research/jtbd-interview/SKILL.md)** — Structure and analyse Jobs-to-Be-Done customer interviews to uncover functional and emotional outcomes.

### Strategic Frameworks

- **[awareness-map](./skills/strategy/awareness-map/SKILL.md)** — Classify audience segments by Schwartz's 5 Stages of Awareness and determine which stage to target.
- **[sophistication-level](./skills/strategy/sophistication-level/SKILL.md)** — Assess market sophistication (Stages 1–5) and select the right messaging angle.
- **[icp-persona-builder](./skills/strategy/icp-persona-builder/SKILL.md)** — Build ICP definitions and 3–5 buyer personas from research data.

### Copy Execution

- **[gradualization](./skills/copy/gradualization/SKILL.md)** — Map the Schwartz belief sequence from current sceptical state to purchase conviction.
- **[headline-generator](./skills/copy/headline-generator/SKILL.md)** — Generate headline variations using verbatim customer language and proven formulas.
- **[copy-framework](./skills/copy/copy-framework/SKILL.md)** — Select and apply the right copy framework (PAS, AIDA, PASTOR, BAB) for the job.
- **[objection-handler](./skills/copy/objection-handler/SKILL.md)** — Convert VoC objections into FAQ copy, inline responses, and trust-building content.

### Quality & Testing

- **[message-market-fit](./skills/quality/message-market-fit/SKILL.md)** — Audit copy against VoC research to validate resonance before publishing.
- **[ab-test-planner](./skills/quality/ab-test-planner/SKILL.md)** — Design hypothesis-driven A/B tests for copy elements grounded in research.

### Domain-Specific

- **[healthcare-copy](./skills/domain/healthcare-copy/SKILL.md)** — Healthcare-specific copywriting: compliance guardrails, patient language, trust-building.
- **[local-service-copy](./skills/domain/local-service-copy/SKILL.md)** — Local service business copy: geo-trust signals, urgency, review integration.

### Workflow Orchestration

- **[campaign-briefer](./skills/workflow/campaign-briefer/SKILL.md)** — Synthesise research into a structured copy brief before writing begins.
- **[copy-chain](./skills/workflow/copy-chain/SKILL.md)** — Run the full research → strategy → copy → validation chain end-to-end.

## Recommended Chains

**Landing page from scratch:**
```
voc-intake-analysis → awareness-map → sophistication-level → icp-persona-builder → gradualization → headline-generator → copy-framework → message-market-fit
```

**Campaign strategy from reviews:**
```
message-mine → sophistication-level → awareness-map → campaign-briefer
```

**Healthcare / chiropractic:**
```
voc-intake-analysis → jtbd-interview → awareness-map → icp-persona-builder → gradualization → healthcare-copy → local-service-copy → objection-handler → message-market-fit
```

## Philosophy

> "The copywriter's job is not to create desire. It is to channel and direct desire that already exists toward a specific product."
> — Eugene Schwartz, *Breakthrough Advertising*

These skills exist to help you find that desire — in customer language, intake forms, review sites, and interview transcripts — before you write a single word.
