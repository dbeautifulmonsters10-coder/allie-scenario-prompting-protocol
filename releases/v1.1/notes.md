# ASPP v1.1 Release Notes

**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Version:** 1.1
**Release Date:** 2026
**Creator:** Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**License:** CC BY 4.0
**Status:** Active Transitional Release

---

## Summary

Version 1.1 is the active transitional release of The Allie Scenario Prompting Protocol (ASPP). It extends the foundational v1.0 release with a formal benchmark specification, a structured test case, response quality examples, machine-readable schema definitions, and a structured Zenodo metadata record. This release establishes the package conventions and directory organization that v1.2 and future versions will reuse.

---

## What Is New in v1.1

### Benchmark Specification
A formal benchmark specification document (`ASPP_Benchmark_Specification_v1_1.md`) has been added under `releases/v1.1/benchmarks/`. This document defines the benchmark scope, evaluation criteria, test case structure, and scoring standards for the ASPP Official Benchmark Evaluation Suite.

### Updated Evaluation Rubric
The evaluation rubric has been updated to v1.1 (`ASPP_Evaluation_Rubric_v1_1.md`) with clarified scoring guidance for each S.C.E.N.A.R.I.O. stage and expanded automatic failure conditions.

### Formal Test Case
A fully specified test case (`ASPP_SCENARIO_001_Test_Case_v1_1.md`) has been added for ASPP-SCENARIO-001: Structured Decision Optimization Evaluation. This test case provides the input scenario, desired outcome, constraints, and expected response criteria for benchmark use.

### Response Quality Examples
Three annotated response examples have been added under `releases/v1.1/examples/`:
- `passing_response_example.md` — Example response scoring 80 or above
- `failing_response_example.md` — Example response scoring below 60
- `borderline_response_example.md` — Example response scoring 60–79

### Machine-Readable Schema Definitions
Two schema files have been added under `releases/v1.1/schemas/`:
- `ASPP_Benchmark_v1_1.json` — JSON schema for ASPP benchmark records
- `ASPP_Benchmark_v1_1.yaml` — YAML schema for ASPP benchmark records

### Zenodo Metadata Record
A structured Zenodo deposition metadata file (`ZENODO_METADATA_v1_1.md`) has been added under `releases/v1.1/zenodo/`.

### GitHub Release Notes
Structured release notes (`GITHUB_RELEASE_NOTES_v1_1.md`) for the v1.1 GitHub release tag have been added under `releases/v1.1/github/`.

### Versioned Repository Structure
A versioned directory layout has been introduced under `releases/`:
- `releases/v1.0/` — v1.0 manifest and notes referencing preserved root-level v1.0 assets
- `releases/v1.1/` — Complete v1.1 package contents (this release)
- `releases/v1.2/` — v1.2 scaffold for the next release

---

## What Carries Forward from v1.0

All v1.0 assets are preserved unchanged at the repository root and in their original directories. The following v1.0 elements are extended but not replaced by v1.1:

- Core ASPP methodology and S.C.E.N.A.R.I.O. framework — unchanged
- 100-point scoring scale and performance level thresholds — unchanged
- Anti-fabrication rule — unchanged
- Standard ASPP prompt template — unchanged
- DOI 10.5281/zenodo.20596641 — active for v1.0; v1.1 Zenodo record will have its own version entry

---

## Successor

Version 1.2 is the planned next release. The `releases/v1.2/manifest.md` scaffold is provided to make v1.2 onboarding straightforward. Version 1.2 should follow the same directory and naming conventions established in v1.1.
