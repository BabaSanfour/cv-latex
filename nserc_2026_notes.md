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
- Part I now contains 13 entries. Re-check compiled length after this revision before drafting
  Parts II and III; combined document must not exceed 2 pages.

---

## Resolved identifiers

- Oswald 2026: doi:10.1016/j.isci.2026.117377 ✓
- Dehgan 2025: doi:10.1088/1741-2552/addd4a ✓
- Thölke 2023: doi:10.1016/j.neuroimage.2023.120253 ✓
- CCN 2022: doi:10.32470/CCN.2022.1320-0 ✓
- MEG Foundation Models roadmap: arXiv:2609.04461 ✓
- Coord2Region: arXiv:2512.18165 ✓
- Oswald consciousness manuscript: arXiv:2509.19254 ✓
- Jamica v0.3.0: doi:10.5281/zenodo.21817485 ✓
- MNE-Denoise repository: https://github.com/mne-tools/mne-denoise ✓
- Jamica repository: https://github.com/snesmaeili/jamica ✓

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

**PNPL retrospective — Elvers et al. 2026**
- Removed from Part I in the current revision to prioritize first-author, mentoring-linked,
  and brain-dynamics contributions.
- Can be restored if space permits and Hamza's specific contribution is documented precisely.

---

## Section c — non-peer-reviewed contributions

**7. Face-familiarity manuscript — Abdelhedi et al. 2026**
- Title updated to the CURRENT version:
  "Task-optimized neural networks reveal distinct contributions of specialized and
  broader visual learning to face familiarity in lateral occipital and fusiform cortex"
- The general CV source still shows the OLD title and should be updated separately.
- TODO: Confirm the current bioRxiv DOI for the updated-title version.
- TODO: Add exact journal submission date.
- Status: bioRxiv preprint; submitted for journal peer review. Do NOT move to
  section (a) until formal acceptance is documented.

**8. Benslimane et al. 2026 — NeurIPS 2026 under review**
- Reinstated because it adds evidence of research mentoring and collaborative leadership.
- Maryem Benslimane is documented in `mentoring.tex` as an MSc student mentored by Hamza
  from her engineering graduation internship through ongoing MSc work.
- Current role note: "second author; research mentor to first author."
- TODO: Add more precise intellectual/technical contribution if available (analyses,
  interpretation, methods, writing, supervision) without inventing details.

**9. MEG Foundation Models roadmap — Thölke, Abdelhedi, et al. 2026**
- arXiv:2609.04461 confirmed.
- TODO: Confirm Hamza's specific contribution beyond "second author" before final submission.

**10. Coord2Region — Abdelhedi et al. 2025**
- arXiv:2512.18165 confirmed.
- First authorship and creator/maintainer role confirmed.

**11. Oswald et al. 2025 — consciousness manuscript**
- Reinstated because it adds breadth directly relevant to electrophysiology, aperiodic activity,
  complexity and brain dynamics.
- arXiv:2509.19254 confirmed; submitted to *Neuroscience of Consciousness*.
- Current role note is deliberately conservative: "PhD; co-author."
- TODO: Replace with a precise contribution statement once Hamza's role is confirmed.

**Mantegna et al. 2026 — PNPL Competition**
- Not added. It overlaps with the existing PNPL/LibriBrain line of work and adds less marginal
  information than Benslimane or Oswald for this application.

---

## Section d — technology transfer

**12. MNE-Denoise**
- Authorship and order declared by applicant for this NSERC draft:
    1. Abdelhedi, H. (shared first)
    2. Esmaeili, S. (shared first)
    3. Larson, E.
    4. McCloy, D.
    5. Jerbi, K.
- Hyperlink added directly to the official repository: https://github.com/mne-tools/mne-denoise
- The repository's current `CITATION.cff` still lists only Esmaeili and Abdelhedi as software authors.
- Applicant explicitly requested the extended author list and shared-first ordering for this NSERC version.
- Hamza is not an MNE-Python maintainer; he is a contributor with 5 merged PRs.
- MNE conference presentation: "MNE-Denoise: Denoising methods for the MNE ecosystem,"
  MNE-Python Maintainers Conference & Sprint, Meta Paris, August 2026.

**13. Jamica v0.3.0**
- Canonical five-author citation used: Esmaeili, Abdelhedi, Mantilla-Ramos, Pascarella, Jerbi.
- Version v0.3.0 publicly released 28 August 2026.
- DOI added: doi:10.5281/zenodo.21817485.
- GitHub link added: https://github.com/snesmaeili/jamica
- Current role note: "contributor; MNE-Python integration."
- TODO: Refine with Hamza's exact technical contribution if more specific wording is available.

---

## Items deferred from Part I — conditions for reinstatement

**CoCo-PiPe**
- Public GitHub repository exists, but assess whether there is a formal public release/version before
  calling it a released research contribution in Part I.
- If formally released before NSERC submission, it could replace a weaker line because Hamza is
  creator/maintainer, which is strong evidence of independence.

**PNPL retrospective / Mantegna 2026**
- Keep deferred unless space permits or a stronger role statement becomes available.

---

## NSERC classification reminders

- All preprints and submitted manuscripts must remain in section (c) until formal acceptance is documented.
- COSYNE abstract peer-review status: verify before final classification in (b).
- Do not list open-source software as an awarded copyright without official documentation.
- Do not use impact factors, h-index, or journal prestige claims.
- The ‡ (shared first authorship) for MNE-Denoise must remain internally consistent with the applicant's
  intended authorship representation for the contribution.
