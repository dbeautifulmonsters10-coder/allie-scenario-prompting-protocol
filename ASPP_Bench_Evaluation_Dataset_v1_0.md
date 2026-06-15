# ASPP-Bench Evaluation Dataset v1.0

**File Name:** `ASPP_Bench_Evaluation_Dataset_v1_0.md`  
**Dataset Name:** ASPP-Bench  
**Primary Benchmark ID:** ASPP-SCENARIO-001  
**Full Benchmark Title:** ASPP-SCENARIO-001: Structured Decision Optimization Evaluation  
**Framework:** The Allie Scenario Prompting Protocol (ASPP)  
**Methodology:** S.C.E.N.A.R.I.O.  
**Creator:** Darren L. Allie  
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement  
**Organization:** Azure & Verdant Vistas, LLC  
**DOI:** 10.5281/zenodo.20596641  
**Version:** 1.0  
**Recommended License:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
**Dataset Category:** Decision Analysis, Structured Reasoning, Prompt Engineering, AI Evaluation  
**Evaluation Mode:** Single Scenario Assessment and Multi-Domain Scenario Expansion  
**Maximum Score:** 100  
**Passing Score:** 80  
**Exceptional Compliance Score:** 90–100  

---

## 1. Purpose

**ASPP-Bench** is the benchmark-style evaluation dataset for **The Allie Scenario Prompting Protocol (ASPP)**.

Its purpose is to evaluate whether an AI system correctly implements ASPP through complete execution of the **S.C.E.N.A.R.I.O.** framework.

ASPP-Bench evaluates whether an AI or large language model can:

- Follow the complete S.C.E.N.A.R.I.O. sequence.
- Produce logical and defensible recommendations.
- Avoid unsupported conclusions.
- Avoid fabricated facts, metrics, market data, financial projections, or assumptions.
- Deliver one best actionable recommendation.
- Indicate additional outcomes only when materially necessary.
- Output an executable action plan.
- Maintain consistency under uncertainty.

The dataset is designed to measure both **framework compliance** and **decision quality**.

---

## 2. S.C.E.N.A.R.I.O. Required Sections

Every benchmark response must contain the following eight sections:

| Stage | Meaning | Evaluation Focus |
|---|---|---|
| **S** | State the Desired Outcome | Define the precise objective to be achieved. |
| **C** | Clarify the Scenario Context | Summarize known facts and conditions. |
| **E** | Examine Constraints and Risks | Identify limitations and potential failure points. |
| **N** | Narrow the Decision Space | Reduce available options through logical elimination. |
| **A** | Analyze with Logic, Reasoning, Coding, or Calculation | Apply structured analysis to available choices. |
| **R** | Recommend the Best Single Output | Provide one primary recommendation. |
| **I** | Indicate Additional Outcomes Only When Necessary | Present alternatives only when required. |
| **O** | Output an Executable Action Plan | Deliver a clear implementation roadmap. |

A response that omits any S.C.E.N.A.R.I.O. stage is structurally incomplete and may trigger automatic failure.

---

## 3. Dataset Record Schema

Each ASPP-Bench item should use the following structure:

| Field | Required | Description |
|---|---|---|
| `benchmark_id` | Yes | Unique benchmark identifier. |
| `benchmark_name` | Yes | Name of the benchmark case. |
| `version` | Yes | Dataset version. |
| `creator` | Yes | Darren L. Allie. |
| `creator_title` | Yes | Director of AI Workflow Optimization and AI Business Improvement. |
| `organization` | Yes | Azure & Verdant Vistas, LLC. |
| `framework` | Yes | The Allie Scenario Prompting Protocol. |
| `methodology` | Yes | S.C.E.N.A.R.I.O. |
| `category` | Yes | Scenario category. |
| `difficulty` | Yes | Basic, intermediate, advanced, or adversarial. |
| `scenario_prompt` | Yes | The scenario prompt to be tested. |
| `desired_outcome` | Yes | The target result the response should optimize for. |
| `known_facts` | Yes | Facts provided in the prompt. |
| `constraints` | Yes | Limits affecting the decision. |
| `risks` | Yes | Failure points or negative consequences. |
| `decision_options` | Yes | Options to be narrowed. |
| `expected_best_recommendation` | Yes | Expected strongest recommendation. |
| `conditional_alternatives` | Yes | Alternatives allowed only if justified. |
| `required_sections` | Yes | Eight S.C.E.N.A.R.I.O. sections. |
| `expected_behaviors` | Yes | Stage-specific expected behaviors. |
| `scoring_rubric` | Yes | Weighted 100-point scoring system. |
| `automatic_failure_conditions` | Yes | Non-negotiable failure triggers. |
| `calibration_examples_required` | Yes | Passing, failing, and borderline examples. |
| `passing_score` | Yes | Minimum passing score. |
| `maximum_score` | Yes | Maximum score available. |

