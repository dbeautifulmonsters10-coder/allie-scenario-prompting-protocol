# ASPP Evaluation Rubric v1.1

**File Name:** `ASPP_Evaluation_Rubric_v1_1.md`
**Rubric Name:** ASPP Evaluation Rubric
**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Framework:** S.C.E.N.A.R.I.O.
**Creator:** Darren L. Allie
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement
**Organization:** Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**Version:** 1.1
**Recommended License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
**Maximum Score:** 100
**Passing Score:** 80
**Exceptional Compliance Score:** 90–100

---

## 1. Purpose

The **ASPP Evaluation Rubric** is used to evaluate whether an AI or large language model response correctly applies **The Allie Scenario Prompting Protocol (ASPP)**.

The rubric evaluates both:

1. **Structural compliance** — whether all eight S.C.E.N.A.R.I.O. stages are present.
2. **Decision quality** — whether the response produces one logical, defensible, actionable, and non-fabricated recommendation.

A response should not receive a high score merely because it uses the correct headings. The score must reflect the quality of scenario interpretation, constraint analysis, decision narrowing, recommendation, and action plan.

---

## 2. Official Scoring Summary

| ASPP Component | Points |
|---|---:|
| **S — State the Desired Outcome** | 10 |
| **C — Clarify the Scenario Context** | 10 |
| **E — Examine Constraints and Risks** | 15 |
| **N — Narrow the Decision Space** | 15 |
| **A — Analyze with Logic, Reasoning, Coding, or Calculation** | 20 |
| **R — Recommend the Best Single Output** | 10 |
| **I — Indicate Additional Outcomes Only When Necessary** | 5 |
| **O — Output an Executable Action Plan** | 15 |
| **Total** | **100** |

---

## 3. Performance Levels

| Score | Rating | Interpretation |
|---:|---|---|
| **90–100** | Exceptional ASPP Compliance | Fully applies ASPP, provides one defensible recommendation, avoids fabrication, and delivers an executable action plan. |
| **80–89** | Strong ASPP Compliance | Mostly complete ASPP response with minor weakness in analysis, action planning, or alternative calibration. |
| **70–79** | Moderate ASPP Compliance | Includes the framework but has incomplete reasoning, weak narrowing, or limited actionability. |
| **60–69** | Weak ASPP Compliance | Uses some ASPP elements but is generic, noisy, incomplete, or insufficiently decision-focused. |
| **Below 60** | Non-Compliant | Missing major stages, provides weak reasoning, fabricates information, or fails to recommend a clear action. |

---

## 4. Stage-Level Scoring Guidance

### S — State the Desired Outcome (10 points)

| Points | Criteria |
|---:|---|
| 10 | Desired outcome is clearly identified and precisely reflects the user's goal |
| 7–9 | Desired outcome is present but slightly generic or loosely tied to the scenario |
| 4–6 | Outcome is mentioned but vague, incomplete, or misaligned |
| 0–3 | Outcome is absent or fundamentally incorrect |

### C — Clarify the Scenario Context (10 points)

| Points | Criteria |
|---:|---|
| 10 | All material facts, stakeholders, timeline, and conditions are accurately summarized |
| 7–9 | Context is mostly complete with minor omissions |
| 4–6 | Context is present but incomplete or contains unsupported assumptions |
| 0–3 | Context is missing, superficial, or fabricated |

### E — Examine Constraints and Risks (15 points)

| Points | Criteria |
|---:|---|
| 13–15 | At least three material constraints or risks are identified and analyzed with specificity |
| 9–12 | Two or three constraints are identified but analysis is incomplete |
| 5–8 | Constraints are mentioned but not analyzed |
| 0–4 | Constraints are missing, fabricated, or ignored |

### N — Narrow the Decision Space (15 points)

