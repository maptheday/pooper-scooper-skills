# Pooper Scooper AI Skills Library

> Free instructions that make AI smarter for your scooping business.
> Written by operators, for operators.

---

## How to use the marketplace plugin

This repo is packaged as a Claude marketplace plugin. The full skill library is available in one install, and the packaged skills live under `plugins/pooper-scooper-skills/skills`.

1. Open Claude.
2. Go to Settings.
3. Open Plugins.
4. Click Add plugin.
5. Choose Add marketplace.
6. Paste this GitHub URL:
   `https://github.com/maptheday/pooper-scooper-skills`
7. Wait for the marketplace to load, then use the plugin or slash commands like `/yard-quote-estimator`.

If you prefer the CLI, use:

```bash
/plugin marketplace add maptheday/pooper-scooper-skills
```

---

## What is this?

When you use an AI tool like Claude to help run your business, it starts out knowing nothing about the pooper scooper industry. It doesn't know how to quote a yard, respond to a one-star review, or tell a new hire what to expect on their first day.

**Skills fix that.** A skill is a plain text file your AI uses to learn one part of your business. Think of it like handing your AI a one-page training doc before asking it a question. Once it has the skill loaded, it gives you answers that actually make sense for your industry instead of generic advice.

This library is a collection of those training docs — written and shared for free by scooper business owners.

---

## What’s in the plugin

The packaged skills live under `plugins/pooper-scooper-skills/skills` and include:

- Customer communication: `cancellation-handler`, `complaint-response`, `firing-a-customer`, `objection-handling`, `price-increase-notice`, `seasonal-communication`, `win-back-message`, `yard-quote-estimator`
- Team operations: `first-day-script`, `performance-conversation`, `pooper-scooper-job-post`
- Growth: `negative-review-response`, `neighborhood-outreach`, `referral-ask`, `review-request`, `upsell-message`
- Pricing: `late-payment-followup`, `pricing-confidence`, `service-agreement-language`

---

## How to sponsor a skill

All skills are free. Sponsoring a skill means your name gets credited on it, and the skill can be shaped around your preferred phrasing, pricing approach, and local business style.

If you want to sponsor, improve, or customize a skill, email **info@maptheday.com**.

---

## Current sponsors

| Sponsor | Skill |
|---------|-------|
| Zachary Glontz | yard-quote-estimator |

*Want your name here? Email info@maptheday.com to claim an open skill.*

---

## Skills index

✅ Complete — click View/Copy to open the skill file. &nbsp; ○ Not yet written — [email us](mailto:info@maptheday.com) to contribute.

---

### 💬 Talking to customers

| Skill | Status | Sponsor | What it does for you | &nbsp; |
|-------|--------|---------|----------------------|--------|
| yard-quote-estimator | ✅ | Zachary Glontz | If you're using AI to help price a new customer's yard, this teaches it what actually drives the cost — yard size, dog count, access, and frequency — so the number you land on makes sense and holds up. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/yard-quote-estimator/SKILL.md) |
| complaint-response | ○ | — | If a customer reaches out upset — missed visit, quality issue, billing confusion — this helps your AI draft a response that takes responsibility, sounds human, and keeps the relationship intact. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/complaint-response/SKILL.md) |
| cancellation-handler | ○ | — | If a customer says they want to cancel, this helps your AI coach you through the conversation — what to offer, what to ask, when to try to save it, and how to let go gracefully if it's time. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/cancellation-handler/SKILL.md) |
| firing-a-customer | ○ | — | If you have a customer who isn't worth keeping — chronic non-payer, unsafe dog, impossible to deal with — this helps your AI write the message that ends the relationship professionally without drama. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/firing-a-customer/SKILL.md) |
| price-increase-notice | ○ | — | If you need to raise your rates, this helps your AI write the customer message — how much notice to give, how to explain it without over-explaining, and how to frame it so most customers accept it and stay. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/price-increase-notice/SKILL.md) |
| objection-handling | ○ | — | If a prospect says "that seems expensive" or "I need to think about it," this gives your AI the language to respond confidently without being pushy — covering the most common objections a scooper owner hears. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/objection-handling/SKILL.md) |
| win-back-message | ○ | — | If you want to reach out to a customer who stopped service months ago, this helps your AI write a message that feels warm and personal rather than like a form email — and actually gets replies. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/win-back-message/SKILL.md) |
| seasonal-communication | ○ | — | If you need to message customers at the start of spring or heading into winter — resuming service, going on pause, or running a promotion — this gives your AI the right tone and timing for each situation. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/seasonal-communication/SKILL.md) |

