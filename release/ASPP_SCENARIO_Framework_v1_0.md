# The Allie Scenario Prompting Protocol — SCENARIO Framework

**File Name:** `ASPP_SCENARIO_Framework_v1_0.md`  
**Framework:** The Allie Scenario Prompting Protocol (ASPP)  
**Framework Component:** S.C.E.N.A.R.I.O.  
**Version:** 1.0  
**Creator:** Darren L. Allie  
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement  
**Organization:** Azure & Verdant Vistas, LLC  
**DOI:** 10.5281/zenodo.20596641  
**License Recommendation:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 1. Purpose

The **S.C.E.N.A.R.I.O. Framework** is the operating structure of **The Allie Scenario Prompting Protocol (ASPP)**. It is designed to guide AI and large language model systems through disciplined scenario-based analysis, decision narrowing, and executable recommendation generation.

The framework is intended for prompts where the user presents a real-world or hypothetical scenario and needs the AI system to produce **one best actionable output** rather than a broad list of brainstorming options.

---

## 2. Official SCENARIO Acronym

**S.C.E.N.A.R.I.O.** stands for:

| Letter | Official ASPP Meaning | Required Function |
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

## 3. One-Sentence Definition

The **S.C.E.N.A.R.I.O. Framework** is the structured operating method of ASPP that guides AI systems to state the desired outcome, clarify context, examine constraints, narrow decision options, analyze the situation, recommend one best output, disclose alternatives only when necessary, and produce an executable action plan.

---

## 4. Framework Principle

The core principle of S.C.E.N.A.R.I.O. is:

> When a scenario requires a decision, the AI system should identify the strongest actionable recommendation and avoid unnecessary brainstorming noise unless multiple outcomes are materially probable or explicitly requested.

---

## 5. Detailed Stage Definitions

## S — State the Desired Outcome

The AI system must first identify the result the user wants to achieve.

This stage answers:

- What does the user want to accomplish?
- What decision needs to be made?
- What outcome should the response optimize for?
- What would a successful answer look like?

**Required Output:** A clear statement of the user’s desired result.

**Failure Mode:** No explicit objective, a vague goal, or a misstatement of what the user is trying to achieve.

---

## C — Clarify the Scenario Context

The AI system must summarize the facts, conditions, and circumstances that shape the scenario.

This stage may include:

- People or stakeholders involved.
- Timeline or urgency.
- Financial details.
- Operational conditions.
- Known facts.
- Missing information.
- Assumptions that must be clearly labeled.
- Current problem state.
- Available resources.

**Required Output:** A concise but accurate summary of the scenario context.

**Failure Mode:** Omitting material facts, adding unsupported facts, or failing to distinguish known facts from assumptions.

---

## E — Examine Constraints and Risks

The AI system must identify the limits and risks that affect the recommendation.

Constraints and risks may include:

- Budget limits.
- Time pressure.
- Credit or financial impact.
- Legal or compliance concerns.
- Safety issues.
- Labor capacity.
- Technology limitations.
- Contractual obligations.
- Ethical boundaries.
- Operational disruption.
- Reputational risk.
- Data uncertainty.

**Required Output:** A clear analysis of material risks and constraints that shape the decision.

**Failure Mode:** Ignoring constraints, treating all options as risk-free, or inventing unsupported risks or metrics.

---

## N — Narrow the Decision Space

The AI system must reduce the number of viable options by eliminating weak, unrealistic, redundant, or low-value paths.

This is the central decision-constriction stage of ASPP.

This stage answers:

- Which options fail the constraints?
- Which options create unnecessary risk?
- Which options do not support the desired outcome?
- Which option is strongest based on the scenario facts?
- Which options should be removed or treated only as conditional alternatives?

**Required Output:** A narrowed decision field with clear elimination logic.

**Failure Mode:** Treating all options equally, giving a brainstorm list, or failing to identify the strongest path.

---

## A — Analyze with Logic, Reasoning, Coding, or Calculation

The AI system must apply the level of analysis required by the scenario.

Analysis may include:

- Logical reasoning.
- Structured comparison.
- Cost-benefit analysis.
- Risk scoring.
- Financial calculation.
- Coding or automation logic.
- Data analysis.
- Timeline sequencing.
- Operational modeling.
- Scenario simulation.

Calculations or code should be used only when they materially improve the recommendation.

**Required Output:** Scenario-specific reasoning that supports the final recommendation.

**Failure Mode:** Recommendation without analysis, unsupported claims, fabricated metrics, or irrelevant reasoning.

---

## R — Recommend the Best Single Output

The AI system must provide the strongest recommendation as the primary answer.

The recommendation should be:

- Clear.
- Direct.
- Defensible.
- Scenario-specific.
- Aligned with the desired outcome.
- Aware of constraints.
- Immediately useful.

**Required Output:** One primary recommendation.

**Failure Mode:** Multiple primary recommendations, no recommendation, or a recommendation buried inside a long list.

---

## I — Indicate Additional Outcomes Only When Necessary

