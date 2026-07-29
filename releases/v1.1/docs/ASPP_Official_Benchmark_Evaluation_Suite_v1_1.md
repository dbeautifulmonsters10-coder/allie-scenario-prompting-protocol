# ASPP Official Benchmark Evaluation Suite v1.1

**File Name:** `ASPP_Official_Benchmark_Evaluation_Suite_v1_1.md`
**Suite Name:** ASPP Official Benchmark Evaluation Suite
**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Framework:** S.C.E.N.A.R.I.O.
**Creator:** Darren L. Allie
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement
**Organization:** Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**Version:** 1.1
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 1. Overview

The **ASPP Official Benchmark Evaluation Suite** is the complete formal evaluation framework for The Allie Scenario Prompting Protocol (ASPP). It consolidates the benchmark specification, evaluation rubric, test cases, response quality examples, and schema definitions into a single referenced suite for reproducible AI compliance testing.

This document serves as the top-level reference for the v1.1 benchmark suite. For individual component details, see the linked files in the package index (`releases/v1.1/manifest.md`).

---

## 2. Suite Components

| Component | File | Purpose |
|---|---|---|
| Benchmark Specification | `benchmarks/ASPP_Benchmark_Specification_v1_1.md` | Defines scope, criteria, test case structure, and scoring standards |
| Evaluation Rubric | `benchmarks/ASPP_Evaluation_Rubric_v1_1.md` | 100-point rubric with stage-level scoring guidance |
| Test Case 001 | `benchmarks/ASPP_SCENARIO_001_Test_Case_v1_1.md` | Structured input and expected criteria for ASPP-SCENARIO-001 |
| Passing Example | `examples/passing_response_example.md` | Annotated example scoring 80 or above |
| Failing Example | `examples/failing_response_example.md` | Annotated example scoring below 60 |
| Borderline Example | `examples/borderline_response_example.md` | Annotated example scoring 60–79 |
| JSON Schema | `schemas/ASPP_Benchmark_v1_1.json` | Machine-readable benchmark record schema |
| YAML Schema | `schemas/ASPP_Benchmark_v1_1.yaml` | Machine-readable benchmark record schema |
| Zenodo Metadata | `zenodo/ZENODO_METADATA_v1_1.md` | Deposition metadata for this suite |

All paths above are relative to `releases/v1.1/`.

---

## 3. How to Use This Suite

### For AI Evaluation

1. Present the test case input from `ASPP_SCENARIO_001_Test_Case_v1_1.md` to the AI being evaluated.
2. Collect the AI response.
3. Score the response using `ASPP_Evaluation_Rubric_v1_1.md`.
4. Compare the score to the performance levels defined in the rubric.
5. Record the result using the schema defined in `ASPP_Benchmark_v1_1.json` or `ASPP_Benchmark_v1_1.yaml`.

### For Training and Reference

- Use `passing_response_example.md` to understand what a compliant response looks like.
- Use `failing_response_example.md` to understand common non-compliance patterns.
- Use `borderline_response_example.md` to calibrate scoring at the margin.

---

## 4. Scoring Summary

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

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

---

## 5. Official Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 6. Version History

| Version | Date | Description |
|---|---|---|
| 1.1 | 2026 | Initial ASPP Official Benchmark Evaluation Suite. Consolidates specification, rubric, test case, examples, schemas, and Zenodo metadata. |
