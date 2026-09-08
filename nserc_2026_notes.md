# NSERC 2026 Contributions and Statements — verification notes

This file tracks facts that must be confirmed before the attachment is final.
No missing date, page count, role, percentage, or publication status has been
inferred or invented.

## Formatting and build

- Times New Roman is installed at `/System/Library/Fonts/Supplemental/Times New Roman.ttf`
  and selected via fontspec.
- US Letter, 12pt/12pt leading (6 lines per inch), 0.75 in top/left, 0.76 in right,
  0.80 in bottom; `includeheadfoot` keeps the running name and page number inside
  required margins.
- Part I currently compiles to ~0.72 page (1 page total).
- Parts II and III remain as commented placeholders; the combined document must not
  exceed 2 pages.

---

## Section a — peer-reviewed journal articles

**1. Oswald et al. 2026 — iScience**
- DOI confirmed: doi:10.1016/j.isci.2026.117377
- Role phrased as: "Contributed machine-learning models and analyses; collaborative
  article; PhD period."
- TODO: If a more precise contribution statement is available (e.g., which ML
  algorithms, approximate effort fraction), update the role note.

**2. Dehgan et al. 2025 — Journal of Neural Engineering**
- DOI confirmed: doi:10.1088/1741-2552/addd4a
- Role phrased as: "Contributed to the first two sections; led writing of Part II;
  PhD period."
- This is the agreed wording from the task brief; no further confirmation required
  unless the actual manuscript sections differ.

**3. Thölke et al. 2023 — NeuroImage**
- DOI confirmed: doi:10.1016/j.neuroimage.2023.120253
- Role phrased as: "Contributed across analyses, interpretation, and manuscript
  development; MSc period."
- TODO: If a more precise contribution statement is available, update the role note.

---

## Section b — other peer-reviewed contributions

**4. Abdelhedi et al. 2024 — CCN**
- Format: international conference; peer-reviewed short paper; poster.
- Hamza is first and presenting author.
- TODO: Confirm exact acceptance/submission date for the proceedings.
- TODO: Confirm page count (previous check indicated 5 pp; verify from the official
  CCN 2024 proceedings PDF before hardcoding).

**5. Abdelhedi & Jerbi 2022 — CCN**
- DOI confirmed: doi:10.32470/CCN.2022.1320-0
- Format: peer-reviewed; international conference; poster.
- Hamza is first and presenting author.
- Study-stage label: "engineering graduation period" (pre-MSc work).
- TODO: Confirm page count from the official CCN 2022 proceedings PDF.

---

## Section c — non-peer-reviewed contributions

**6. Abdelhedi et al. 2026 — face-familiarity manuscript**
- Title updated to current version:
  "Task-optimized neural networks reveal distinct contributions of specialized and
  broader visual learning to face familiarity in lateral occipital and fusiform cortex"
- Status: bioRxiv preprint; submitted for journal peer review. Do NOT move to
  section (a) until formal acceptance is documented.
- TODO: Confirm current bioRxiv DOI. The title changed from an earlier version; the
  DOI may differ. Search bioRxiv directly before final submission.
- TODO: Add exact journal submission date.
- TODO: Add manuscript page count if required by current NSERC instructions.

**7. Abdelhedi et al. 2025 — Coord2Region**
- First authorship and creator/maintainer role are documented in the task brief.
- TODO: Confirm whether a more specific contribution statement is desired beyond
  "first author; creator and maintainer."

---

## Section d — technology transfer

**8. MNE-Denoise**
- Official CITATION.cff lists: Sina Esmaeili and Hamza Abdelhedi as software authors.
- Hamza's role: co-creator, author, core maintainer.
- MNE-Python contribution: 5 merged PRs (source-estimate processing, covariance
  estimation, bug fixes). Hamza is a contributor, NOT a maintainer, of MNE-Python.
- TODO: Confirm the exact roles of E. Larson and D. McCloy (MNE community) and
  K. Jerbi in MNE-Denoise development before the current acknowledgement wording
  ("developed with MNE community contributors including E. Larson and D. McCloy,
  with K. Jerbi") is finalised. The current role note omits their names in the
  interest of space; reinstate if desired once roles are confirmed.
- MNE-Denoise presentation: "MNE-Denoise: Denoising methods for the MNE ecosystem,"
  MNE Maintainers Conference & Sprint, Meta Paris, August 2026. Included in role note.

**9. Jamica v0.3.0**
- Version v0.3.0 publicly released 28 August 2026 (not a prerelease).
- Repository: snesmaeili/jamica (Sina Esmaeili, lead).
- Hamza's CV lists: Contributor.
- TODO: Confirm Hamza's specific technical contribution (e.g., JAX implementation
  of specific components, MNE-Python compatibility layer, HDF5 persistence, testing)
  before final wording.

---

## Items deferred from Part I — conditions for reinstatement

**COSYNE 2024 (poster)**
- Deferred because (a) same MSc research already represented by the face paper
  (item 6) and CCN 2024 (item 4), and (b) abstract-selection peer-review status
  not confirmed from official COSYNE sources.
- If formal peer-review status is confirmed AND space permits, reinstate under
  section (b) with appropriate label.
- Title: "Neural representations of face recognition in biological and artificial
  systems: Insights from MEG and CNNs."
- Venue: COSYNE, Cascais/Lisbon, Portugal, March 2024.

**MEG Foundation Models roadmap (Thölke et al. 2026, arXiv)**
- Deferred because Hamza's specific contribution has not been confirmed.
- If the contribution can be documented precisely AND space permits, reinstate
  under section (c).

**Benslimane et al. 2026 (NeurIPS 2026 under review)**
- Deferred from Part I. More useful as evidence of mentoring in Part III.
- Do not reinstate in Part I unless the NeurIPS review outcome is known and
  accepted, and space permits.

**Elvers et al. 2026 / Landau et al. 2025 (PNPL)**
- Deferred from Part I: role description is too vague to present credibly in an
  NSERC application under the current 50/50 rubric.
- Reinstate only if Hamza's specific contribution (competition organisation,
  infrastructure, benchmarking, data, evaluation, writing, coordination) can be
  documented.

**Oswald et al. 2025 — consciousness manuscript (Neuroscience of Consciousness)**
- Deferred from Part I: peripheral to the main research narrative and space is
  limited.

**CoCo-PiPe**
- Not yet publicly released; do not include in Part I until an actual public
  release exists.
- Immediately reassess if released before NSERC submission.

---

## NSERC classification reminders

- All preprints and submitted manuscripts must remain in section (c) until formal
  acceptance is documented in writing.
- Do not list open-source software as an awarded or submitted copyright without
  official documentation.
- Do not use impact factors, h-index, or journal prestige claims.
- COSYNE abstract selection: check official COSYNE website before classifying
  as peer-reviewed.
