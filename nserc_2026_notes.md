# NSERC 2026 Contributions and Statements — verification notes

This file tracks facts that must be confirmed before the attachment is final.
No missing date, page count, role, or publication status has been inferred or invented.

## Formatting and build

- Times New Roman, installed at `/System/Library/Fonts/Supplemental/Times New Roman.ttf`;
  selected via fontspec.
- Geometry: US Letter; `top=bottom=left=right=0.75in`; header/footer live in margin areas
  (no `includeheadfoot`); body text begins at exactly 0.75in from paper edge.
- `headheight=14.5pt`, `headsep=3pt`, `footskip=18pt`.
- Leading: 12pt/12pt = 6 lines per inch (NSERC maximum).
- Part I currently compiles to ~0.82 page, 12 entries, 1 page total.
- Parts II and III remain as commented placeholders; combined document must not exceed
  2 pages.

---

## Resolved identifiers

- Oswald 2026: doi:10.1016/j.isci.2026.117377 ✓
- Dehgan 2025: doi:10.1088/1741-2552/addd4a ✓
- Thölke 2023: doi:10.1016/j.neuroimage.2023.120253 ✓
- CCN 2022: doi:10.32470/CCN.2022.1320-0 ✓
- MEG Foundation Models roadmap: arXiv:2609.04461 ✓
- Coord2Region: arXiv:2512.18165 ✓

---

## Section a — peer-reviewed journal articles

**1. Oswald et al. 2026 — iScience**
- TODO: If a more precise contribution statement is available (specific ML methods,
  approximate effort), update the role note from "ML models and analyses."

**2. Dehgan et al. 2025 — Journal of Neural Engineering**
- Role wording ("contributed to Sections I–II; led writing of Part II") confirmed
  by the task brief. No further changes expected unless the manuscript layout differs.

**3. Thölke et al. 2023 — NeuroImage**
- TODO: If a more precise contribution statement is available beyond "analyses,
  interpretation, and manuscript," update the role note.

---

## Section b — other peer-reviewed contributions

**4. CCN 2024**
- Proceedings URL confirmed in CV source (2024.ccneuro.org).
- TODO: Confirm exact acceptance/submission date.
- TODO: Confirm page count. Previous indication: 5 pp. Verify from the official PDF
  at 2024.ccneuro.org before hardcoding.

**5. COSYNE 2024**
- TODO: Confirm peer-review classification from the official COSYNE 2024 programme.
  If abstract selection is confirmed as peer-reviewed, the entry is correctly placed
  in section (b). If not, move to section (c).

**6. CCN 2022**
- DOI confirmed: doi:10.32470/CCN.2022.1320-0.
- Study stage: "engineering graduation period" (pre-MSc work).
- TODO: Confirm page count from the official CCN 2022 proceedings PDF.

**7. PNPL retrospective — Elvers et al. 2026**
- This is the retrospective/lessons-learned paper (distinct from the 2025 competition
  paper, Landau et al. 2025, arXiv:2506.10165, and the 2026 competition paper,
  Mantegna et al. 2026, arXiv:2609.03231).
- TODO: Confirm Hamza's specific contribution (competition organisation, infrastructure,
  benchmarking, data preparation, evaluation, writing, or coordination).
- TODO: Confirm the final publication venue, volume/page, and whether the PMLR
  classification as peer-reviewed is accurate for this specific paper.
- TODO: Confirm the final author list and Hamza's position in it.
- This entry has the lowest priority in section (b). Remove if space becomes tight
  or if the role cannot be documented precisely.

---

## Section c — non-peer-reviewed contributions

**8. Face-familiarity manuscript — Abdelhedi et al. 2026**
- Title updated to the CURRENT version:
  "Task-optimized neural networks reveal distinct contributions of specialized and
  broader visual learning to face familiarity in lateral occipital and fusiform cortex"
- The CV source still shows the OLD title. The old bioRxiv entry's DOI may differ
  from the updated-title version.
- TODO: Confirm the current bioRxiv DOI for the updated title (search bioRxiv
  directly by title before final submission).
- TODO: Add exact journal submission date.
- TODO: Add manuscript page count if required by current NSERC electronic
  submission instructions.
- Status: bioRxiv preprint; submitted for journal peer review. Do NOT move to
  section (a) until formal acceptance is documented.

**9. MEG Foundation Models roadmap — Thölke, Abdelhedi, et al. 2026**
- arXiv:2609.04461 confirmed (in CV source and task brief). Submitted 3 Sep 2026.
- TODO: Confirm Hamza's specific contribution beyond "second author" before final
  submission. Update role note if a more precise description is available.

**10. Coord2Region — Abdelhedi et al. 2025**
- arXiv:2512.18165 confirmed (in CV source).
- First authorship and creator/maintainer role confirmed by task brief.

---

## Section d — technology transfer

**11. MNE-Denoise**
- Authorship and order declared by applicant for this NSERC draft:
    1. Abdelhedi, H. (shared first)
    2. Esmaeili, S. (shared first)
    3. Larson, E.
    4. McCloy, D.
    5. Jerbi, K.
- The CITATION.cff in the official repository previously listed only Esmaeili, S.
  and Abdelhedi, H. as software authors.
- TODO: Before final NSERC submission, verify or update the official MNE-Denoise
  citation/authorship metadata so that the authorship order and list asserted here
  matches the contribution's official or forthcoming citation. NSERC asks applicants
  to report authorship as it appears (or will appear) in the original contribution.
- Hamza is NOT an MNE-Python maintainer. He is a contributor with 5 merged PRs.
- MNE conference presentation: "MNE-Denoise: Denoising methods for the MNE ecosystem,"
  MNE-Python Maintainers Conference & Sprint, Meta Paris, August 2026. Confirmed in
  task brief.

**12. Jamica v0.3.0**
- Version v0.3.0 publicly released 28 August 2026 (not a prerelease). Confirmed.
- Repository: snesmaeili/jamica (Sina Esmaeili, lead).
- TODO: Confirm Hamza's specific technical contribution (e.g., JAX implementation
  of specific AMICA components, MNE-Python compatibility layer, HDF5 persistence,
  or testing/CI) before final wording. Currently listed as "contributor."

---

## Items deferred from Part I — conditions for reinstatement

**CoCo-PiPe**
- Not yet publicly released. Do not include in Part I until a public release exists.
- REASSESS IMMEDIATELY if CoCo-PiPe is released before NSERC submission. If released,
  it could replace a weaker contribution rather than simply extending Part I length.

**Benslimane et al. 2026 (NeurIPS 2026 under review)**
- More useful as evidence of mentoring/collaboration in Part III.
- Reinstate in Part I only if NeurIPS outcome is known and accepted, and space permits.

**Oswald et al. 2025 — consciousness manuscript**
- Too peripheral to the main research narrative; deferred to keep Part I tight.

---

## NSERC classification reminders

- All preprints and submitted manuscripts must remain in section (c) until formal
  acceptance is documented.
- COSYNE abstract peer-review status: verify before final classification in (b).
- PNPL retrospective (Elvers et al.): confirm PMLR/NeurIPS peer-review classification.
- Do not list open-source software as an awarded copyright without official documentation.
- Do not use impact factors, h-index, or journal prestige claims.
- The ‡ (shared first authorship) for MNE-Denoise must be consistent with the official
  citation metadata at the time of final submission.