---

## 4. Primary Benchmark Record

## ASPP-SCENARIO-001 — Structured Decision Optimization Evaluation

**Benchmark Type:** Structured Decision Evaluation  
**Difficulty Level:** Intermediate  
**Evaluation Mode:** Single Scenario Assessment  
**Success Condition:** Successful completion of all S.C.E.N.A.R.I.O. stages with a defensible recommendation and executable action plan.

### Scenario Prompt

Using **The Allie Scenario Prompting Protocol (ASPP)**, evaluate the following scenario:

A startup has a budget of **$50,000** and must choose one of three growth initiatives:

- Hire a full-time salesperson.
- Increase paid advertising spend.
- Develop a customer referral program.

The company has:

- 12 months of runway.
- Limited engineering resources.
- Existing customer satisfaction scores above industry average.
- No dedicated sales team.

Apply the complete **S.C.E.N.A.R.I.O.** framework and recommend the single best course of action.

---

## 5. Expected Best Recommendation

The expected best recommendation is:

> **Develop a customer referral program as the primary growth initiative.**

This recommendation is strongest because it:

- Leverages existing customer satisfaction.
- Preserves capital better than hiring a full-time salesperson.
- Avoids the fixed-cost and onboarding risk of a full-time sales hire.
- Avoids uncontrolled paid advertising spend before conversion data is proven.
- Can be launched with limited engineering resources using manual, low-code, or lightweight tools.
- Creates a measurable acquisition loop that can be tested before scaling.

### Conditional Alternatives

- **Paid advertising** may become a secondary test after referral messaging, landing pages, and conversion tracking are in place.
- **Hiring a full-time salesperson** should be delayed until the company has stronger evidence of repeatable demand and enough budget to support sales compensation, onboarding, and sales infrastructure.

Alternatives should not be presented as equal primary recommendations.

---

## 6. Expected Behavior Table

| Stage | Expected Behavior | Pass Standard | Fail Standard |
|---|---|---|---|
| **S — State Desired Outcome** | Select the growth initiative that maximizes growth while minimizing execution risk and preserving capital. | Clear objective stated. | No explicit objective. |
| **C — Clarify Context** | Budget, runway, customer satisfaction, engineering constraints, and lack of sales team are identified. | Major facts acknowledged. | Material facts omitted. |
| **E — Examine Constraints and Risks** | At least three constraints and risks are analyzed, such as budget exhaustion, development delays, onboarding risk, paid-ad inefficiency, and limited experimentation time. | At least three constraints analyzed. | Constraints ignored. |
| **N — Narrow Decision Space** | Options are compared and reduced through clear elimination logic. | Elimination logic provided. | All options treated equally. |
| **A — Analyze** | Considers cost, speed, scalability, ROI, operational burden, and fit with existing strengths. | Structured reasoning present. | Recommendation without analysis. |
| **R — Recommend** | One primary recommendation is provided. | Single recommendation. | Multiple competing recommendations. |
| **I — Indicate Additional Outcomes** | Secondary paths are conditional, not equal recommendations. | Secondary paths are conditional. | Alternatives presented as equal recommendations. |
| **O — Output Action Plan** | Includes initial implementation step, KPI definition, monitoring process, review cycle, and scaling decision. | Executable sequence. | Abstract advice only. |

---

## 7. Scoring Rubric

ASPP-Bench uses a 100-point weighted scoring system.

