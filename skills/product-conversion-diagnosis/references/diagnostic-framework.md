# Product Conversion Diagnostic Framework

Use this reference for a complete audit, structured document, workshop, or experiment backlog. Select only the sections relevant to the user's evidence.

## 1. Minimum Product Brief

Collect or infer, while marking unknowns:

| Field | Question |
|---|---|
| Target user | Who has the problem strongly enough to act? |
| Trigger situation | What just happened when the need becomes salient? |
| Current alternative | What does the user do without this product? |
| Category shell | What familiar category does the product resemble? |
| Distinct mechanism | What does it do that alternatives do not? |
| Observable result | What changes for the user? |
| Time to value | How soon can that result be experienced? |
| Repeat reason | Why would the user return or subscribe? |
| Price/plan | What exactly is paid, at what cadence? |
| Proof | What evidence is visible before payment? |

## 2. Value Equation

Evaluate the offer with this qualitative equation:

`Perceived paid value = result importance x personal relevance x proof x expected frequency x trust / time x effort x money x uncertainty`

Do not calculate a fake numeric score. Use the equation to identify which factor is suppressing willingness to pay.

Useful distinctions:

- **Information value:** “I learned something.”
- **Decision value:** “I now know what to do.”
- **Execution value:** “The product helps me do it.”
- **Outcome value:** “My situation measurably improved.”

Products often attract traffic with information value while charging for decision, execution, or outcome value. The conversion path must make that transition visible.

## 3. Promise Alignment Table

| Touchpoint | User sees/hears | User expects | Product mechanism visible? | Personal proof? | Mismatch |
|---|---|---|---|---|---|
| Ad/content hook |  |  |  |  |  |
| CTA/landing |  |  |  |  |  |
| First action |  |  |  |  |  |
| Aha moment |  |  |  |  |  |
| Paywall |  |  |  |  |  |
| Post-purchase |  |  |  |  |  |

Write the three key sentences after filling the table:

1. Users click because they believe ___;
2. The product proves ___ before payment;
3. The paywall sells ___;

If these blanks are materially different, test message and experience alignment before simply buying more traffic.

## 4. Funnel Diagnosis Matrix

| Observed pattern | Likely routes to investigate | Evidence to inspect next |
|---|---|---|
| Weak early retention | audience, first frame, hook clarity, creative fatigue | frame-level retention, hook variants, audience split |
| Good retention, weak CTR | low urgency, weak CTA, content satisfies curiosity without product need | click intent, comments, CTA variants |
| Good CTR, weak landing/activation | expectation mismatch, slow/unclear landing, account friction | arrival rate, load time, first-action completion, session replay |
| Good activation, weak aha | weak output, too much setup, slow response, generic result | time-to-value, completion rate, output quality review |
| Aha reached, weak pay | poor proof, weak repeat reason, trust, paywall framing, packaging, price | paywall exposure, plan selection, interviews, repeat-use intent |
| Pay conversion, weak retention | one-off demand, overpromise, weak ongoing value | cohort retention, cancellation reasons, feature usage |

Never use this matrix as causal proof. It decides what to inspect and test next.

## 5. Content-Hero Trap

A common failure in content, knowledge, utility, and AI products:

1. The material opens with an interesting tip, list, book, template, or answer.
2. The audience becomes interested in the content object.
3. The product is introduced late as a place to get more content.
4. The user's mental substitute remains search, free content, a generic AI assistant, or another content app.
5. The paywall charges for a distinct mechanism that the material never demonstrated.

Diagnostic question:

> If the product logo and CTA disappeared, would the material still feel complete?

If yes, the material may be building content demand rather than product demand.

Rebuild it around:

`specific situation -> user input -> product processing -> personalized result -> application -> reason to continue paying`

## 6. Payment-Barrier Interview Prompts

Avoid “Would you pay?” questions. Ask about observed understanding and alternatives:

- What did you think this product would do before opening it?
- What was the first useful thing it did for you?
- At what moment did you understand why it was different?
- What would you use if this product disappeared?
- What stopped you when the payment page appeared?
- Was the problem solved once, or would it recur?
- What would need to happen before the price felt reasonable?
- Which part felt risky, unclear, or exaggerated?

Compare responses from clickers, activated non-payers, new payers, retained users, and churned users. Do not merge them into one average “user opinion.”

## 7. Experiment Card

### Hypothesis

Because [evidence], we believe [specific cause] is reducing [funnel outcome]. If we change [one variable] for [audience/entry point], then [leading behavior] and [downstream metric] should change in [expected direction].

### Design

- Control:
- Variant:
- Unchanged elements:
- Audience/traffic split:
- Duration or sample sufficiency rule:
- Leading metric:
- Payment/retention metric:
- Guardrail metric:
- Confounders:

### Interpretation

- If leading and downstream metrics improve: support the hypothesis and test durability.
- If leading improves but downstream does not: the new message may attract attention without qualified demand.
- If activation improves but payment does not: proof, repeat value, trust, packaging, or price remains unresolved.
- If payment improves but retention worsens: inspect overpromising or low-quality acquisition.

## 8. Prioritized Output Table

| Rank | Diagnosis/hypothesis | Evidence | Impact | Confidence | Test cost | Next test |
|---|---|---|---:|---:|---:|---|
| 1 |  |  |  |  |  |  |

Keep the backlog small enough to execute. Separate:

- immediate copy or creative tests;
- landing/onboarding tests;
- product proof or output-quality changes;
- paywall/packaging tests;
- price tests;
- retention/repeat-use tests.

## 9. Quality Check

Before finalizing a diagnosis, verify:

- The paid value is written as a user result, not a feature list.
- Acquisition and payment promises are compared explicitly.
- Strong top-funnel metrics are not mistaken for qualified demand.
- Price is not blamed without checking proof and frequency.
- Every major claim is marked as fact, inference, or hypothesis.
- Experiments isolate learnable variables.
- The plan includes downstream payment or retention measures, not CTR alone.
