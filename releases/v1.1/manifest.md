# ASPP v1.1 Versioned Package Index

**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Version:** 1.1
**Release Type:** Active Transitional Release
**Creator:** Darren L. Allie
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement
**Organization:** Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
**Status:** Active — current public release

---

## Purpose

This manifest is the versioned package index for ASPP v1.1. It documents all assets that constitute the v1.1 release, explains how this release relates to the ASPP versioning lifecycle, and provides the canonical upload and deposition sequence for GitHub and Zenodo.

Version 1.1 is the active transitional release between the initial v1.0 publication and the forthcoming v1.2. It extends v1.0 with a formal benchmark specification, an expanded test case, structured response quality examples, machine-readable schema definitions, and a complete Zenodo metadata record.

---

## Role in the ASPP Release Lifecycle

| Version | Status | Description |
|---|---|---|
| 1.0 | Archived | Initial release. Foundational preprint, specification, and evaluation rubric. See `releases/v1.0/manifest.md`. |
| **1.1** | **Active** | **Transitional release. Expanded benchmark suite, test case, examples, schemas, and Zenodo metadata.** |
| 1.2 | Planned | Next release. See `releases/v1.2/manifest.md` for the scaffold. |

---

## Package Contents

All paths below are relative to the repository root.

### Root-Level Files (Updated for v1.1)

| File | Action | Description |
|---|---|---|
| `README.md` | Updated | Public front page referencing v1.1 as the active release |
| `CITATION.cff` | Updated | Machine-readable citation reflecting v1.1 version and DOI |

### v1.1 Release Files (Under `releases/v1.1/`)

| File | Description |
|---|---|
| `releases/v1.1/manifest.md` | This document — the v1.1 versioned package index |
| `releases/v1.1/notes.md` | v1.1 release notes |
| `releases/v1.1/README_INSERT_v1_1.md` | v1.1 content block for insertion into the public README |
| `releases/v1.1/FINAL_UPLOAD_CHECKLIST.md` | v1.1 upload and publication checklist |

### Benchmarks (`releases/v1.1/benchmarks/`)

| File | Description |
|---|---|
| `releases/v1.1/benchmarks/ASPP_Benchmark_Specification_v1_1.md` | Formal benchmark specification for ASPP v1.1 |
| `releases/v1.1/benchmarks/ASPP_Evaluation_Rubric_v1_1.md` | Updated 100-point evaluation rubric for v1.1 |
| `releases/v1.1/benchmarks/ASPP_SCENARIO_001_Test_Case_v1_1.md` | Formal test case: ASPP-SCENARIO-001 |

### Evaluation Suite Document (`releases/v1.1/docs/`)

| File | Description |
|---|---|
| `releases/v1.1/docs/ASPP_Official_Benchmark_Evaluation_Suite_v1_1.md` | Official benchmark evaluation suite reference document |

### Response Quality Examples (`releases/v1.1/examples/`)

| File | Description |
|---|---|
| `releases/v1.1/examples/passing_response_example.md` | Example of a passing (80+) ASPP response |
| `releases/v1.1/examples/failing_response_example.md` | Example of a failing (below 60) ASPP response |
| `releases/v1.1/examples/borderline_response_example.md` | Example of a borderline (60–79) ASPP response |

### Release Notes (`releases/v1.1/github/`)

| File | Description |
|---|---|
| `releases/v1.1/github/GITHUB_RELEASE_NOTES_v1_1.md` | GitHub release notes for the v1.1 tag |

### Schema Definitions (`releases/v1.1/schemas/`)

| File | Description |
|---|---|
| `releases/v1.1/schemas/ASPP_Benchmark_v1_1.json` | Machine-readable benchmark schema (JSON format) |
| `releases/v1.1/schemas/ASPP_Benchmark_v1_1.yaml` | Machine-readable benchmark schema (YAML format) |

### Zenodo Metadata (`releases/v1.1/zenodo/`)

| File | Description |
|---|---|
| `releases/v1.1/zenodo/ZENODO_METADATA_v1_1.md` | Structured Zenodo deposition metadata for v1.1 |

---

## Naming Conventions

All v1.1 files follow the pattern:

```
ASPP_<Component>_v1_1.<ext>
```

Examples:
- `ASPP_Benchmark_Specification_v1_1.md`
- `ASPP_Evaluation_Rubric_v1_1.md`
- `ASPP_Benchmark_v1_1.json`
- `GITHUB_RELEASE_NOTES_v1_1.md`
- `ZENODO_METADATA_v1_1.md`

Future versions should follow the same pattern, substituting `v1_2`, `v2_0`, etc.

---

## Upload Sequence

Follow this order when uploading to GitHub and Zenodo:

1. Add `releases/v1.1/docs/ASPP_Official_Benchmark_Evaluation_Suite_v1_1.md`
2. Add `releases/v1.1/benchmarks/` files (specification, rubric, test case)
3. Add `releases/v1.1/examples/` files (passing, failing, borderline)
4. Add `releases/v1.1/github/GITHUB_RELEASE_NOTES_v1_1.md`
5. Add `releases/v1.1/schemas/` files (JSON and YAML)
6. Add `releases/v1.1/zenodo/ZENODO_METADATA_v1_1.md`
7. Update `README.md` using content from `releases/v1.1/README_INSERT_v1_1.md`
8. Update `CITATION.cff` after Zenodo DOI is confirmed for v1.1
9. Tag release `v1.1` in GitHub

---

## Repo Alignment Rules

- `README.md` at the repository root is always the public front page for the latest active version.
- `CITATION.cff` at the repository root always reflects the active version's DOI and metadata.
- Each version's assets live under `releases/v<major>.<minor>/` to ensure clean separation.
- Release notes and Zenodo metadata are version-specific and never overwrite prior version records.
- v1.0 assets are preserved at the repository root and in `releases/v1.0/` for historical traceability.
- Future versions (v1.2, v2.0, etc.) must follow the same directory and naming conventions.

---

## Pre-Publication Verification Checklist

Before publishing the v1.1 release:

- [ ] All files listed in this manifest are present in the repository
- [ ] `README.md` references v1.1 as the active release
- [ ] `CITATION.cff` version field is `1.1` and DOI is the v1.1 Zenodo DOI
- [ ] GitHub release tag `v1.1` exists and points to the correct commit
- [ ] Zenodo record title includes "v1.1" and version field is `1.1`
- [ ] Schema files are valid JSON and YAML
- [ ] All example files include scores and performance level labels
- [ ] v1.0 assets are still present and unmodified
