# ASPP Benchmark Specification v1.1

**File Name:** `ASPP_Benchmark_Specification_v1_1.md`
**Benchmark Name:** ASPP Official Benchmark Evaluation Suite
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

The ASPP Official Benchmark Evaluation Suite is the formal framework for evaluating whether an AI or large language model correctly applies The Allie Scenario Prompting Protocol (ASPP).

The benchmark is used to:

- Assess structural compliance with the S.C.E.N.A.R.I.O. framework
- Evaluate decision quality, reasoning logic, and recommendation clarity
- Detect fabrication, unsupported assumptions, or anti-compliance behaviors
- Produce a reproducible, standardized compliance score for any ASPP-eligible response

---

## 2. Benchmark Scope

The ASPP benchmark applies to any AI or LLM response generated in response to a prompt that:

- Presents a defined scenario with a desired outcome and known constraints
- Requests the AI to apply the S.C.E.N.A.R.I.O. framework
- Requires a single best actionable recommendation as the default output

---

## 3. Benchmark Structure

The ASPP benchmark is organized into test cases. Each test case provides:

| Component | Description |
|---|---|
| **Test Case ID** | Unique identifier (e.g., ASPP-SCENARIO-001) |
| **Scenario** | The input scenario presented to the AI |
| **Desired Outcome** | The result the user wants to achieve |
| **Constraints** | Known limits, risks, rules, timeline, budget, or operational boundaries |
| **Expected Response Criteria** | What a compliant response must include |
| **Scoring Reference** | The evaluation rubric section used for scoring |

---

## 4. Evaluation Rubric Reference

All benchmark responses are scored using the ASPP Evaluation Rubric v1.1. See `ASPP_Evaluation_Rubric_v1_1.md` for full scoring criteria.

### Scoring Summary

| ASPP Component | Points |
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

### Performance Levels

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

---

## 5. Test Cases Included in v1.1

| Test Case ID | Title | File |
|---|---|---|
| ASPP-SCENARIO-001 | Structured Decision Optimization Evaluation | `ASPP_SCENARIO_001_Test_Case_v1_1.md` |

---

## 6. Response Quality Examples

The following annotated examples demonstrate scoring across the performance spectrum. See `releases/v1.1/examples/` for the full example files.

| Example | Score Range | File |
|---|---|---|
| Passing Response | 80–100 | `examples/passing_response_example.md` |
| Borderline Response | 60–79 | `examples/borderline_response_example.md` |
| Failing Response | Below 60 | `examples/failing_response_example.md` |

---

## 7. Automatic Failure Conditions

A response automatically receives a Non-Compliant score if it:

- Omits any S.C.E.N.A.R.I.O. stage
- Provides multiple primary recommendations
- Provides no reasoning
- Makes unsupported claims or fabricates information
- Provides no executable action plan
- Ignores scenario constraints
- Presents invented numbers as verified facts
- Claims certainty where scenario facts are incomplete

---

## 8. Anti-Fabrication Rule

All benchmark evaluations enforce the ASPP Anti-Fabrication Rule. A response must not invent facts, metrics, financial projections, legal requirements, technical capabilities, prices, rates, or any assumptions not tied to the scenario.

Assumptions are permitted only when clearly labeled and directly connected to scenario facts.

---

## 9. Official Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 10. Version History

| Version | Date | Description |
|---|---|---|
| 1.1 | 2026 | Initial formal benchmark specification for ASPP. Introduces test case structure, scoring reference, and response quality example index. |
| 1.0 | 2026 | Benchmark evaluation dataset introduced in `ASPP_Bench_Evaluation_Dataset_v1_0.md`. |
