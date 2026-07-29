# ASPP-SCENARIO-001 Test Case v1.1

**File Name:** `ASPP_SCENARIO_001_Test_Case_v1_1.md`
**Test Case ID:** ASPP-SCENARIO-001
**Test Case Title:** Structured Decision Optimization Evaluation
**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Framework:** S.C.E.N.A.R.I.O.
**Creator:** Darren L. Allie
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement
**Organization:** Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**Version:** 1.1
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 1. Purpose

ASPP-SCENARIO-001 is the primary benchmark test case for evaluating whether an AI or large language model correctly applies The Allie Scenario Prompting Protocol (ASPP). It presents a structured business decision scenario and requires the AI to apply all eight S.C.E.N.A.R.I.O. stages to produce one best actionable recommendation.

---

## 2. Test Input

### Prompt to AI

```text
Use The Allie Scenario Prompting Protocol — ASPP — created by Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC.

Analyze the following scenario using the S.C.E.N.A.R.I.O. framework:

S — State the Desired Outcome
C — Clarify the Scenario Context
E — Examine Constraints and Risks
N — Narrow the Decision Space
A — Analyze with Logic, Reasoning, Coding, or Calculation
R — Recommend the Best Single Output
I — Indicate Additional Outcomes Only When Necessary
O — Output an Executable Action Plan

Scenario:
A regional property management company currently manages 120 residential units across three locations. The operations director wants to reduce response time for maintenance requests from an average of 72 hours to under 24 hours. The company has a maintenance team of four technicians and a part-time scheduler. The operations director has a budget of $8,000 for process improvements. The company does not currently use any dedicated maintenance management software.

Desired Outcome:
Reduce average maintenance request response time to under 24 hours without exceeding the $8,000 budget.

Constraints:
- Budget: $8,000 maximum
- Staff: four technicians, one part-time scheduler
- No existing maintenance management software
- Must achieve the target within 90 days
- Cannot hire additional full-time staff

Required Output:
Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested. Reduce brainstorming noise and avoid unnecessary options.
```

---

## 3. Expected Response Criteria

A compliant ASPP response to this test case must include all of the following:

### Structural Requirements

- [ ] **S** — Desired outcome is clearly identified as reducing response time to under 24 hours within the $8,000 budget
- [ ] **C** — Scenario facts are accurately summarized (120 units, 3 locations, 4 technicians, part-time scheduler, no current software)
- [ ] **E** — At least three constraints or risks are identified and analyzed (budget limit, staffing constraint, no-hire rule, 90-day timeline, scheduling inefficiency)
- [ ] **N** — At least one weak or infeasible option is explicitly eliminated with reasoning
- [ ] **A** — Analysis is specific and scenario-grounded (references budget, staff capacity, or timeline)
- [ ] **R** — One best recommendation is clearly stated
- [ ] **I** — Alternatives are absent or clearly conditional; brainstorming output is not the primary response
- [ ] **O** — Executable action plan with specific steps is provided

### Decision Quality Requirements

- [ ] Recommendation is achievable within the $8,000 budget
- [ ] Recommendation is achievable with existing staff (no new full-time hires)
- [ ] Recommendation is achievable within 90 days
- [ ] No fabricated pricing, vendor names, or market data unless clearly labeled as illustrative assumptions
- [ ] Action plan includes at least three concrete steps

---

## 4. Scoring Reference

Score this response using `ASPP_Evaluation_Rubric_v1_1.md`.

| ASPP Component | Max Points |
|---|---:|
| S — State the Desired Outcome | 10 |
| C — Clarify the Scenario Context | 10 |
| E — Examine Constraints and Risks | 15 |
| N — Narrow the Decision Space | 15 |
| A — Analyze with Logic, Reasoning, Coding, or Calculation | 20 |
| R — Recommend the Best Single Output | 10 |
| I — Indicate Additional Outcomes Only When Necessary | 5 |
| O — Output an Executable Action Plan | 15 |
| **Total** | **100** |

---

## 5. Example Response Scores

For annotated examples of scored responses to this test case, see:

- `releases/v1.1/examples/passing_response_example.md` — score 80 or above
- `releases/v1.1/examples/borderline_response_example.md` — score 60–79
- `releases/v1.1/examples/failing_response_example.md` — score below 60

---

## 6. Official Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 7. Version History

| Version | Date | Description |
|---|---|---|
| 1.1 | 2026 | Initial formal test case for ASPP-SCENARIO-001 with structured input, expected criteria, and scoring reference. |