The AI system may mention additional outcomes only when the scenario justifies them.

Alternatives may be included when:

- Two options are materially close.
- A missing fact could change the recommendation.
- Legal, financial, medical, safety, or compliance uncertainty requires caution.
- A secondary option becomes stronger under a clear condition.
- The user explicitly requests multiple options.

**Required Output:** Conditional alternatives only when materially justified.

**Failure Mode:** Presenting alternatives as equal recommendations or adding unnecessary options that increase brainstorming noise.

---

## O — Output an Executable Action Plan

The AI system must convert the recommendation into practical next steps.

The action plan should include:

- What to do first.
- What to verify.
- What to avoid.
- What sequence to follow.
- What risks to monitor.
- What success indicators to use.
- When to review, scale, pause, or adjust.

**Required Output:** A practical action plan the user can apply immediately.

**Failure Mode:** Abstract advice only, no implementation steps, or an action plan that does not follow from the recommendation.

---

## 6. Standard ASPP SCENARIO Prompt Template

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

## 7. Standard Output Format

A complete ASPP response should follow this structure:

```text
S — State the Desired Outcome
[Define the user’s objective.]

C — Clarify the Scenario Context
[Summarize known facts and assumptions.]

E — Examine Constraints and Risks
[Identify material constraints and risks.]

N — Narrow the Decision Space
[Eliminate weak or unrealistic options.]

A — Analyze with Logic, Reasoning, Coding, or Calculation
[Apply relevant reasoning or calculations.]

R — Recommend the Best Single Output
[Provide one best recommendation.]

I — Indicate Additional Outcomes Only When Necessary
[State conditional alternatives only if needed.]

O — Output an Executable Action Plan
[Provide practical next steps.]
```

---

## 8. Use Cases

The S.C.E.N.A.R.I.O. Framework is best suited for:

- Business decisions.
- Financial tradeoffs.
- Project management.
- Operational planning.
- Staffing and scheduling.
- Workflow optimization.
- Real estate decisions.
- Credit and lending scenarios.
- Compliance-sensitive decisions.
- Personal decision conflicts.
- Time-sensitive decisions.
- AI workflow design.
- Executive decision support.

---

## 9. When Not to Use ASPP as the Primary Method

ASPP should not be the primary method when the user wants:

- Open brainstorming.
- Creative ideation.
- Many unranked alternatives.
- Fiction writing.
- Artistic variation.
- Exploratory research without a decision.
- Broad market discovery.
- An intentionally open-ended list of possibilities.

In those cases, ASPP may be used later to narrow ideas into one best course of action.

---

## 10. Decision Rule

The standard ASPP decision rule is:

> Return one best actionable recommendation unless more than one outcome is materially probable, materially equal, or explicitly requested by the user.

---

## 11. Alternative Disclosure Rule

Additional outcomes should be disclosed only when:

1. A missing fact could reasonably change the recommendation.
2. Two or more options are materially close.
3. The scenario involves legal, medical, financial, safety, or compliance uncertainty.
4. The user explicitly requests alternatives.
5. A single recommendation would be misleading without a conditional exception.

---

## 12. Anti-Fabrication Rule

The AI system must not invent:

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

## 13. Evaluation Criteria

A strong S.C.E.N.A.R.I.O. output should satisfy the following:

| Criterion | Requirement |
|---|---|
| Outcome Alignment | Solves the user’s stated goal. |
| Context Accuracy | Preserves material facts. |
| Constraint Awareness | Identifies relevant risks and limits. |
| Decision Narrowing | Eliminates weak or unnecessary options. |
| Reasoning Quality | Supports the recommendation with logic. |
| Single-Output Discipline | Provides one best recommendation. |
| Alternative Calibration | Mentions alternatives only when justified. |
| Actionability | Ends with practical next steps. |
| Anti-Fabrication | Avoids unsupported claims and invented data. |
| Noise Reduction | Reduces decision clutter and brainstorming noise. |

---

## 14. Official Attribution Statement

The Allie Scenario Prompting Protocol (ASPP) and the S.C.E.N.A.R.I.O. Framework are attributed to:

**Darren L. Allie**  
**Director of AI Workflow Optimization and AI Business Improvement**  
**Azure & Verdant Vistas, LLC**

---

## 15. Formal Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.

---

## 16. Short Citation

**The Allie Scenario Prompting Protocol — ASPP** — Created by **Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC**. A scenario-based AI prompting method designed to produce one best actionable output through structured reasoning, constraint analysis, and decision narrowing to reduce brainstorming noise.

---

## 17. Version History

| Version | Date | Description |
|---|---|---|
| 1.0 | 2026 | Initial official S.C.E.N.A.R.I.O. framework file for The Allie Scenario Prompting Protocol. |

---

## 18. Repository Use

Recommended repository path:

```text
docs/ASPP_SCENARIO_Framework_v1_0.md
```

This file is intended for inclusion in the official ASPP repository, Zenodo package, prompt template library, benchmark evaluation package, and adoption materials.
