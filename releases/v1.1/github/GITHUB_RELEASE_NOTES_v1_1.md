# ASPP v1.1 GitHub Release Notes

**File Name:** `GITHUB_RELEASE_NOTES_v1_1.md`
**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Version:** 1.1
**Release Tag:** v1.1
**Release Title:** ASPP v1.1 — Official Benchmark Evaluation Suite
**Creator:** Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**License:** CC BY 4.0

---

## Release Summary

ASPP v1.1 is the active transitional release of The Allie Scenario Prompting Protocol. This release extends the foundational v1.0 preprint and specification with the ASPP Official Benchmark Evaluation Suite, introducing a formal benchmark specification, a structured test case, annotated response quality examples, machine-readable schema definitions, and a versioned repository organization.

---

## What Is New in v1.1

### ASPP Official Benchmark Evaluation Suite

The benchmark evaluation suite provides a complete, reproducible framework for testing AI compliance with ASPP:

- **Benchmark Specification** (`releases/v1.1/benchmarks/ASPP_Benchmark_Specification_v1_1.md`) — defines benchmark scope, test case structure, and scoring standards
- **Evaluation Rubric v1.1** (`releases/v1.1/benchmarks/ASPP_Evaluation_Rubric_v1_1.md`) — updated 100-point rubric with stage-level scoring guidance
- **ASPP-SCENARIO-001 Test Case** (`releases/v1.1/benchmarks/ASPP_SCENARIO_001_Test_Case_v1_1.md`) — structured test input and expected response criteria

### Response Quality Examples

Three annotated examples are now included to calibrate scoring:

- `releases/v1.1/examples/passing_response_example.md` — score 91/100, Exceptional ASPP Compliance
- `releases/v1.1/examples/borderline_response_example.md` — score 67/100, Weak ASPP Compliance
- `releases/v1.1/examples/failing_response_example.md` — score 34/100, Non-Compliant

### Machine-Readable Schema Definitions

Benchmark records can now be structured using:

- `releases/v1.1/schemas/ASPP_Benchmark_v1_1.json`
- `releases/v1.1/schemas/ASPP_Benchmark_v1_1.yaml`

### Versioned Repository Organization

The repository now uses a `releases/` directory tree for clean version separation:

```text
releases/
  v1.0/
    manifest.md
    notes.md
  v1.1/
    manifest.md
    notes.md
    README_INSERT_v1_1.md
    FINAL_UPLOAD_CHECKLIST.md
    benchmarks/
    docs/
    examples/
    github/
    schemas/
    zenodo/
  v1.2/
    manifest.md
```

### Updated Public Front Page and Citation

- `README.md` has been updated to reference v1.1 as the active release
- `CITATION.cff` has been updated to version `1.1`

---

## What Carries Forward from v1.0

All v1.0 assets are preserved unchanged at the repository root. The foundational ASPP methodology, S.C.E.N.A.R.I.O. framework, scoring scale, anti-fabrication rule, and standard prompt template are unchanged.

---

## Files in This Release

```text
releases/v1.1/manifest.md
releases/v1.1/notes.md
releases/v1.1/README_INSERT_v1_1.md
releases/v1.1/FINAL_UPLOAD_CHECKLIST.md
releases/v1.1/benchmarks/ASPP_Benchmark_Specification_v1_1.md
releases/v1.1/benchmarks/ASPP_Evaluation_Rubric_v1_1.md
releases/v1.1/benchmarks/ASPP_SCENARIO_001_Test_Case_v1_1.md
releases/v1.1/docs/ASPP_Official_Benchmark_Evaluation_Suite_v1_1.md
releases/v1.1/examples/passing_response_example.md
releases/v1.1/examples/borderline_response_example.md
releases/v1.1/examples/failing_response_example.md
releases/v1.1/github/GITHUB_RELEASE_NOTES_v1_1.md
releases/v1.1/schemas/ASPP_Benchmark_v1_1.json
releases/v1.1/schemas/ASPP_Benchmark_v1_1.yaml
releases/v1.1/zenodo/ZENODO_METADATA_v1_1.md
releases/v1.0/manifest.md
releases/v1.0/notes.md
releases/v1.2/manifest.md
README.md (updated)
CITATION.cff (updated)
```

---

## Citation

Allie, Darren L. **The Allie Scenario Prompting Protocol: A Scenario-Constrained, Outcome-First Method for Prompt Engineering.** Azure & Verdant Vistas, LLC, 2026. DOI: **10.5281/zenodo.20596641**.