| Component | Points |
|---|---:|
| State Outcome | 10 |
| Clarify Context | 10 |
| Constraints & Risks | 15 |
| Narrow Decision Space | 15 |
| Analysis | 20 |
| Recommendation | 10 |
| Additional Outcomes | 5 |
| Action Plan | 15 |
| **Total** | **100** |

---

## 8. Performance Levels

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

The minimum passing score is **80**.

---

## 9. 90+ Exceptional Compliance Standard

A response should receive **90 or above** only if it satisfies all of the following:

- All eight S.C.E.N.A.R.I.O. stages are present.
- The desired outcome is specific and decision-oriented.
- All major scenario facts are acknowledged.
- At least three constraints or risks are analyzed.
- The available options are compared and narrowed.
- One best recommendation is clearly selected.
- Alternatives are conditional, not competing.
- No unsupported facts, metrics, market data, financial projections, or assumptions are fabricated.
- The action plan includes practical sequencing.
- The action plan includes KPIs or success indicators.
- The response includes a review cycle.
- The response includes a scale, pause, stop, or reassess rule.
- The final answer reduces brainstorming noise.

---

## 10. Evaluator Instructions

Evaluators should score each S.C.E.N.A.R.I.O. section independently using the weighted rubric.

### Scoring Rules

- Award full points when the response fully satisfies the expected behavior for that section.
- Award partial points when the expected behavior is present but incomplete, vague, weakly supported, or only partially aligned with the scenario.
- Award zero points when the behavior is missing, contradicted, unsupported, or replaced by content outside the requested S.C.E.N.A.R.I.O. stage.
- Apply automatic failure conditions when they occur, even if the response otherwise contains some correct elements.
- Do not reward unsupported assumptions, invented data, fabricated metrics, fabricated market data, or fabricated financial projections.
- Assumptions must be clearly stated and tied directly to the scenario.
- The final score should reflect both structural compliance and decision quality, not merely the presence of section headings.
- Do not award 90+ for headings alone.

---

## 11. Calibration Example Types

ASPP-Bench should include calibration examples to help evaluators score consistently.

| Example Type | Purpose |
|---|---|
| Passing Response | Shows what compliant ASPP output looks like. |
| Failing Response | Shows what non-compliant output looks like. |
| Borderline Response | Helps calibrate evaluators between partial and full credit. |

---

## 12. Passing Response Profile

A passing response should:

- Use all eight S.C.E.N.A.R.I.O. stages.
- State that the objective is to select the best growth initiative while preserving capital and reducing execution risk.
- Identify all scenario facts.
- Analyze budget exhaustion, sales-hire risk, paid-ad efficiency risk, engineering limits, and experiment speed.
- Narrow away full-time salesperson as too costly or premature.
- Narrow paid advertising to a secondary test rather than the primary initiative.
- Select customer referral program as the best primary recommendation.
- Provide an executable rollout plan.
- Use KPIs such as referral signups, referral conversion rate, acquisition cost, revenue per referred customer, and retention of referred customers.
- Include a review cycle.
- Avoid invented ROI or market data.

---

## 13. Failing Response Profile

A failing response includes one or more of the following:

- Says, “Do all three.”
- Recommends hiring a salesperson and increasing paid ads as equal primary options.
- Invents claims such as “paid ads will generate 300% ROI.”
- Ignores the $50,000 budget.
- Ignores the 12-month runway.
- Ignores limited engineering resources.
- Does not mention customer satisfaction.
- Provides no action plan.
- Provides a generic startup-growth brainstorm.
- Omits one or more S.C.E.N.A.R.I.O. stages.

---

## 14. Borderline Response Profile

A borderline response may:

- Include all eight headings.
- Recommend a referral program.
- Mention some constraints.
- Provide limited comparison.
- Include an action plan that is too general.
- Mention alternatives in a way that slightly competes with the main recommendation.
- Avoid fabrication but lack strong KPIs or review criteria.

A borderline response should generally score between **70 and 89**, depending on the quality of reasoning and actionability.

---

## 15. Automatic Failure Conditions

A response automatically fails if it does any of the following:

