# The Allie Scenario Prompting Protocol — ASPP

## Core Specification Document

**Version:** 1.0  
**DOI:** 10.5281/zenodo.20596641  
**Created by:** Darren L. Allie  
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement  
**Organization:** Azure & Verdant Vistas, LLC  
**Document Type:** Prompt Engineering Protocol Specification  
**Primary Domain:** Prompt Engineering, Large Language Models, AI Workflow Optimization, Scenario-Based Decision Support  
**Recommended License:** Creative Commons Attribution 4.0 International — CC BY 4.0  

---

## 1. Formal Attribution

**The Allie Scenario Prompting Protocol — ASPP** is credited to **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**.

ASPP is presented as a structured, scenario-based prompt-engineering protocol designed to guide AI and large language model systems toward one best actionable output through outcome identification, scenario-context clarification, constraint analysis, decision-space narrowing, logical reasoning, and executable action planning.

---

## 2. Purpose

The purpose of ASPP is to convert scenario-based prompts into focused, decision-ready outputs.

Many AI systems respond to complex scenarios by generating broad lists of options, alternative possibilities, and open-ended recommendations. While this can be useful for brainstorming, it may create decision overload when the user needs one clear course of action.

ASPP addresses this problem by requiring the AI system to:

1. Identify the user’s desired outcome.
2. Clarify the scenario context.
3. Examine constraints, risks, and material assumptions.
4. Narrow the decision space.
5. Analyze using logic, reasoning, coding, calculation, or structured comparison where needed.
6. Recommend the best single output.
7. Indicate additional outcomes only when necessary.
8. Output an executable action plan.

The central purpose of ASPP is to **reduce brainstorming noise** and improve decision clarity in scenario-based prompting.

---

## 3. Bounded Novelty Claim

ASPP does **not** claim to invent the general phrase “scenario prompting,” nor does it claim to invent the broad practice of placing an AI system inside a real-world or hypothetical scenario.

Instead, ASPP is positioned as a **new formalization of scenario-based prompting** that emphasizes:

- Scenario framing.
- Desired-outcome alignment.
- Constraint recognition.
- Decision-space narrowing.
- One-best-output discipline.
- Conditional alternative disclosure.
- Actionable implementation planning.
- Reduced brainstorming noise.

ASPP’s novelty is not the use of scenarios alone. Its distinct contribution is the formal combination of scenario-based prompting with **decision constriction**, meaning the protocol directs the AI system toward a single best actionable recommendation unless materially probable alternatives must be disclosed.

---

## 4. Formal Definition

**The Allie Scenario Prompting Protocol — ASPP — is a scenario-based prompt-engineering protocol that formalizes how AI systems should interpret, analyze, and respond to real-world or hypothetical scenarios by identifying the desired outcome, clarifying context, examining constraints and risks, narrowing the decision space, applying reasoning or calculation where needed, and producing one best actionable output to reduce brainstorming noise.**

---

## 5. Core Principle

The core principle of ASPP is:

> When a user presents a scenario requiring a decision, the AI system should prioritize the strongest actionable recommendation over a broad list of possibilities, unless multiple outcomes are materially probable, materially equal, or explicitly requested by the user.

This principle separates ASPP from general brainstorming, exploratory ideation, or unlimited option-generation prompts.

---

## 6. SCENARIO Framework

ASPP operates through the acronym **SCENARIO**. Each letter represents a required operating stage.

| Letter | Official ASPP Meaning | Required Function |
|---|---|---|
| **S** | **State the Desired Outcome** | Identify the result the user wants to achieve. |
| **C** | **Clarify the Scenario Context** | Define relevant facts, stakeholders, timeline, and assumptions. |
| **E** | **Examine Constraints and Risks** | Identify limits, risks, obligations, and restrictions. |
| **N** | **Narrow the Decision Space** | Remove weak, unrealistic, or unnecessary options. |
| **A** | **Analyze with Logic, Reasoning, Coding, or Calculation** | Apply the appropriate analytical method. |
| **R** | **Recommend the Best Single Output** | Provide the strongest actionable recommendation. |
| **I** | **Indicate Additional Outcomes Only When Necessary** | Mention alternatives only when materially justified. |
| **O** | **Output an Executable Action Plan** | Provide practical next steps for implementation. |

