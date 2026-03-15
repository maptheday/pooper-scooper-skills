# Pooper Scooper Agent Skills Library

> Open-source AI agent skills built for the pooper scooper industry.
> Powered by the community. Sponsored by the businesses that use them.

---

## What is this?

This is a community library of **AI agent skills** for pooper scooper / pet waste removal business owners.

Skills are folders of instructions that teach AI agents (Claude Code, Cursor, GitHub Copilot, etc.) how to handle specific tasks in your business — writing customer messages, advertising ideas, onboarding new techs, and more.

**Anyone can use them. Anyone can contribute. Businesses can sponsor them.**

---

## How skills work

Drop a skill into your AI agent's skills folder and it gains domain-specific knowledge about how to handle that task — already tuned for a pooper scooper operation.

```
# Example: Ask your agent to optimize today's route
> "Optimize my Tuesday route using the stops I just loaded"
# The agent loads skills/scheduling/optimize-route/SKILL.md and knows exactly what to do
```

Skills work with any agent that supports the `.claude/skills` or `/mnt/skills` pattern, including Claude Code, Cursor, and Windsurf.

---

## Skill status

| Badge | Meaning |
|-------|---------|
| ✅ Complete | Fully written and tested |
| ⏳ Sponsored | Sponsor claimed it — being written now |
| ○ Open | Needs a sponsor or contributor |

---

## Sponsor a skill

Skills are free to use but cost time to write well. Sponsoring a skill means:

- Your business name + logo appears in that skill's `SPONSOR.md` and in this README
- You get a link to your website or product
- You help every operator in this community get that skill for free
- Optional: your team writes the skill content (great if you have domain expertise)

---

## Current sponsors

*Be the first — [claim a skill today.](#sponsor-a-skill)*

---

## Skills index

### 🗓 Scheduling

| Skill | Status | Sponsor |
|-------|--------|---------|
| [optimize-route](skills/scheduling/optimize-route/) | 🔒 MTD official | Map the Day |
| [recurring-stop-builder](skills/scheduling/recurring-stop-builder/) | ○ Open | — |
| [service-day-adjuster](skills/scheduling/service-day-adjuster/) | ○ Open | — |
| [stop-time-estimator](skills/scheduling/stop-time-estimator/) | ○ Open | — |
| [new-customer-onboarding-scheduler](skills/scheduling/new-customer-onboarding-scheduler/) | ○ Open | — |

### 👤 Customer management

| Skill | Status | Sponsor |
|-------|--------|---------|
| [customer-profile-builder](skills/customer-mgmt/customer-profile-builder/) | 🔒 MTD official | Map the Day |
| [pet-notes-tracker](skills/customer-mgmt/pet-notes-tracker/) | ○ Open | — |
| [cancellation-handler](skills/customer-mgmt/cancellation-handler/) | ○ Open | — |
| [customer-win-back](skills/customer-mgmt/customer-win-back/) | ○ Open | — |
| [complaint-response](skills/customer-mgmt/complaint-response/) | ○ Open | — |
| [seasonal-communication](skills/customer-mgmt/seasonal-communication/) | ○ Open | — |

### 🚛 Field operations

| Skill | Status | Sponsor |
|-------|--------|---------|
| [technician-checkin](skills/field-ops/technician-checkin/) | ○ Open | — |
| [yard-condition-report](skills/field-ops/yard-condition-report/) | ○ Open | — |
| [missed-stop-handler](skills/field-ops/missed-stop-handler/) | ○ Open | — |
| [equipment-checklist](skills/field-ops/equipment-checklist/) | ○ Open | — |
| [photo-documentation](skills/field-ops/photo-documentation/) | ○ Open | — |

### 💵 Billing

| Skill | Status | Sponsor |
|-------|--------|---------|
| [invoice-generator](skills/billing/invoice-generator/) | ○ Open | — |
| [late-payment-followup](skills/billing/late-payment-followup/) | ○ Open | — |
| [pricing-calculator](skills/billing/pricing-calculator/) | ○ Open | — |
| [service-pause-credit](skills/billing/service-pause-credit/) | ○ Open | — |

### 📣 Marketing

| Skill | Status | Sponsor |
|-------|--------|---------|
| [review-request](skills/marketing/review-request/) | ○ Open | — |
| [referral-program](skills/marketing/referral-program/) | ○ Open | — |
| [upsell-scripts](skills/marketing/upsell-scripts/) | ○ Open | — |
| [seasonal-promo-builder](skills/marketing/seasonal-promo-builder/) | ○ Open | — |

### ⚙️ Operations

| Skill | Status | Sponsor |
|-------|--------|---------|
| [tech-hiring-checklist](skills/operations/tech-hiring-checklist/) | ○ Open | — |
| [sop-generator](skills/operations/sop-generator/) | ○ Open | — |
| [insurance-compliance](skills/operations/insurance-compliance/) | ○ Open | — |

---

## Contributing

Want to write or improve a skill? See [CONTRIBUTING.md](CONTRIBUTING.md).

The fastest way to contribute:
1. Pick any skill marked ○ Open
2. Fork the repo
3. Fill in the `SKILL.md` following the template in CONTRIBUTING.md
4. Open a PR — we review within a week

No AI background needed. If you run a scooping business and know how *you* handle a situation, you already have everything needed to write a great skill.

---

## About Map the Day

[Map the Day](https://maptheday.com) is CRM software built specifically for pooper scooper operators — route management, customer billing, technician dispatch, and more.

This skill library is free and open-source, maintained by Map the Day and the broader scooper community.

---

*MIT License — use these skills in any agent, any product, any way you want.*
