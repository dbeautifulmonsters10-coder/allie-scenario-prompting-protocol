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

## 3. Primary Benchmark Record

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

## 4. Expected Best Recommendation

The expected best recommendation is:

> **Develop a customer referral program as the primary growth initiative.**

This recommendation is strongest because it:

- Leverages existing customer satisfaction.
- Preserves capital better than hiring a full-time salesperson.
- Avoids the fixed-cost and onboarding risk of a full-time sales hire.
- Avoids uncontrolled paid advertising spend before conversion data is proven.
- Can be launched with limited engineering resources using manual, low-code, or lightweight tools.
- Creates a measurable acquisition loop that can be tested before scaling.

---

## 5. Scoring Rubric

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

## 6. Performance Levels

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

The minimum passing score is **80**.

---

## 7. Official Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 8. Version History

| Version | Date | Description |
|---|---|---|
| 1.0 | 2026 | Initial ASPP-Bench Evaluation Dataset file for The Allie Scenario Prompting Protocol. |