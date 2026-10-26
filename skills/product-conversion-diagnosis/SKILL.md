---
name: product-conversion-diagnosis
description: Diagnose app, software, subscription, content, or AI products whose traffic, engagement, activation, or payment conversion is weak or contradictory. Use when Codex must connect product positioning, acquisition promise, ad creative, landing page, first-use experience, paywall, pricing, retention, and experiments instead of analyzing one funnel stage in isolation.
---

# Product Conversion Diagnosis

## Purpose

Find the most likely break in the product-to-payment chain and turn it into testable product, creative, experience, or monetization actions.

Do not begin with feature ideas or assume price is the problem. First determine what users believe they are clicking for, what result the product actually creates, what they experience before payment, and what the paywall asks them to buy.

## Core Mental Model

Treat conversion as an alignment problem across five layers:

1. **User problem** — the concrete situation, urgency, frequency, and desired change.
2. **Product mechanism** — how the product produces a result differently from alternatives.
3. **Acquisition promise** — what the ad, content, recommendation, or hook makes users expect.
4. **Experienced proof** — what users personally see, receive, or accomplish before payment.
5. **Paid promise** — what outcome, continued access, or repeated capability the price unlocks.

The central diagnostic question is:

> Did the user click for the same value that the product later asks them to pay for?

If not, strong attention or CTR can coexist with weak subscription conversion.

## Evidence Discipline

- Separate facts, observed behavior, user statements, and hypotheses.
- Never invent benchmarks, audience data, market numbers, feedback, or funnel metrics.
- Use metric combinations to locate possible breaks, not to claim causality by themselves.
- Label missing-data analysis as a hypothesis and state what evidence would confirm or reject it.
- Preserve the user's actual product wording until its meaning has been understood; do not replace it with generic positioning language too early.

## Diagnostic Workflow

### 1. Reconstruct the Product Truth

Write a one-sentence value chain:

`For [specific user in a specific situation], the product uses [distinct mechanism] to create [observable result] within [time/effort], unlike [current alternative].`

Then distinguish:

- **Category shell:** what the product superficially resembles.
- **Content or feature bait:** the element most likely to attract attention.
- **Paid value:** the repeatable result or capability worth paying for.
- **Proof moment:** the earliest point where the user can feel that value personally.

Do not confuse useful content with the product's unique value. A piece of content can be the acquisition vehicle while the application of that content to the user's situation is the actual product.

### 2. Map the Full Conversion Chain

Use the relevant stages rather than inspecting one number alone:

`impression -> early retention -> click -> arrival -> first action -> value/aha moment -> paywall -> purchase -> repeated use`

For each stage record:

- user expectation;
- product promise or interface shown;
- observable behavior/metric;
- likely uncertainty or friction;
- evidence still missing.

Common directional readings:

- Weak early retention suggests a hook, audience, or first-frame problem.
- Strong early retention but weak click suggests interest without a compelling next action.
- Strong click but weak activation suggests expectation mismatch, landing friction, or unclear first action.
- Strong click/activation but weak payment suggests weak experienced proof, paid-promise mismatch, trust, frequency, urgency, paywall, or price-value framing.
- Initial payment but weak retention suggests overpromising, insufficient repeated value, or a one-off use case sold as a subscription.

These are hypothesis routes, not automatic conclusions.

### 3. Compare Acquisition Promise With Paid Promise

Extract each promise in plain language:

- “The user clicks because they expect ___.”
- “The first-use experience proves ___.”
- “The paywall asks them to pay for ___.”

Classify the alignment:

- same promise, clearly proven;
- same promise, weakly proven;
- adjacent promise;
- different promise;
- attractive content with no product mechanism visible.

When acquisition is content-led, check whether the content becomes the hero while the product becomes a late, replaceable mention. Prefer showing the transformation sequence:

`user input/problem -> product mechanism -> personalized output -> recommended action/result`

### 4. Diagnose the Payment Barrier

Separate these causes instead of calling everything “price sensitivity”:

- **Comprehension:** users do not understand what the product does.
- **Relevance:** they understand it but do not see it as their problem.
- **Differentiation:** free or familiar alternatives seem equivalent.
- **Proof:** the product claims value without demonstrating it personally.
- **Trust:** users doubt quality, accuracy, safety, or delivery.
- **Urgency:** the problem can wait.
- **Frequency:** the need feels one-off, making subscription framing weak.
- **Experience:** setup, onboarding, latency, or output quality blocks the aha moment.
- **Paywall:** timing, packaging, copy, plan structure, or hidden terms create friction.
- **Price:** value is understood and proven, but willingness to pay is still lower than the offer.

Only recommend a price change after checking value comprehension, proof, frequency, and packaging.

### 5. Turn Diagnosis Into Experiments

For every proposed test include:

- causal hypothesis;
- exact variable being changed;
- control and variant;
- audience and entry point;
- leading metric;
- payment/retention metric;
- expected pattern if the hypothesis is correct;
- decision rule and major confounders.

Prefer tests that isolate one question. Do not change the hook, audience, onboarding, paywall, and price in one variant and then claim to know which caused the result.

Prioritize tests by:

`expected learning value x business impact x confidence / implementation cost`

## Creative and Messaging Lens

When acquisition material is part of the task, translate product truth into visible proof:

- problem scene: what happened to the user;
- input: what the user tells or gives the product;
- mechanism: what the product uniquely does;
- output: what specific result appears;
- application: how that result changes the user's next decision or action;
- paid continuation: why repeated access is valuable.

Favor demonstrations of the product's mechanism over generic category education, lists, tips, or content summaries. Keep proven content shells when they attract qualified demand, but test whether the product appears early enough to shape the click expectation.

## Output Standard

Lead with a diagnosis, not a recap. A useful answer normally contains:

1. Primary judgment and confidence level.
2. Evidence and contradictions.
3. Product value chain and category-vs-paid-value distinction.
4. Acquisition-promise vs paid-promise comparison.
5. Funnel-stage hypotheses ranked by likelihood and impact.
6. Product, creative, landing/onboarding, paywall, and pricing actions as relevant.
7. A small prioritized experiment plan.
8. Missing evidence that would materially change the conclusion.

Use the detailed worksheets in [references/diagnostic-framework.md](references/diagnostic-framework.md) when the user requests a complete audit, document, workshop, or experimentation backlog. For a short question, apply the same reasoning without forcing the full template.

## Boundaries

- Do not turn every diagnosis into a feature roadmap.
- Do not optimize CTR alone when downstream conversion is the stated goal.
- Do not treat competitor features as proof of user demand; use competitors to understand alternatives and expectations.
- Do not declare product-market fit or its absence from one funnel metric.
- Do not hide uncertainty behind polished language. State the strongest current explanation and the fastest way to test it.
