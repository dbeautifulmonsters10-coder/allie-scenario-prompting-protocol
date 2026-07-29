# ASPP v1.1 Final Upload Checklist

**Protocol:** The Allie Scenario Prompting Protocol (ASPP)
**Version:** 1.1
**Creator:** Darren L. Allie, Director of AI Workflow Optimization and AI Business Improvement, Azure & Verdant Vistas, LLC
**DOI:** 10.5281/zenodo.20596641
**License:** CC BY 4.0

---

## Purpose

This checklist verifies that all v1.1 package files are present, correctly named, and ready for GitHub publication and Zenodo deposition.

---

## File Presence Checklist

### Root-Level Files

- [ ] `README.md` — updated to reference v1.1 as the active release
- [ ] `CITATION.cff` — version field is `1.1` and DOI is the v1.1 Zenodo DOI

### v1.1 Release Core Files

- [ ] `releases/v1.1/manifest.md`
- [ ] `releases/v1.1/notes.md`
- [ ] `releases/v1.1/README_INSERT_v1_1.md`
- [ ] `releases/v1.1/FINAL_UPLOAD_CHECKLIST.md` (this file)

### Benchmarks

- [ ] `releases/v1.1/benchmarks/ASPP_Benchmark_Specification_v1_1.md`
- [ ] `releases/v1.1/benchmarks/ASPP_Evaluation_Rubric_v1_1.md`
- [ ] `releases/v1.1/benchmarks/ASPP_SCENARIO_001_Test_Case_v1_1.md`

### Evaluation Suite Document

- [ ] `releases/v1.1/docs/ASPP_Official_Benchmark_Evaluation_Suite_v1_1.md`

### Examples

- [ ] `releases/v1.1/examples/passing_response_example.md`
- [ ] `releases/v1.1/examples/failing_response_example.md`
- [ ] `releases/v1.1/examples/borderline_response_example.md`

### GitHub Release Notes

- [ ] `releases/v1.1/github/GITHUB_RELEASE_NOTES_v1_1.md`

### Schema Definitions

- [ ] `releases/v1.1/schemas/ASPP_Benchmark_v1_1.json`
- [ ] `releases/v1.1/schemas/ASPP_Benchmark_v1_1.yaml`

### Zenodo Metadata

- [ ] `releases/v1.1/zenodo/ZENODO_METADATA_v1_1.md`

---

## Content Verification Checklist

- [ ] `README.md` heading and version history table reference v1.1 as the active release
- [ ] `CITATION.cff` `version` field is `"1.1"`
- [ ] All v1.1 files use the naming pattern `ASPP_<Component>_v1_1.<ext>`
- [ ] Schema files (`ASPP_Benchmark_v1_1.json` and `.yaml`) are valid and parseable
- [ ] All example files include a score and performance level label
- [ ] `ZENODO_METADATA_v1_1.md` title includes "v1.1" and version field is `1.1`
- [ ] `GITHUB_RELEASE_NOTES_v1_1.md` references the correct commit or tag
- [ ] v1.0 assets remain present and unmodified at the repository root

---

## GitHub Publication Steps

1. Commit all v1.1 files to the repository default branch
2. Verify all files in this checklist are present
3. Create GitHub release tag `v1.1`
4. Set the release title to: `ASPP v1.1 — Official Benchmark Evaluation Suite`
5. Paste the contents of `releases/v1.1/github/GITHUB_RELEASE_NOTES_v1_1.md` as the release body
6. Publish the release

---

## Zenodo Deposition Steps

1. Sign in to Zenodo
2. Select New Upload or new version under the existing ASPP Zenodo record
3. Upload files listed in the Zenodo Metadata section of `releases/v1.1/zenodo/ZENODO_METADATA_v1_1.md`
4. Set the version field to `1.1`
5. Set the title to: `The Allie Scenario Prompting Protocol: Official Benchmark Evaluation Suite v1.1`
6. Confirm DOI assignment
7. Preview the record
8. Publish the record
9. Update `CITATION.cff` with the confirmed v1.1 DOI

---

## Post-Publication Steps

- [ ] Confirm GitHub release tag `v1.1` is visible and accessible
- [ ] Confirm Zenodo record for v1.1 is published and DOI resolves
- [ ] Update `CITATION.cff` with the confirmed v1.1 Zenodo DOI
- [ ] Commit the updated `CITATION.cff` to the repository
- [ ] Announce the v1.1 release