---

### 👥 Running your team

| Skill | Status | Sponsor | What it does for you | &nbsp; |
|-------|--------|---------|----------------------|--------|
| pooper-scooper-job-post | ○ | — | If you need to write a job listing, this helps your AI write something that attracts reliable, dog-friendly people and filters out the ones who'll ghost you after the first yard. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/pooper-scooper-job-post/SKILL.md) |
| first-day-script | ○ | — | If you're sending a new hire out for the first time, this helps your AI build a simple rundown of everything they need to know before they go solo — what to do, what to look out for, and how to handle the situations that always come up. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/first-day-script/SKILL.md) |
| performance-conversation | ○ | — | If a tech is taking too long on yards and it's throwing off your whole route, this helps your AI prepare you for that conversation — how to bring it up, what to say, and how to set a clear expectation without making it weird. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/performance-conversation/SKILL.md) |

---

### 📣 Growing the business

| Skill | Status | Sponsor | What it does for you | &nbsp; |
|-------|--------|---------|----------------------|--------|
| review-request | ○ | — | If you want to ask a happy customer for a Google review, this helps your AI write the message — the right timing after a visit, the right tone, a direct link — so you actually get reviews instead of just meaning to ask. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/review-request/SKILL.md) |
| negative-review-response | ○ | — | If someone leaves you a bad review on Google, this helps your AI draft a public response that looks professional, addresses the issue without getting defensive, and shows future customers you handle problems well. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/negative-review-response/SKILL.md) |
| referral-ask | ○ | — | If you want to ask a loyal customer to refer their neighbors, this helps your AI write the ask in a way that feels natural — not transactional — and tells them exactly what to say when they do refer someone. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/referral-ask/SKILL.md) |
| upsell-message | ○ | — | If you want to offer a customer an upgrade — adding a dog, going from biweekly to weekly, adding deodorizer — this helps your AI write the message so it feels like a helpful suggestion, not a sales pitch. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/upsell-message/SKILL.md) |
| neighborhood-outreach | ○ | — | If you want to reach out to neighbors in an area where you already have customers, this helps your AI write a door-hanger message or a Nextdoor post that's specific enough to feel local and personal. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/neighborhood-outreach/SKILL.md) |

---

### 💵 Pricing & money

| Skill | Status | Sponsor | What it does for you | &nbsp; |
|-------|--------|---------|----------------------|--------|
| yard-quote-estimator | ✅ | Zachary Glontz | If you're using AI to help price a new customer's yard, this teaches it the variables that drive the actual time and cost — so your quotes are consistent, fair, and protect your margins. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/yard-quote-estimator/SKILL.md) |
| late-payment-followup | ○ | — | If a customer hasn't paid and you need to follow up, this gives your AI an escalating sequence of messages — friendly first, firmer later — with language that gets responses without damaging the relationship. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/late-payment-followup/SKILL.md) |
| pricing-confidence | ○ | — | If you're second-guessing your rates or losing quotes and wondering if you're priced wrong, this helps your AI walk you through how to evaluate your pricing against your costs and your market — not just your gut. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/pricing-confidence/SKILL.md) |
| service-agreement-language | ○ | — | If you want to put together a simple service agreement for new customers, this helps your AI draft the key clauses that matter most — cancellation, access, dogs, liability — in plain English. | [View/Copy](https://github.com/maptheday/pooper-scooper-skills/blob/main/plugins/pooper-scooper-skills/skills/service-agreement-language/SKILL.md) |

---

## Contributing

Want to write a skill? You don't need a tech background — just knowledge of your own business. Pick any skill marked ○, email **info@maptheday.com**, and we'll send you the template to fill in. Your name gets credited on it.

---

## About

This library is maintained by the scooper community and supported by [Map the Day](https://maptheday.com), CRM software built for pooper scooper operators.

*MIT License — free to use, share, and build on.*