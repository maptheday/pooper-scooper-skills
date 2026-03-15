# Pooper Scooper AI Skills Library

> Free, community-built instructions that make AI smarter for your scooping business.
> Written by operators, for operators.

---

## What is this?

When you use AI tools like Claude, ChatGPT, or any AI assistant to help run your business, the AI starts out knowing nothing about the pooper scooper industry. It doesn't know how to quote a yard, handle a difficult customer, or build a stop route.

**Skills fix that.** A skill is a plain text file you upload to your AI that gives it specific knowledge and instructions for one part of your business. Think of it like handing your AI a one-page training doc before asking it a question.

This library is a collection of those training docs — written and shared for free by scooper business owners like you.

---

## How to use a skill in Claude (no tech skills needed)

Claude has a built-in way to upload your own custom instructions. Here's how:

1. Go to [claude.ai](https://claude.ai) and open **Settings**
2. Look for **"Custom Instructions"** or **"Manage Memory & Skills"**
3. Download the skill file you want from this library (it's just a `.md` text file)
4. Upload it, or copy and paste the contents into your custom instructions

That's it. Now when you ask Claude questions related to that topic, it already knows the context of your industry and how to help you properly.

> **Tip:** You can load multiple skills at once. Most owners keep 3–5 loaded at all times — one for quoting, one for customer communication, one for billing, etc.

---

## How to contribute or sponsor a skill

All skills in this library are free. No cost, no catch.

If you want to give back to the community, you can **sponsor a skill** — which just means your name gets credited on it. You can either write the skill yourself (if you have strong opinions on how something should work) or just put your name on an open one and we'll help you fill it in.

To sponsor or contribute, open an issue on this repo or reach out directly. Your name and a link to your website will be listed next to the skill forever.

---

## Current sponsors

| Sponsor | Skill |
|---------|-------|
| Zachary Glontz | [yard-quote-estimator](#-billing) |

*Want your name here? [Claim an open skill.](#how-to-contribute-or-sponsor-a-skill)*

---

## Skills index

Skills marked ✅ are complete and ready to use. Skills marked ○ are stubs that need a contributor to finish writing them — the structure is there, the knowledge just needs filling in.

---

### 🗓 Scheduling

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [optimize-route](skills/scheduling/optimize-route/) | ○ Open | — | If you're asking AI to help plan your day's stops in the most efficient order, this teaches it how routing works for a scooping business — drive time, stop clusters, and service windows. |
| [recurring-stop-builder](skills/scheduling/recurring-stop-builder/) | ○ Open | — | If you're setting up a new customer on a weekly or biweekly schedule, this helps your AI understand how to structure recurring stops with the right frequency and technician assignment. |
| [service-day-adjuster](skills/scheduling/service-day-adjuster/) | ○ Open | — | If a holiday or bad weather hits and you need to reschedule a bunch of customers, this helps your AI suggest how to shift days and communicate the change without double-booking. |
| [stop-time-estimator](skills/scheduling/stop-time-estimator/) | ○ Open | — | If you're trying to figure out how long your route will take, this helps your AI estimate time per stop based on yard size, number of dogs, and how long since the last service. |
| [new-customer-onboarding-scheduler](skills/scheduling/new-customer-onboarding-scheduler/) | ○ Open | — | If a new customer just signed up and you're figuring out when to slot their first visit, this gives your AI the logic for getting them on the right day without disrupting your existing route. |

---

### 👤 Customer management

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [customer-profile-builder](skills/customer-mgmt/customer-profile-builder/) | ○ Open | — | If you're asking AI to help write up a new customer record, this teaches it what details matter — gate codes, dog names, aggression flags, preferred contact method — so nothing important gets missed. |
| [pet-notes-tracker](skills/customer-mgmt/pet-notes-tracker/) | ○ Open | — | If you want to keep good notes on each customer's pets, this helps your AI know what to ask and how to organize the information so your techs have it before they pull up to the yard. |
| [cancellation-handler](skills/customer-mgmt/cancellation-handler/) | ○ Open | — | If a customer says they want to cancel, this gives your AI the scripts and logic to try to save the relationship — pause instead of cancel, offer a skip, or handle the offboarding gracefully if they're truly done. |
| [customer-win-back](skills/customer-mgmt/customer-win-back/) | ○ Open | — | If you have lapsed customers you want to reach back out to, this helps your AI write the right kind of message — not too pushy, not too salesy — that actually gets responses. |
| [complaint-response](skills/customer-mgmt/complaint-response/) | ○ Open | — | If a customer is upset and you need help responding, this gives your AI the right tone and resolution options for the most common scooper complaints — missed visits, quality issues, billing confusion. |
| [seasonal-communication](skills/customer-mgmt/seasonal-communication/) | ○ Open | — | If you need to send messages at the start of spring or when pausing for winter, this gives your AI the right templates and timing for seasonal customer touchpoints. |

---

### 🚛 Field operations

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [technician-checkin](skills/field-ops/technician-checkin/) | ○ Open | — | If you want your techs to check in at the start and end of their day using AI, this gives the assistant the right prompts to log important info quickly and flag anything unusual. |
| [yard-condition-report](skills/field-ops/yard-condition-report/) | ○ Open | — | If a tech needs to document a problem at a stop — muddy conditions, an aggressive dog, an inaccessible gate — this helps your AI generate a clear note for the customer's file. |
| [missed-stop-handler](skills/field-ops/missed-stop-handler/) | ○ Open | — | If a stop gets skipped for any reason, this gives your AI the steps to log why, draft a message to the customer, and get the stop rescheduled without things falling through the cracks. |
| [equipment-checklist](skills/field-ops/equipment-checklist/) | ○ Open | — | If you want your techs to run a quick supply check before heading out, this helps your AI run through the checklist and flag when bags, sanitizer, or other supplies are running low. |
| [photo-documentation](skills/field-ops/photo-documentation/) | ○ Open | — | If you want to document yard conditions with photos, this gives your AI guidance on when to take them, what to capture, and how to attach notes so they're actually useful later. |

---

### 💵 Billing

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [yard-quote-estimator](skills/billing/yard-quote-estimator/) | ✅ Complete | Zachary Glontz | If you're asking AI to help quote a new customer's yard, this teaches it how to factor in yard size, number of dogs, visit frequency, and how backed up the yard is — so your quote makes sense and protects your margin. |
| [invoice-generator](skills/billing/invoice-generator/) | ○ Open | — | If you want AI to help put together invoices for recurring customers or one-time jobs, this gives it the logic for what to include, how to handle partial months, and how to format it clearly. |
| [late-payment-followup](skills/billing/late-payment-followup/) | ○ Open | — | If a customer is past due and you need to follow up, this gives your AI an escalating sequence of messages — starting friendly, getting firmer — without burning the relationship. |
| [service-pause-credit](skills/billing/service-pause-credit/) | ○ Open | — | If a customer pauses their service mid-cycle and you need to figure out what they owe or what credit to apply, this helps your AI do the proration math and communicate it clearly. |

---

### 📣 Marketing

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [review-request](skills/marketing/review-request/) | ○ Open | — | If you want to ask happy customers for a Google review, this helps your AI write the message — the right timing, the right tone, and a direct link — so you actually get reviews instead of just hoping. |
| [referral-program](skills/marketing/referral-program/) | ○ Open | — | If you run any kind of refer-a-friend program, this teaches your AI how to explain it, track who referred who, and write the right thank-you message when a referral converts. |
| [upsell-scripts](skills/marketing/upsell-scripts/) | ○ Open | — | If you want to offer a customer an extra dog, more frequent service, or a deodorizer add-on, this gives your AI the right language to bring it up naturally without sounding like a sales pitch. |
| [seasonal-promo-builder](skills/marketing/seasonal-promo-builder/) | ○ Open | — | If you want to run a spring special or a new-mover offer, this helps your AI build the campaign — the offer, the message, the timing — without you having to start from scratch every season. |

---

### ⚙️ Operations

| Skill | Status | Sponsor | What it does for you |
|-------|--------|---------|----------------------|
| [tech-hiring-checklist](skills/operations/tech-hiring-checklist/) | ○ Open | — | If you're looking to hire a new technician, this gives your AI a checklist to work through — job post language, interview questions, and a trial day structure that weeds out the wrong fits early. |
| [sop-generator](skills/operations/sop-generator/) | ○ Open | — | If you have a process that lives in your head and want to write it down, this helps your AI turn your rough notes into a clean standard operating procedure your team can actually follow. |
| [insurance-compliance](skills/operations/insurance-compliance/) | ○ Open | — | If you want to make sure your coverage is in order, this helps your AI run through a checklist of what a scooping business typically needs — liability, vehicle, workers comp — and flag what might be missing. |

---

## Contributing

If you want to write a skill, you don't need a tech background. You just need to know your business. Pick any skill marked ○ Open, look at the existing `SKILL.md` stub inside the folder, and fill in the guidance section based on how you personally handle that situation.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the exact format.

---

## About

This library is maintained by the scooper community and supported by [Map the Day](https://maptheday.com), CRM software built for pooper scooper operators.

*MIT License — free to use, share, and build on.*