### 6.1 S — State the Desired Outcome

The AI system must first identify what the user is trying to achieve. The desired outcome becomes the anchor for the entire response.

### 6.2 C — Clarify the Scenario Context

The AI system must identify the relevant facts surrounding the situation, including stakeholders, timeline, environment, resources, known facts, and assumptions.

### 6.3 E — Examine Constraints and Risks

The AI system must identify limits and risks that affect the recommendation, such as budget, time, legal exposure, safety, credit impact, operational capacity, compliance, or data uncertainty.

### 6.4 N — Narrow the Decision Space

The AI system must remove weak, unrealistic, redundant, or low-value options. This is the defining decision-constriction stage of ASPP.

### 6.5 A — Analyze with Logic, Reasoning, Coding, or Calculation

The AI system must apply the level of analysis required by the scenario, including logical reasoning, financial calculation, operational modeling, coding, data analysis, risk scoring, or timeline sequencing when useful.

### 6.6 R — Recommend the Best Single Output

The AI system must provide the best single recommendation by default. The recommendation should be clear, direct, defensible, scenario-specific, and immediately actionable.

### 6.7 I — Indicate Additional Outcomes Only When Necessary

The AI system should mention additional outcomes only when two or more options are materially close, missing facts could change the recommendation, risk requires contingency awareness, or the user explicitly requests alternatives.

### 6.8 O — Output an Executable Action Plan

The final output must include a practical action plan explaining what to do first, what to verify, what to avoid, what risks to monitor, and what next step completes the decision.

---

## 7. ASPP Output Rule

The standard ASPP output rule is:

> Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested by the user.

If additional outcomes exist but are not necessary to expand, the AI may state:

> Additional possible outcomes are available, but the strongest recommendation is clear under the facts provided.

---

## 8. Alternative Disclosure Rule

ASPP allows alternatives only when justified.

Alternatives should be disclosed when:

- The top recommendation depends on an unconfirmed fact.
- The decision has high legal, medical, financial, or safety consequences.
- A secondary option becomes stronger under a clearly defined condition.
- The user’s stated outcome is ambiguous.
- A constraint prevents a single recommendation from being reliable.

Alternatives should not be disclosed merely to fill space or appear comprehensive.

---

## 9. Anti-Brainstorming Noise Rule

ASPP is designed to reduce brainstorming noise.

For ASPP purposes, **brainstorming noise** means:

- Too many options.
- Unranked suggestions.
- Repetitive recommendations.
- Generic advice.
- Unnecessary hypotheticals.
- Equal treatment of weak and strong options.
- Long lists that delay decision-making.
- Output that informs but does not direct action.

ASPP requires the AI to favor decision clarity over volume.

---

## 10. Anti-Fabrication Rule

ASPP responses must not fabricate facts, metrics, market data, financial projections, legal claims, technical claims, user-specific details, or assumptions not provided in the scenario.

Assumptions are allowed only when they are:

1. Clearly labeled as assumptions.
2. Necessary to complete the analysis.
3. Directly tied to the scenario facts.
4. Not presented as verified truth.

---

## 11. Recommended Use Cases

ASPP is best suited for scenario prompts involving:

- Business decisions.
- Financial tradeoffs.
- Project management.
- Operational planning.
- Workflow optimization.
- Real estate decisions.
- Credit and lending scenarios.
- Labor and staffing issues.
- Customer-service escalation.
- Legal or compliance-sensitive choices.
- Personal decision conflicts.
- Time-sensitive choices.
- Risk-based decision-making.
- AI workflow design.
- Executive decision support.

---