| Points | Criteria |
|---:|---|
| 13–15 | Weak, unrealistic, or redundant options are explicitly eliminated with clear reasoning |
| 9–12 | Some narrowing occurs but elimination logic is incomplete |
| 5–8 | Multiple options are listed without meaningful narrowing |
| 0–4 | Narrowing is absent or the response lists all options without elimination |

### A — Analyze with Logic, Reasoning, Coding, or Calculation (20 points)

| Points | Criteria |
|---:|---|
| 17–20 | Analysis is specific, scenario-grounded, uses appropriate reasoning, and supports the recommendation |
| 12–16 | Analysis is present but has gaps in logic, specificity, or connection to recommendation |
| 6–11 | Analysis is superficial or generic |
| 0–5 | Analysis is absent, fabricated, or circular |

### R — Recommend the Best Single Output (10 points)

| Points | Criteria |
|---:|---|
| 10 | One clear, defensible recommendation is provided |
| 7–9 | Recommendation is present but hedged excessively or weakly stated |
| 4–6 | Recommendation is present but poorly supported or competing with alternatives |
| 0–3 | No recommendation, multiple primary recommendations, or fabricated conclusion |

### I — Indicate Additional Outcomes Only When Necessary (5 points)

| Points | Criteria |
|---:|---|
| 5 | Alternatives are absent or presented only when materially justified and clearly conditional |
| 3–4 | Alternatives are mentioned but not prominently competing with the primary recommendation |
| 1–2 | Multiple options are listed in a way that dilutes the primary recommendation |
| 0 | Brainstorming output replaces decision analysis |

### O — Output an Executable Action Plan (15 points)

| Points | Criteria |
|---:|---|
| 13–15 | Action plan is specific, executable, sequenced, and includes success criteria or review cycle |
| 9–12 | Action plan is present but lacks specificity, sequencing, or success criteria |
| 5–8 | Action plan is vague or generic |
| 0–4 | Action plan is absent or non-actionable |

---

## 5. Automatic Failure Conditions

A response automatically fails if it does any of the following:

- Omits any S.C.E.N.A.R.I.O. stage
- Provides multiple primary recommendations
- Provides no reasoning
- Makes unsupported claims
- Provides no action plan
- Ignores scenario constraints
- Fabricates facts, metrics, market data, financial projections, legal claims, technical claims, or unsupported assumptions
- Presents invented numbers as if they are verified
- Claims certainty where the facts are incomplete
- Provides unsafe financial, legal, medical, compliance, or safety-sensitive advice without caution
- Replaces decision analysis with generic brainstorming

---

## 6. Anti-Fabrication Rule

The anti-fabrication rule is mandatory.

A response must not invent:

- Facts
- Metrics
- Market data
- Financial projections
- Legal requirements
- Technical capabilities
- Prices
- Rates
- Case law
- Medical claims
- User-specific details
- Assumptions not tied to the scenario

Assumptions are allowed only when they are:

1. Clearly labeled as assumptions
2. Necessary to complete the analysis
3. Directly tied to the scenario facts
4. Not presented as verified truth

---

## 7. 90+ Exceptional Compliance Checklist

A response should score **90 or higher** only if it satisfies all of the following:

- All eight S.C.E.N.A.R.I.O. stages are present
- The desired outcome is clearly stated
- Scenario context is accurately summarized
- All material constraints are acknowledged
- At least three risks or constraints are analyzed
- The decision space is narrowed through clear elimination logic
- The analysis is specific and scenario-grounded
- One best recommendation is clearly provided
- Alternatives are conditional, not competing
- No fabricated facts, metrics, projections, or unsupported assumptions are included
- The action plan is executable
- The action plan includes success criteria or KPIs where relevant
- The action plan includes a review cycle
- The response reduces brainstorming noise

---

## 8. Official Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 9. Version History

| Version | Date | Description |
|---|---|---|
| 1.1 | 2026 | Updated evaluation rubric with stage-level scoring guidance and expanded automatic failure conditions. |
| 1.0 | 2026 | Initial ASPP Evaluation Rubric. |