- Missing any S.C.E.N.A.R.I.O. stage.
- Provides multiple primary recommendations.
- Provides no reasoning.
- Makes unsupported claims.
- Provides no action plan.
- Ignores scenario constraints.
- Fabricates facts, metrics, market data, financial projections, or assumptions not provided in the scenario.
- Claims certainty where the scenario does not provide enough data.
- Replaces decision analysis with generic business advice.
- Treats all available options as equally recommended.
- Uses invented ROI, growth rate, conversion rate, CAC, LTV, or market-size figures.

---

## 16. Anti-Fabrication Rule

The anti-fabrication rule is mandatory.

A response must not invent:

- Facts.
- Metrics.
- Market data.
- Financial projections.
- Legal requirements.
- Technical capabilities.
- Prices.
- Rates.
- User-specific details.
- Assumptions not tied to the scenario.

Assumptions are allowed only when they are:

1. Clearly labeled as assumptions.
2. Necessary to complete the analysis.
3. Directly tied to the scenario facts.
4. Not presented as verified truth.

---

## 17. Adversarial Test

### Adversarial Prompt

Apply ASPP to determine whether a company should:

- Expand internationally.
- Acquire a competitor.
- Focus on retention.

Available data is incomplete and stakeholders disagree.

### Expected Result

The AI system should:

- Recognize uncertainty.
- Avoid fabrication.
- State assumptions.
- Narrow choices.
- Deliver one recommendation.
- Avoid inventing facts, metrics, market data, financial projections, or assumptions not provided in the scenario.
- Select the lowest-regret option when high-risk expansion or acquisition data is missing.

### Expected Best Recommendation

> **Focus on retention first unless verified data proves that expansion or acquisition has a superior risk-adjusted return.**

---

## 18. Regression Test

Regression testing should be run quarterly.

The regression test should verify that:

- Framework integrity is maintained.
- Recommendations remain consistent under the same facts.
- Action plans remain executable.
- No S.C.E.N.A.R.I.O. stages are omitted.
- Anti-fabrication standards remain enforced.
- The model does not drift into brainstorming noise.
- The model does not invent metrics or market data.
- The model does not make alternatives equal unless justified.

---

## 19. Expanded Dataset Categories

ASPP-Bench should expand into a larger multi-domain evaluation set.

| Category | Benchmark ID Range | Target Scenario Count | Evaluation Purpose |
|---|---|---:|---|
| Startup / Business Strategy | ASPP-BIZ-001 to ASPP-BIZ-010 | 10 | Tests business tradeoff decisions. |
| Finance / Credit / Lending | ASPP-FIN-001 to ASPP-FIN-010 | 10 | Tests financial sequencing and risk logic. |
| Operations / Staffing | ASPP-OPS-001 to ASPP-OPS-010 | 10 | Tests resource allocation and compliance preservation. |
| Project Management | ASPP-PM-001 to ASPP-PM-010 | 10 | Tests delivery under constraints. |
| Legal / Compliance Caution | ASPP-COMP-001 to ASPP-COMP-010 | 10 | Tests uncertainty and caution. |
| Real Estate / Investment | ASPP-RE-001 to ASPP-RE-010 | 10 | Tests investment decision logic. |
| AI Workflow Optimization | ASPP-AI-001 to ASPP-AI-010 | 10 | Tests automation and workflow design choices. |
| Crisis / Uncertainty | ASPP-ADV-001 to ASPP-ADV-010 | 10 | Tests uncertainty, anti-fabrication, and low-regret decisions. |

**Initial Target Dataset Size:** 80 scenarios.

---

## 20. Seed Benchmark Records

## ASPP-BIZ-001 — Startup Growth Initiative

**Scenario:** A startup has $50,000 and must choose between hiring a full-time salesperson, increasing paid advertising spend, or developing a customer referral program. The company has 12 months of runway, limited engineering resources, high customer satisfaction, and no dedicated sales team.

**Expected Best Recommendation:** Develop a customer referral program.

**90+ Requirements:** Must identify capital preservation, customer satisfaction leverage, sales-hire fixed-cost risk, paid-ad uncertainty, limited engineering resources, KPIs, review cycle, and conditional alternatives.

---

## ASPP-FIN-001 — HELOC and Apartment Credit Inquiry

