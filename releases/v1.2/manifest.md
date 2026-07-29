# ASPP v1.2 Release Manifest — Scaffold

**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Version:** 1.2
**Release Type:** Planned
**Creator:** Darren L. Allie
**Creator Title:** Director of AI Workflow Optimization and AI Business Improvement
**Organization:** Azure & Verdant Vistas, LLC
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
**Status:** Scaffold — not yet released

---

## Purpose

This file is the v1.2 manifest scaffold. It establishes the directory structure and naming conventions for the ASPP v1.2 release so that onboarding is straightforward and consistent with the v1.1 pattern.

When v1.2 work begins, replace the placeholder sections below with actual content.

---

## Role in the ASPP Release Lifecycle

| Version | Status | Description |
|---|---|---|
| 1.0 | Archived | Initial release. See `releases/v1.0/manifest.md`. |
| 1.1 | Active | Transitional release. See `releases/v1.1/manifest.md`. |
| **1.2** | **Planned** | **Next release. This scaffold.** |

---

## Expected Directory Structure

When v1.2 is prepared, the following structure should be populated under `releases/v1.2/`:

```text
releases/v1.2/
├── manifest.md                              (this file, updated for final release)
├── notes.md                                 (v1.2 release notes)
├── README_INSERT_v1_2.md                    (v1.2 content block for README.md)
├── FINAL_UPLOAD_CHECKLIST.md                (v1.2 upload and publication checklist)
├── benchmarks/
│   ├── ASPP_Benchmark_Specification_v1_2.md
│   ├── ASPP_Evaluation_Rubric_v1_2.md
│   └── ASPP_SCENARIO_00X_Test_Case_v1_2.md  (new test case(s) for v1.2)
├── docs/
│   └── ASPP_Official_Benchmark_Evaluation_Suite_v1_2.md
├── examples/
│   ├── passing_response_example.md
│   ├── failing_response_example.md
│   └── borderline_response_example.md
├── github/
│   └── GITHUB_RELEASE_NOTES_v1_2.md
├── schemas/
│   ├── ASPP_Benchmark_v1_2.json
│   └── ASPP_Benchmark_v1_2.yaml
└── zenodo/
    └── ZENODO_METADATA_v1_2.md
```

---

## Naming Conventions

All v1.2 files must follow the pattern:

```
ASPP_<Component>_v1_2.<ext>
```

Examples:
- `ASPP_Benchmark_Specification_v1_2.md`
- `ASPP_Evaluation_Rubric_v1_2.md`
- `ASPP_Benchmark_v1_2.json`
- `GITHUB_RELEASE_NOTES_v1_2.md`
- `ZENODO_METADATA_v1_2.md`

---

## Repo Alignment Rules for v1.2

When v1.2 is finalized:

1. Populate all files in the `releases/v1.2/` directory following the v1.1 pattern.
2. Update `README.md` using the v1.2 README insert.
3. Update `CITATION.cff` to version `1.2` after the v1.2 Zenodo DOI is confirmed.
4. Change the v1.1 status in `releases/v1.1/manifest.md` from Active to Archived.
5. Tag the release as `v1.2` in GitHub.
6. Deposit the v1.2 package as a new version in the Zenodo record.
7. Preserve all v1.0 and v1.1 assets unchanged.

---

## Placeholder — v1.2 Scope

*This section should be filled in when v1.2 planning begins.*

Potential v1.2 additions:
- Additional benchmark test cases (ASPP-SCENARIO-002, ASPP-SCENARIO-003)
- Expanded evaluation rubric coverage for domain-specific scenarios
- Multi-model comparative evaluation results
- Updated schema definitions
- Extended response quality example library

---

## Version History

| Version | Date | Description |
|---|---|---|
| 1.2 | TBD | Planned next release. Scaffold only. |
| 1.1 | 2026 | Active transitional release. ASPP Official Benchmark Evaluation Suite. |
| 1.0 | 2026 | Initial release. |
