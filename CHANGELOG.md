# Changelog

All notable changes to this repository are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project uses [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

_No unreleased changes._

## [2.2.0] - 2026-07-29

Minor release. Adds **Series II ("recovery systems")** alongside the original Series I, plus a project-wide AI methodology disclosure and DOI/metadata integrity corrections.

> **DOI status:** The v2.2.0 **version DOI is pending.** A GitHub release and a Zenodo "sync" message do not by themselves mint a Zenodo deposit; the live Zenodo record showed v2.0.2 ([10.5281/zenodo.21630213](https://doi.org/10.5281/zenodo.21630213)) as the latest confirmed version at the time of writing. The concept DOI [10.5281/zenodo.21618895](https://doi.org/10.5281/zenodo.21618895) always resolves to the latest confirmed version. The v2.2.0 version DOI will be recorded here only after it is visible on the live Zenodo record.

> **Verification status:** Series II is complete and publicly inspectable and was authored to the series' evidence discipline (ESTABLISHED / PLAUSIBLE / SPECULATIVE tagging, mandatory Falsification Check, full `sources.md` bibliographies). It has **not yet received a deliberate human verification pass**. Specific historical claims — exact dates, characterizations of "complete" or "permanent" loss, manufacturing-recovery claims, and technical comparisons — should be checked directly against the cited sources before Series II is described publicly as equal in rigor to Series I.

### Added
- **Series II — `/recovery-systems/`**: eight recovery cases (01 Rosetta Stone, 02 Linear B, 03 Roman Concrete, 04 Ancient Music Reconstruction, 05 Wôpanâak Language Reclamation, 06 Apollo F-1 Engine, 07 BBC Domesday Project, 08 Greek Fire) plus a Series II synthesis, each with `sources.md` bibliography and PDF/DOCX renderings.
- **`METHODOLOGY.md`**: project-wide research-methodology and AI-use disclosure (MD/PDF/DOCX), linked from `README.md`.

### Changed
- **`.zenodo.json` / `CITATION.cff` version** bumped to `2.2.0`; `CITATION.cff` primary DOI/URL point at the concept DOI until the v2.2.0 version DOI is minted.

### Fixed
- **DOI integrity**: removed an erroneously introduced DOI (`10.5281/zenodo.14664076`) that had appeared only in draft release notes / working docs and never in repository files; reaffirmed concept DOI `10.5281/zenodo.21618895` and most-recent-confirmed version DOI `10.5281/zenodo.21630213` (v2.0.2).
- **Version numbering**: Series II is released as **v2.2.0**; the earlier `v2.1.0` tag remains the PDF/metadata release it originally was (see below) and was not moved.

## [2.1.0] - 2026-07-27

Minor release. Completes the per-document PDF set and corrects repository/status metadata across the series.

### Added
- **PDF renderings for case studies 02–08**: `Aboriginal_Oral_Traditions_CIF.pdf`, `Antikythera_Mechanism_CIF.pdf`, `Late_Bronze_Age_Collapse_CIF.pdf`, `Japanese_Tsunami_Stones_CIF.pdf`, `Polynesian_Navigation_CIF.pdf`, `Gobekli_Tepe_CIF.pdf`, and `Undeciphered_Scripts_CIF.pdf`. Case 01 already carried its own PDF.
- **Capstone synthesis PDF**: `synthesis/CIF_Ancient_Systems_Synthesis.pdf`, rendered from `synthesis/README.md`.

### Changed
- **README status table**: cases 02–08 now show as **Published** (included in the series Zenodo deposit at v2.0.2+), each linking the series concept DOI, replacing the previous *Written* status. Footnote updated to explain the series-deposit vs. foundational-DOI distinction.
- **`.zenodo.json` version** bumped to `2.1.0`.
- **`CITATION.cff` version** bumped to `2.1.0`.

### Fixed
- **`.zenodo.json` source URL**: corrected the `notes` field from the old repository name `cif-giza-transmission` to the current `cif-ancient-systems-test-series`.

## [2.0.2] - 2026-07-27

Patch release. Published to Zenodo — version DOI [10.5281/zenodo.21630213](https://doi.org/10.5281/zenodo.21630213), concept DOI [10.5281/zenodo.21618895](https://doi.org/10.5281/zenodo.21618895) — and tagged [`v2.0.2`](https://github.com/derekhone/cif-giza-transmission/releases/tag/v2.0.2) on GitHub.

### Changed
- **Cleaned the Zenodo source archive**: removed a non-content platform system file that was previously visible in the published archive listing. No changes to any intellectual content, case studies, framework, or metadata versus 2.0.1.

## [2.0.1] - 2026-07-27

Patch release for academic rigor and metadata corrections in SUMMARY document. Published to Zenodo — version DOI [10.5281/zenodo.21629986](https://doi.org/10.5281/zenodo.21629986), concept DOI [10.5281/zenodo.21618895](https://doi.org/10.5281/zenodo.21618895) — and tagged [`v2.0.1`](https://github.com/derekhone/cif-giza-transmission/releases/tag/v2.0.1) on GitHub.

### Fixed
- **Evidence discipline in SUMMARY.md**: Changed "proof that" / "proves that" / "CIF stands" to academically safer "demonstrates that" / "illustrates that" / "supports CIF's central claim" (7 instances corrected)
- **GitHub repository URL in SUMMARY.md**: Corrected from `derekjhone` to `derekhone` (canonical account path)
- Academic rigor upgrade: historical case studies support/refine/illustrate CIF but cannot formally prove the whole framework

## [2.0.0] - 2026-07-27

First complete release of the full **CIF Ancient Systems Test Series**: all eight case studies written, graded, and reconciled, with the capstone synthesis in place. Published to Zenodo — version DOI [10.5281/zenodo.21628073](https://doi.org/10.5281/zenodo.21628073), concept DOI [10.5281/zenodo.21618895](https://doi.org/10.5281/zenodo.21618895) — and tagged [`v2.0.0`](https://github.com/derekhone/cif-giza-transmission/releases/tag/v2.0.0) on GitHub.

### Added
- **All eight case studies complete**, each with its own `sources.md`:
  - #01 **The Giza Transmission Hypothesis** (speculative / thought-experiment; poses the series question)
  - #02 **Aboriginal Oral Traditions** (verdict: *Refines CIF*)
  - #03 **The Antikythera Mechanism** (verdict: *Supported*)
  - #04 **The Late Bronze Age Collapse** (verdict: *Supported*)
  - #05 **Japanese Tsunami Stones** (verdict: *Supported*)
  - #06 **Polynesian Wayfinding** (verdict: *Supported — with a critical addition*)
  - #07 **Göbekli Tepe** (verdict: *Supported*)
  - #08 **Undeciphered Scripts** (verdict: *Supported*)
- `synthesis/README.md` — the **capstone synthesis**, drawing the cross-case pattern together (written last, so the pattern is read out of the evidence).
- `GRADING.md` — a cross-disciplinary **polymath grading review** of every case study, the framework, and the README against the Remnant Fieldworks highest-honesty quality bar.
- `case-studies/01-giza-transmission/sources.md` — mainstream Egyptological anchors and evidence-handling notes for the foundational case.
- The **Five Inheritance Layers** (physical form / data / method / intent / semantic continuity), now formalized in `framework/CIF_Framework.md` as a named diagnostic lens alongside the Five Engineering Pillars.

### Changed
- **Framework reconciliation:** `framework/CIF_Framework.md` now documents *two* complementary five-part lenses — the Five Engineering Pillars (prospective governance) and the Five Inheritance Layers (retrospective fidelity) — and the canonical case-study structure states which lens each phase applies. This resolves a vocabulary drift in which "Pillar Analysis" had silently meant two different schemes between Phase 1 and Phase 2.
- **README corrected:** the six-axiom summary now matches the canonical framework axioms; the pillar/layer lists are relabeled and disambiguated; the case-study index reflects actual completion; the broken DOI badge was replaced with a working badge.
- `assets/` — Giza concept imagery retained.

## [1.1.0] - 2026-07-27

### Added
- Restructured the repository from a single-paper repo into the **CIF Ancient Systems Test Series**.
- `framework/CIF_Framework.md` — full description of the Coherent Inheritance Framework: status and provenance (including the UIP → CIF renaming), central proposition, six axioms, the Five Engineering Pillars, the canonical case-study structure, and the rationale for testing against ancient systems.
- Case study #02 — **Aboriginal Oral Traditions**, with sources.
- Case study #05 — **Japanese Tsunami Stones**, with sources.
- `assets/` — Giza concept imagery.
- A shared **Final CIF Verdict** taxonomy (`SUPPORTED` / `PARTIALLY SUPPORTED` / `INCONCLUSIVE` / `CHALLENGED` / `FALSIFIED AS FRAMED`) and a mandatory **Falsification Check** in every case study.

### Changed
- Moved the Giza publication into `case-studies/01-giza-transmission/` (git history preserved).
- Rewrote the top-level `README.md` as a series overview with a case-study index and evidence-discipline statement.
- Updated `CITATION.cff` to reflect the series title.

## [1.0.0] - 2026-07-27

### Added
- Initial publication of **The Giza Transmission Hypothesis: A Coherent Inheritance Framework Thought Experiment in Deep-Time Information Preservation**.
- Published to Zenodo with DOI [10.5281/zenodo.21618896](https://doi.org/10.5281/zenodo.21618896).
- `CITATION.cff` and CC BY 4.0 `LICENSE`.