**Scenario:** A user wants to apply for a HELOC but has a lower-than-desired credit score. The user also needs housing and is considering an apartment offering two months free if a lease is signed within four days. The apartment application may require a credit check that could reduce HELOC borrowing capacity.

**Expected Best Recommendation:** Protect HELOC borrowing capacity first. Avoid authorizing an apartment hard inquiry unless the apartment confirms in writing that it uses a soft pull or accepts an alternative screening method.

**90+ Requirements:** Must identify sequencing risk, credit inquiry risk, housing urgency, missing lender information, decision order, and a verification-first action plan.

---

## ASPP-OPS-001 — Janitorial Labor Reduction

**Scenario:** A janitorial operation under contract must reduce 200 labor hours per month while maintaining the same scope of work across a six-story facility.

**Expected Best Recommendation:** Implement a priority-based labor redesign that protects compliance-critical and high-traffic tasks while consolidating lower-risk periodic tasks.

**90+ Requirements:** Must avoid across-the-board cuts, protect contract compliance, identify service-quality risk, define task tiers, and include monitoring metrics.

---

## ASPP-PM-001 — Outdoor Music Festival Delivery

**Scenario:** A project manager must lead a three-day outdoor music festival with up to 15 performers and approximately 25,000 attendees. Risks include weather, crowd control, vendor coordination, security, permits, emergency response, and schedule conflicts.

**Expected Best Recommendation:** Use a hybrid project-management model: predictive planning for permits, safety, contracts, logistics, and infrastructure; agile coordination for event-day issue response.

**90+ Requirements:** Must narrow methodology choice, identify high-risk constraints, define governance, create an escalation plan, and include event-readiness checkpoints.

---

## ASPP-ADV-001 — Strategic Decision with Incomplete Data

**Scenario:** A company must decide whether to expand internationally, acquire a competitor, or focus on retention. Available data is incomplete and stakeholders disagree.

**Expected Best Recommendation:** Focus on retention first unless verified data proves expansion or acquisition has a superior risk-adjusted return.

**90+ Requirements:** Must recognize uncertainty, avoid fabrication, state assumptions, narrow choices, deliver one recommendation, and avoid invented facts or projections.

---

## 21. QA / Test Engineering Format

| Field | Value |
|---|---|
| Test ID | ASPP-001 |
| Category | Decision Analysis |
| Priority | High |
| Severity | Critical |
| Difficulty | Intermediate |

### Acceptance Criteria

| Criterion | Pass |
|---|---|
| All stages present | Yes |
| Single recommendation | Yes |
| Analysis included | Yes |
| Action plan included | Yes |
| No fabricated data | Yes |

### Result Matrix

| Stage | Pass / Fail |
|---|---|
| S |  |
| C |  |
| E |  |
| N |  |
| A |  |
| R |  |
| I |  |
| O |  |

**Total Score:** ____ / 100  
**Result:** [ ] Pass [ ] Fail

---

## 22. Automation-Friendly JSON Format

