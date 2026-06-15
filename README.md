# The Allie Scenario Prompting Protocol (ASPP)

**Repository Package:** The Allie Scenario Prompting Protocol  
**Abbreviation:** ASPP  
**Creator:** Darren L. Allie  
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement  
**Organization:** Azure & Verdant Vistas, LLC  
**DOI:** 10.5281/zenodo.20596641  
**Version:** 1.0  
**Recommended License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## Overview

**The Allie Scenario Prompting Protocol (ASPP)** is a scenario-constrained, outcome-first prompt engineering methodology created by **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**.

ASPP formalizes scenario-based prompting into a structured decision-support protocol designed to guide AI and large language model systems toward **one best actionable output** rather than an overextended list of possibilities.

ASPP is designed to reduce **brainstorming noise** by helping AI systems clarify the user's desired outcome, understand the scenario context, identify constraints and risks, narrow the decision space, apply logic or calculation where useful, recommend one best course of action, disclose alternatives only when necessary, and output an executable action plan.

---

## DOI

**10.5281/zenodo.20596641**

Suggested DOI link:

```text
https://doi.org/10.5281/zenodo.20596641
```

---

## Formal Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## Short Citation

**The Allie Scenario Prompting Protocol — ASPP** — Created by **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**. A scenario-based AI prompting method designed to produce one best actionable output through structured reasoning, constraint analysis, and decision narrowing to reduce brainstorming noise. DOI: **10.5281/zenodo.20596641**.

---

## Purpose

ASPP is intended for prompts where a user presents a scenario and needs a clear, useful, practical decision.

It is especially useful when the prompt involves:

- Business decisions.
- Financial tradeoffs.
- Project management.
- Operational planning.
- Staffing and scheduling.
- Workflow optimization.
- Real estate decisions.
- Credit and lending decisions.
- Compliance-sensitive decisions.
- Executive decision support.
- Personal decision conflicts.
- Time-sensitive scenarios.
- AI workflow design.

ASPP is not intended to replace open brainstorming, creative ideation, fiction writing, artistic variation, or exploratory research where the user intentionally wants many possible directions.

---

## The S.C.E.N.A.R.I.O. Framework

ASPP operates through the **S.C.E.N.A.R.I.O.** framework.

| Letter | Meaning | Function |
|---|---|---|
| **S** | **State the Desired Outcome** | Identify the result the user wants to achieve. |
| **C** | **Clarify the Scenario Context** | Define the facts, stakeholders, timeline, conditions, and assumptions. |
| **E** | **Examine Constraints and Risks** | Identify limits, risks, obligations, uncertainties, and failure points. |
| **N** | **Narrow the Decision Space** | Remove weak, unrealistic, redundant, or low-value options. |
| **A** | **Analyze with Logic, Reasoning, Coding, or Calculation** | Apply the appropriate analytical method to support the decision. |
| **R** | **Recommend the Best Single Output** | Provide one strongest actionable recommendation by default. |
| **I** | **Indicate Additional Outcomes Only When Necessary** | Mention alternatives only when materially justified or requested. |
| **O** | **Output an Executable Action Plan** | Convert the recommendation into practical next steps. |

---

## Core Decision Rule

ASPP follows this standard decision rule:

> Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested by the user.

---

## Anti-Fabrication Rule

ASPP requires that AI systems avoid inventing:

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

Assumptions are allowed only when they are clearly labeled and directly connected to the scenario facts.

---

## Standard ASPP Prompt Template

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
[Insert scenario here.]

Desired Outcome:
[Insert desired result here.]

Constraints:
[Insert known limits, risks, rules, timeline, budget, or operational boundaries.]

Required Output:
Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested. Reduce brainstorming noise and avoid unnecessary options.
```

---

## ASPP-Bench

**ASPP-Bench** is the benchmark-style evaluation dataset for testing whether an AI system correctly applies The Allie Scenario Prompting Protocol.

Primary benchmark:

**ASPP-SCENARIO-001: Structured Decision Optimization Evaluation**

ASPP-Bench evaluates whether a model can:

- Follow the complete S.C.E.N.A.R.I.O. sequence.
- Produce logical and defensible recommendations.
- Avoid unsupported conclusions.
- Avoid fabricated data.
- Provide one best recommendation.
- Deliver an executable action plan.
- Maintain consistency under uncertainty.

---

## Evaluation Rubric

ASPP uses a 100-point evaluation rubric.

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

Performance levels:

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

---

## Package Contents

This release package includes:

```text
ASPP_Preprint_v1_0.tex
ASPP_Specification_v1_0.md
ASPP_SCENARIO_Framework_v1_0.md
ASPP_Bench_Evaluation_Dataset_v1_0.md
ASPP_Evaluation_Rubric_v1_0.md
ASPP_Citation_Metadata.txt
ASPP_Abstract_and_Metadata.txt
LICENSE_CC_BY_4_0.txt
README.md
references.bib
```

---

## How to Use ASPP

1. Identify a scenario that requires a clear recommendation.
2. Insert the scenario into the ASPP prompt template.
3. State the desired outcome and known constraints.
4. Require the AI system to follow all eight S.C.E.N.A.R.I.O. stages.
5. Require one best actionable recommendation unless alternatives are materially necessary.
6. Review the output for accuracy, assumptions, risks, and actionability.
7. Use ASPP-Bench and the ASPP Evaluation Rubric to evaluate implementation quality.

---

## When to Use ASPP

Use ASPP when the user needs:

- A decision.
- A recommended course of action.
- A narrowed set of options.
- A risk-aware plan.
- A scenario-specific answer.
- A practical next-step sequence.

---

## When Not to Use ASPP as the Primary Method

Do not use ASPP as the primary method when the user wants:

- Open brainstorming.
- Creative writing.
- Many unranked options.
- Exploratory research without a decision.
- Artistic alternatives.
- Broad idea generation.

ASPP can still be used later to narrow ideas into one best recommendation.

---

## License

This work is recommended for release under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

Under CC BY 4.0, users may share and adapt the work with appropriate attribution to Darren L. Allie and citation of DOI: **10.5281/zenodo.20596641**.

License URL:

```text
https://creativecommons.org/licenses/by/4.0/
```

---

## Attribution

The Allie Scenario Prompting Protocol (ASPP), the S.C.E.N.A.R.I.O. Framework, ASPP-Bench, and related evaluation materials are attributed to:

**Darren L. Allie**  
**Director of AI Workflow Optimization and AI Business Improvement**  
**Azure & Verdant Vistas, LLC**

---

## Version History

| Version | Date | Description |
|---|---|---|
| 1.0 | 2026 | Initial README for The Allie Scenario Prompting Protocol repository and Zenodo package. |

---

## Status

This package is prepared for:

- Zenodo archive upload.
- GitHub repository publication.
- Prompt template library development.
- Benchmark evaluation use.
- Community review and adoption.
- Future ASPP versioning and validation.