# The Allie Scenario Prompting Protocol (ASPP)

**A Scenario-Constrained, Outcome-First Method for Prompt Engineering**

[![Version](https://img.shields.io/badge/version-v1.0.0-blue)]()
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-green)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20596641-blue)](https://doi.org/10.5281/zenodo.20596641)

---

## Official Attribution

**The Allie Scenario Prompting Protocol (ASPP)** was created by:

**Darren L. Allie**  
**Director of AI Workflow Optimization and AI Business Improvement**  
**Azure & Verdant Vistas, LLC**

**DOI:** [10.5281/zenodo.20596641](https://doi.org/10.5281/zenodo.20596641)

---

## Overview

The **Allie Scenario Prompting Protocol (ASPP)** is a formal scenario-based prompt engineering methodology designed to guide AI and large language model systems toward **one best actionable output** through structured scenario framing, constraint analysis, decision narrowing, and executable action planning.

ASPP is not a claim that the broad phrase **scenario prompting** or the general practice of placing an AI system into a hypothetical or real-world situation is new. Instead, ASPP is a distinct and bounded formalization of scenario-based prompting that uses the **S.C.E.N.A.R.I.O.** framework to reduce brainstorming noise, improve decision discipline, and produce clearer, more usable recommendations.

---

## Core Purpose

ASPP is designed for users who need AI systems to:

- Clarify a desired outcome.
- Understand scenario context.
- Identify constraints, risks, and missing facts.
- Narrow the decision space.
- Analyze options using logic, reasoning, calculation, coding, or domain-specific evaluation.
- Recommend one best actionable output.
- Mention alternatives only when materially necessary.
- Produce an executable action plan.

---

## The S.C.E.N.A.R.I.O. Framework

ASPP uses the **S.C.E.N.A.R.I.O.** framework:

| Letter | Meaning | Function |
|---|---|---|
| **S** | **State the Desired Outcome** | Identify the result the user wants to achieve. |
| **C** | **Clarify the Scenario Context** | Define facts, stakeholders, timeline, conditions, and assumptions. |
| **E** | **Examine Constraints and Risks** | Identify limits, risks, obligations, uncertainties, and failure points. |
| **N** | **Narrow the Decision Space** | Remove weak, unrealistic, redundant, or low-value options. |
| **A** | **Analyze with Logic, Reasoning, Coding, or Calculation** | Apply the appropriate analytical method. |
| **R** | **Recommend the Best Single Output** | Provide one strongest actionable recommendation by default. |
| **I** | **Indicate Additional Outcomes Only When Necessary** | Mention alternatives only when materially justified or requested. |
| **O** | **Output an Executable Action Plan** | Convert the recommendation into practical next steps. |

---

## Decision Rule

ASPP uses the following decision rule:

> **Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested by the user.**

This rule is intended to reduce unnecessary option generation and move AI-assisted work from broad brainstorming toward focused decision support.

---

## Anti-Fabrication Rule

ASPP prohibits fabricated or unsupported claims.

AI systems using ASPP should not invent:

- Facts.
- Metrics.
- Market data.
- Financial projections.
- Legal requirements.
- Technical capabilities.
- Prices or rates.
- User-specific details.
- Unsupported assumptions.

When assumptions are necessary, they should be clearly labeled and tied directly to the scenario.

---

## Repository Contents

This repository contains the public ASPP v1.0.0 release package.

```text
allie-scenario-prompting-protocol/
│
├── README.md
├── LICENSE.txt
├── CITATION.cff
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── RELEASE_NOTES_v1_0.md
│
├── docs/
│   ├── ASPP_Specification_v1_0.md
│   ├── ASPP_SCENARIO_Framework_v1_0.md
│   └── ASPP_Standards_Alignment_Document_v1_0.md
│
├── templates/
│   └── ASPP_Template_Library_v1_0.md
│
├── benchmarks/
│   ├── ASPP_Bench_Evaluation_Dataset_v1_0.md
│   └── ASPP_Evaluation_Rubric_v1_0.md
│
├── preprint/
│   ├── ASPP_Preprint_Zenodo_Ready_v1_0_DOI.pdf
│   ├── ASPP_Preprint_v1_0.docx
│   ├── ASPP_Preprint_v1_0.tex
│   └── references.bib
│
├── figures/
│   ├── figure1_aspp_decision_constriction_model.svg
│   └── figure2_scenario_framework.svg
│
└── spaces/
    └── ASPP_HuggingFace_Space_Demo_v1_0/
```

---

## Main Documents

| Document | Purpose |
|---|---|
| [`docs/ASPP_Specification_v1_0.md`](docs/ASPP_Specification_v1_0.md) | Defines ASPP, its purpose, decision rule, and protocol structure. |
| [`docs/ASPP_SCENARIO_Framework_v1_0.md`](docs/ASPP_SCENARIO_Framework_v1_0.md) | Explains each S.C.E.N.A.R.I.O. stage. |
| [`templates/ASPP_Template_Library_v1_0.md`](templates/ASPP_Template_Library_v1_0.md) | Provides reusable ASPP prompt templates. |
| [`benchmarks/ASPP_Bench_Evaluation_Dataset_v1_0.md`](benchmarks/ASPP_Bench_Evaluation_Dataset_v1_0.md) | Contains ASPP benchmark scenario data. |
| [`benchmarks/ASPP_Evaluation_Rubric_v1_0.md`](benchmarks/ASPP_Evaluation_Rubric_v1_0.md) | Provides the 100-point ASPP evaluation rubric. |
| [`docs/ASPP_Standards_Alignment_Document_v1_0.md`](docs/ASPP_Standards_Alignment_Document_v1_0.md) | Maps ASPP to AI governance, risk, and security frameworks. |
| [`preprint/ASPP_Preprint_Zenodo_Ready_v1_0_DOI.pdf`](preprint/ASPP_Preprint_Zenodo_Ready_v1_0_DOI.pdf) | Formal ASPP preprint manuscript. |

---

## Quick-Start ASPP Prompt

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

Known Facts:
[Insert confirmed facts here.]

Constraints:
[Insert known limits, risks, rules, timeline, budget, or operational boundaries.]

Required Output:
Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested. Reduce brainstorming noise and avoid unnecessary options. Clearly label assumptions and do not fabricate facts, metrics, market data, legal claims, financial projections, or user-specific details.
```

---

## Use Cases

ASPP is intended for structured scenario-based AI assistance in areas such as:

- Business strategy.
- Financial decision support.
- Operations and staffing.
- Project management.
- Real estate investment analysis.
- AI workflow optimization.
- Customer-service escalation.
- Technical and coding decisions.
- Legal or compliance-sensitive decision support.
- Healthcare administration and insurance claim workflows.
- Crisis or urgent decision scenarios.
- Prompt-engineering evaluation.

---

## ASPP-Bench

**ASPP-Bench** is the benchmark evaluation dataset associated with the protocol. It is designed to test whether an AI response follows the S.C.E.N.A.R.I.O. structure, narrows the decision space, avoids fabrication, recommends one best output, and ends with an executable action plan.

The primary benchmark evaluates whether an AI system can provide structured decision support for a startup with limited capital and multiple strategic options.

---

## ASPP Evaluation Rubric

The ASPP Evaluation Rubric scores responses on a 100-point scale:

| Component | Points |
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

Performance bands:

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Passing ASPP Compliance |
| 70–79 | Partial ASPP Compliance |
| Below 70 | Insufficient ASPP Compliance |

---

## Standards Alignment

The ASPP Standards-Alignment Document maps ASPP to major AI governance, risk, and security frameworks, including:

- NIST AI Risk Management Framework.
- NIST Generative AI Profile.
- ISO/IEC 42001:2023 AI Management System concepts.
- OWASP Top 10 for Large Language Model Applications.
- Internal enterprise AI governance practices.

See:

- [`docs/ASPP_Standards_Alignment_Document_v1_0.md`](docs/ASPP_Standards_Alignment_Document_v1_0.md)

---

## Hugging Face Demo

The ASPP Hugging Face Space demo is designed to let users enter a scenario and generate an ASPP-style S.C.E.N.A.R.I.O. output.

Recommended Space configuration:

```text
SDK: Gradio
Template: Blank
License: cc-by-4.0
Visibility: Public
Hardware: CPU Basic
```

The demo package includes:

```text
app.py
requirements.txt
README.md
HF_SPACE_SETUP_GUIDE.md
```

---

## Recommended Citation

```text
Allie, Darren L. The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering. Azure & Verdant Vistas, LLC, 2026. DOI: 10.5281/zenodo.20596641.
```

BibTeX-style citation:

```bibtex
@misc{allie2026aspp,
  author       = {Allie, Darren L.},
  title        = {The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering},
  year         = {2026},
  publisher    = {Azure & Verdant Vistas, LLC},
  doi          = {10.5281/zenodo.20596641},
  url          = {https://doi.org/10.5281/zenodo.20596641}
}
```

---

## License

This project is released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You may share and adapt this work with proper attribution to:

**Darren L. Allie**  
**Director of AI Workflow Optimization and AI Business Improvement**  
**Azure & Verdant Vistas, LLC**

License summary: <https://creativecommons.org/licenses/by/4.0/>

---

## Version

**Current public release:** `v1.0.0`  
**Release title:** `ASPP v1.0.0 — Initial Public Release`

---

## Contribution Guidelines

Contributions, feedback, benchmark submissions, and issue reports are welcome.

Recommended contribution areas include:

- Additional ASPP templates.
- New benchmark scenarios.
- Rubric calibration examples.
- External model evaluations.
- Standards-alignment improvements.
- Documentation clarity.
- Hugging Face Space improvements.

Please see:

- [`CONTRIBUTING.md`](CONTRIBUTING.md)
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md)

---

## Status

ASPP v1.0.0 is the first public release of the protocol, intended for publication, archiving, testing, evaluation, and community feedback.

This release establishes ASPP as a formal scenario-based prompting methodology credited to **Darren L. Allie**, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC.

---

## Official Short Description

**The Allie Scenario Prompting Protocol (ASPP)** is a scenario-based AI prompting method designed to produce one best actionable output through structured reasoning, constraint analysis, and decision narrowing to reduce brainstorming noise.

---

## Acknowledgment

This repository is part of the public documentation and research package for **The Allie Scenario Prompting Protocol (ASPP)**, created by **Darren L. Allie**, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC.