## 12. Situations Where ASPP Should Not Be the Primary Method

ASPP is not the best primary method when the user wants:

- Open-ended brainstorming.
- Creative ideation.
- Fiction writing.
- Many possible concepts.
- Exploratory research without a decision.
- Artistic variation.
- Unranked idea generation.
- Broad market discovery.
- A list of alternatives with no need to choose.

In those cases, ASPP may still be used later to narrow ideas into one decision.

---

## 13. Minimum Input Requirements

A strong ASPP prompt should include:

1. The scenario.
2. The desired outcome.
3. Known facts.
4. Constraints.
5. Risks.
6. Time pressure.
7. Decision that must be made.
8. Whether alternatives are allowed.
9. Any calculations or data that should be considered.

If these fields are missing, the AI may use reasonable assumptions, but must mark them clearly.

---

## 14. Standard ASPP Prompt Template

```text
Use The Allie Scenario Prompting Protocol — ASPP — created by Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC.

Analyze the following scenario using the SCENARIO framework:

S — State the Desired Outcome
C — Clarify the Scenario Context
E — Examine Constraints and Risks
N — Narrow the Decision Space
A — Analyze with Logic, Reasoning, Coding, or Calculation
R — Recommend the Best Single Output
I — Indicate Additional Outcomes Only When Necessary
O — Output an Executable Action Plan

Scenario:
[Insert the scenario here.]

Desired Outcome:
[Insert what the user wants to accomplish.]

Constraints:
[Insert limits, risks, rules, timeline, budget, or operational boundaries.]

Required Output:
Return one best actionable recommendation unless more than one outcome is materially probable. Reduce brainstorming noise and avoid unnecessary options.
```

---

## 15. Standard ASPP Output Structure

A complete ASPP response should include:

1. **Best Recommendation**
2. **Why This Is the Best Option**
3. **Relevant Constraints and Risks**
4. **Essential Analysis**
5. **Action Plan**
6. **Alternative Note Only If Necessary**

The output should be concise, decisive, and actionable.

---

## 16. ASPP-Bench Evaluation Summary

ASPP may be evaluated through **ASPP-Bench**, a benchmark-style evaluation dataset designed to test whether an AI system correctly implements the protocol.

The core ASPP-Bench scoring rubric uses a 100-point scale:

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

Performance levels:

| Score | Rating |
|---:|---|
| 90–100 | Exceptional ASPP Compliance |
| 80–89 | Strong ASPP Compliance |
| 70–79 | Moderate ASPP Compliance |
| 60–69 | Weak ASPP Compliance |
| Below 60 | Non-Compliant |

A response automatically fails if it omits any SCENARIO stage, provides multiple primary recommendations, provides no reasoning, makes unsupported claims, provides no action plan, ignores scenario constraints, or fabricates facts, metrics, market data, financial projections, or assumptions not provided in the scenario.

---

## 17. Evaluation Criteria

ASPP outputs should be evaluated using the following criteria:

| Criterion | Description |
|---|---|
| Desired Outcome Alignment | Does the output solve the user’s stated goal? |
| Context Recognition | Does the output correctly interpret the scenario? |
| Constraint Awareness | Does the output identify limits and risks? |
| Decision Narrowing | Does the output eliminate weak or unnecessary options? |
| Reasoning Quality | Is the recommendation logically supported? |
| Calculation/Data Use | Are calculations or data used when helpful? |
| Single-Best-Output Discipline | Does the output avoid unnecessary alternatives? |
| Actionability | Can the user act on the recommendation immediately? |
| Alternative Calibration | Are alternatives mentioned only when justified? |
| Noise Reduction | Does the output reduce confusion and decision overload? |
| Trustworthiness | Does the output avoid unsupported claims or fabricated facts? |

---

## 18. Performance Levels

ASPP performance may be classified as follows:

| Level | Description |
|---|---|
| Excellent | Produces one clear, justified, actionable recommendation with strong constraint awareness. |
| Good | Produces a useful recommendation with minor missing details or limited risk analysis. |
| Acceptable | Provides a workable answer but includes some unnecessary options or weak prioritization. |
| Poor | Produces generic advice, excessive brainstorming, or insufficient scenario analysis. |
| Failure | Ignores constraints, fabricates facts, gives unsafe guidance, or fails to recommend a clear action. |

---

## 19. Example Use Case

### Scenario

A user needs to apply for a Home Equity Line of Credit but has a lower-than-desired credit score. The user also needs housing and is considering an apartment complex offering two months of free rent if a lease is signed within four days. However, the apartment application may require a credit check, which could reduce the user’s HELOC borrowing power.

### ASPP-Style Recommendation

The strongest recommendation is to prioritize protecting the HELOC borrowing capacity first and avoid authorizing any apartment application that creates a hard credit inquiry unless the apartment complex confirms in writing that the screening is a soft pull or accepts a self-shared credit report.

### Why This Fits ASPP

This scenario contains competing financial priorities, time pressure, credit risk, and a need for decision sequencing. A broad list of options could create confusion. ASPP is appropriate because the user needs one strongest action path.

---

## 20. Relationship to Existing Prompting Methods

ASPP does not replace existing prompt-engineering methods. It may incorporate elements from other methods when useful.

| Existing Method | Relationship to ASPP |
|---|---|
| Role Prompting | May be used to define the AI’s professional role in the scenario. |
| Chain-of-Thought | May support complex reasoning, though ASPP does not require full reasoning disclosure. |
| ReAct | May support tool use and external action when the scenario requires it. |
| Tree of Thoughts | May be useful internally for comparison, but ASPP limits final output branching. |
| Plan-and-Solve | May support stepwise problem solving. |
| Prompt Pattern Catalogs | May provide reusable structures, while ASPP provides a scenario-decision protocol. |

ASPP’s distinct contribution is the formal requirement to narrow the output toward one best actionable recommendation.

---

## 21. Platform Compatibility

ASPP can be used across:

- ChatGPT.
- Claude.
- Gemini.
- Microsoft Copilot.
- Perplexity.
- Custom GPTs.
- AI agents.
- Enterprise chatbots.
- Internal workflow automation tools.
- Prompt libraries.
- AI decision-support systems.
- Low-code and no-code automation environments.

The protocol is platform-agnostic because it is based on prompt structure, reasoning discipline, and output requirements rather than a single model architecture.

---

## 22. Governance and Human Review

ASPP is a decision-support protocol, not a replacement for professional judgment.

Human review is especially important when the scenario involves:

- Legal decisions.
- Medical decisions.
- Financial decisions.
- Employment decisions.
- Safety risks.
- Contractual obligations.
- Regulated industries.
- High-value transactions.
- Sensitive personal information.

In these areas, ASPP should support decision clarity while preserving human accountability.

---

## 23. Official Short Citation Version

**The Allie Scenario Prompting Protocol — ASPP** — Created by **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**. A scenario-based AI prompting method designed to produce one best actionable output through structured reasoning, constraint analysis, and decision narrowing **to reduce brainstorming noise**. DOI: **10.5281/zenodo.20596641**.

---

## 24. Formal Citation Version

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 25. Recommended Repository File Name

```text
ASPP_Specification_v1_0.md
```

---

## 26. Version History

| Version | Date | Description |
|---|---|---|
| 1.0 | 2026 | Initial core specification defining ASPP, SCENARIO framework, output rules, evaluation criteria, attribution statement, DOI, and use cases. |

---

## 27. Completion Statement

This Core Specification Document establishes **The Allie Scenario Prompting Protocol — ASPP** as a bounded, structured, scenario-based prompt-engineering methodology credited to **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**.

It is intended to serve as the foundation for the ASPP preprint manuscript, prompt template library, benchmark-style evaluation set, GitHub repository, DOI archive, and adoption outreach package.
