---
description: Help estimate the true time and cost of a new pooper scooper yard quote.
---

# Yard Quote Estimator

Use this when a prospect asks for a quote on recurring dog waste cleanup.

## Recommended workflow

When this skill is triggered, immediately ask these questions and nothing else:

---

**About your business** (skip these if you've given them to me before in this conversation)

1. Business name?
2. City/market you operate in?
3. Business phone or email to put on the quote?
4. Your hourly rate?
5. Minimum charge per visit, if you have one?

**About this customer**

6. Customer name and address?
7. Number of dogs?
8. Yard size — small, medium, large, or very large?
9. Surface type — grass, gravel, mulch, or mix?
10. Gate access — direct, side gate, or street parking?
11. Any obstacles — steps, hills, multiple potty zones, tall grass?
12. Service frequency — weekly, biweekly, or monthly?
13. First clean or already on a schedule?

---

Once the operator pastes back their answers, calculate the quote silently using the formula below and output the finished document. Do not ask follow-up questions. Do not comment on their pricing. Do not suggest they verify anything. Just produce the quote.

---

## Time estimate formula

Use this to calculate how long a visit should take. This math is for your calculation only — do not show it to the customer.

### Step 1 — Base time per dog
Start here based on service frequency:

| Frequency | Per dog |
|-----------|---------|
| Weekly | 5 min |
| Biweekly | 9 min |
| Monthly / first clean | 15 min |

> Biweekly and monthly visits take longer because waste has accumulated. A first clean on a neglected yard can run 2–3x the monthly estimate.

### Step 2 — Yard size multiplier
Multiply the base time by the yard size:

| Yard size | Multiplier |
|-----------|------------|
| Small (townhouse / patio) | 0.75x |
| Medium (standard suburban) | 1.0x |
| Large (½ acre or more) | 1.5x |
| Very large / rural | 2.0x+ |

### Step 3 — Add time for obstacles
Add minutes for anything that slows the visit:

| Condition | Add |
|-----------|-----|
| Gate requires parking outside and walking in | +3 min |
| Multiple separate potty zones | +3 min per extra zone |
| Tall grass, gravel, mulch, or landscaping | +3 min |
| Steps, hills, or uneven terrain | +2 min |
| First clean with visible buildup | +10–20 min |

### Step 4 — Calculate visit time
> **Total visit time = (base time × yard size multiplier) + obstacle add-ons**

Add 3–5 minutes of travel and reset time (walking to/from vehicle, sanitizing tools) to every visit.

---

## Pricing from time

Once you have the visit time, price using the operator's own hourly rate from their answers — never substitute a different number.

**Formula:**
> **Price per visit = (visit time in hours) × operator's hourly rate**

**Apply the minimum charge:**
If the calculated price per visit is below the operator's stated minimum charge, use the minimum charge instead.

**If the operator didn't give a rate:**
Ask for it before calculating anything — do not guess or default to a placeholder rate.

---

## Example: reference math (not shown to customer)

**Customer A** — 2 dogs, medium yard, direct gate access, weekly service, $60/hr rate
- Base: 2 dogs × 5 min = 10 min
- Size: 10 × 1.0 = 10 min
- Obstacles: none
- Travel/reset: +4 min
- Total: 14 min → **$14/visit** (round up if needed, check against minimum)

**Customer B** — 2 dogs, medium yard, gate requires street parking, biweekly service, $60/hr rate
- Base: 2 dogs × 9 min = 18 min
- Size: 18 × 1.0 = 18 min
- Obstacles: street parking +3 min
- Travel/reset: +4 min
- Total: 25 min → **$25/visit** (round up if needed, check against minimum)

Same dog count, same rate. Very different visits — the formula explains the price difference without anyone having to apologize for it.

---

## Output format

Once all questions are answered, produce a Word document (.docx) the operator can download and send to the customer. Do not summarize or explain — just output the document. Use this exact template every time, word for word, only filling in the bracketed fields:

---

[Business Name]
Dog Waste Removal — Service Quote

Date: [Month DD, YYYY]
Prepared for: [Customer First Name] [Customer Last Name]
Service address: [Full Address]

---

YOUR SERVICE PLAN

Frequency: [Weekly / Biweekly / Monthly] service
Dogs: [#] dog(s)
Yard: [Small / Medium / Large / Very large], [surface type]
First visit: [Date or "To be scheduled"]

---

PRICING

First clean: $[X]
Ongoing [frequency] rate: $[X] per visit
Estimated monthly total: $[X] per month ([#] visits)

Pricing is based on the time required to fully clear your yard at each scheduled visit.

---

WHAT'S INCLUDED

— Complete removal of all dog waste from the service area
— Waste bagged and removed from the property
— Tools sanitized between every yard
— Consistent scheduled visits so your yard stays clean week to week
— Text notification when we're on our way

---

TO ACCEPT THIS QUOTE 

Reply to this message with "Sounds good" and we'll get you on the schedule.

Or sign and return:

Name: ___________________________________

Date: ___________________________________

---

Questions? Contact us at [operator phone] or [operator email].

Thank you for the opportunity — we'd love to take this off your plate.

[Business Name]

---

Rules for filling in this template:
- Never change the section headers or punctuation
- Never add sections or remove sections
- [Business Name] = the business name given in the intake answers
- [operator phone] / [operator email] = the contact info given in the intake answers
- Calculate first clean price using the monthly/first clean rate from the formula (15 min per dog)
- Calculate ongoing price using the correct frequency rate from the formula
- If either calculated price falls below the operator's stated minimum charge, use the minimum charge instead
- Monthly total = price per visit × number of visits per month (weekly = 4, biweekly = 2, monthly = 1)
- Round all prices up to the nearest dollar
- Do not show the time estimate math in the document
- Do not add any commentary, coaching, or notes outside the document