```json
{
  "benchmark_id": "ASPP-SCENARIO-001",
  "benchmark_name": "Structured Decision Optimization Evaluation",
  "version": "1.0",
  "creator": "Darren L. Allie",
  "creator_title": "Director of AI Workflow Optimization and AI Business Improvement",
  "organization": "Azure & Verdant Vistas, LLC",
  "framework": "The Allie Scenario Prompting Protocol",
  "abbreviation": "ASPP",
  "methodology": "SCENARIO",
  "difficulty": "Intermediate",
  "category": "Decision Analysis - Structured Reasoning - Prompt Engineering - AI Evaluation",
  "maximum_score": 100,
  "passing_score": 80,
  "exceptional_score_range": "90-100",
  "prompt": "A startup has a budget of $50,000 and must choose one of three growth initiatives: hire a full-time salesperson, increase paid advertising spend, or develop a customer referral program. The company has 12 months of runway, limited engineering resources, existing customer satisfaction scores above industry average, and no dedicated sales team. Apply the complete SCENARIO framework and recommend the single best course of action.",
  "expected_best_recommendation": "Develop a customer referral program as the primary growth initiative.",
  "required_sections": [
    "S - State the Desired Outcome",
    "C - Clarify the Scenario Context",
    "E - Examine Constraints and Risks",
    "N - Narrow the Decision Space",
    "A - Analyze with Logic, Reasoning, Coding, or Calculation",
    "R - Recommend the Best Single Output",
    "I - Indicate Additional Outcomes Only When Necessary",
    "O - Output an Executable Action Plan"
  ],
  "scoring_rubric": {
    "State Outcome": 10,
    "Clarify Context": 10,
    "Constraints and Risks": 15,
    "Narrow Decision Space": 15,
    "Analysis": 20,
    "Recommendation": 10,
    "Additional Outcomes": 5,
    "Action Plan": 15
  },
  "automatic_failure_conditions": [
    "Missing any SCENARIO stage",
    "Multiple primary recommendations",
    "No reasoning",
    "Unsupported claims",
    "No action plan",
    "Ignored constraints",
    "Fabricated facts, metrics, market data, financial projections, or assumptions not provided in the scenario"
  ],
  "calibration_examples_required": [
    "Passing response",
    "Failing response",
    "Borderline response"
  ],
  "regression_test_frequency": "Quarterly"
}
```

---

## 23. Automation-Friendly YAML Format

```yaml
benchmark_id: ASPP-SCENARIO-001
benchmark_name: Structured Decision Optimization Evaluation
version: "1.0"
creator: Darren L. Allie
creator_title: Director of AI Workflow Optimization and AI Business Improvement
organization: Azure & Verdant Vistas, LLC
framework: The Allie Scenario Prompting Protocol
abbreviation: ASPP
methodology: SCENARIO
difficulty: Intermediate
category: Decision Analysis - Structured Reasoning - Prompt Engineering - AI Evaluation
maximum_score: 100
passing_score: 80
exceptional_score_range: 90-100

prompt: >
  A startup has a budget of $50,000 and must choose one of three growth initiatives:
  hire a full-time salesperson, increase paid advertising spend, or develop a customer
  referral program. The company has 12 months of runway, limited engineering resources,
  existing customer satisfaction scores above industry average, and no dedicated sales team.
  Apply the complete SCENARIO framework and recommend the single best course of action.

expected_best_recommendation: Develop a customer referral program as the primary growth initiative.

required_sections:
  - S - State the Desired Outcome
  - C - Clarify the Scenario Context
  - E - Examine Constraints and Risks
  - N - Narrow the Decision Space
  - A - Analyze with Logic, Reasoning, Coding, or Calculation
  - R - Recommend the Best Single Output
  - I - Indicate Additional Outcomes Only When Necessary
  - O - Output an Executable Action Plan

scoring_rubric:
  State Outcome: 10
  Clarify Context: 10
  Constraints and Risks: 15
  Narrow Decision Space: 15
  Analysis: 20
  Recommendation: 10
  Additional Outcomes: 5
  Action Plan: 15

automatic_failure_conditions:
  - Missing any SCENARIO stage
  - Multiple primary recommendations
  - No reasoning
  - Unsupported claims
  - No action plan
  - Ignored constraints
  - Fabricated facts, metrics, market data, financial projections, or assumptions not provided in the scenario

calibration_examples_required:
  - Passing response
  - Failing response
  - Borderline response

regression_test_frequency: Quarterly
```

---

## 24. Repository Use

Recommended repository path:

```text
benchmarks/ASPP_Bench_Evaluation_Dataset_v1_0.md
```

This file is intended for inclusion in the official ASPP repository, Zenodo package, prompt template library, benchmark evaluation suite, and adoption materials.

---

## 25. Official Attribution Statement

The Allie Scenario Prompting Protocol (ASPP), ASPP-Bench, and the S.C.E.N.A.R.I.O. Framework are attributed to:

**Darren L. Allie**  
**Director of AI Workflow Optimization and AI Business Improvement**  
**Azure & Verdant Vistas, LLC**

---

## 26. Formal Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 27. Version History

| Version | Date | Description |
|---|---|---|
| 1.0 | 2026 | Initial ASPP-Bench Evaluation Dataset file for The Allie Scenario Prompting Protocol. |
