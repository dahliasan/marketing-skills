# VoC Analysis — Worked Example (Chiropractic)

## Scenario
Anonymised intake forms from a suburban chiropractic clinic, N=47 responses.

---

## Raw Input Sample (anonymised)

```
R001: "Sharp pain in lower back when I bend down. Had it for 3 months. Tried physio twice, helped a bit then came back. Can't play golf anymore. Really worried it's going to need surgery."

R002: "Waking up with stiff neck every morning. Can't look over my shoulder when reversing the car. Took ibuprofen every day for a month, stomach started playing up. Friend referred me here."

R003: "Headaches almost every day for 6 months. At the back of my head. Tried massage, acupuncture, nothing works long term. I just want to feel normal again. I have a holiday in 8 weeks."
```

---

## Extracted Tags

| ID | Tag | Verbatim phrase |
|----|-----|-----------------|
| R001 | PAIN | "Sharp pain in lower back when I bend down" |
| R001 | LIMIT | "Can't play golf anymore" |
| R001 | FAIL | "Physio helped a bit then came back" |
| R001 | OBJECTION | "Really worried it's going to need surgery" |
| R002 | PAIN | "Stiff neck every morning" |
| R002 | LIMIT | "Can't look over my shoulder when reversing" |
| R002 | FAIL | "Ibuprofen every day — stomach started playing up" |
| R002 | TRIGGER | "Friend referred me" |
| R003 | PAIN | "Headaches almost every day" |
| R003 | PAIN | "At the back of my head" |
| R003 | FAIL | "Massage, acupuncture, nothing works long term" |
| R003 | DESIRE | "Just want to feel normal again" |
| R003 | TRIGGER | "Holiday in 8 weeks" |

---

## Draft Headlines (verbatim-derived)

1. **"Still Waking Up With a Stiff Neck? Here's Why It Keeps Coming Back"**
   *Source: R002 PAIN + R001/R003 FAIL pattern*

2. **"Can't Play Golf Because of Your Back? Most of Our Patients Are Back on the Course Within 4 Weeks"**
   *Source: R001 LIMIT + desire outcome*

3. **"You've Tried Physio, Massage, and Ibuprofen. They Helped for a Week. Here's What's Actually Going On"**
   *Source: R001 + R002 + R003 FAIL tags*

4. **"Headaches Every Day for 6 Months — It's Not in Your Head (It's in Your Neck)"**
   *Source: R003 PAIN*

5. **"Worried Your Back Pain Might Need Surgery? 94% of Our Patients Avoid It"**
   *Source: R001 OBJECTION*

---

## Awareness Stage Assessment

Based on N=47:
- Problem Aware: 55% (name their symptom, no solution language)
- Solution Aware: 28% (mention specific treatments tried)
- Product Aware: 12% (mention clinic name or referral)
- Most Aware: 5%

**Implication**: Lead campaigns at Problem Aware stage with education-first content. Not "Book now" — "Understand why it keeps coming back."
