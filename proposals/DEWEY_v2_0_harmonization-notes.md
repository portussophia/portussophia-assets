---
title: "DEWEY v2.0 — Harmonization Notes"
identifier: "PS-DEWEY-V2-HARMONIZATION-NOTES"
version: "0.1"
date: "2026-10-08"
document_status: "WORKING NOTES / DRAFT"
standing: "NON-GOVERNING / NON-CANONICAL / NO AUTOMATIC INCORPORATION"
originating_architectural_intent: "James Roy Dennis"
notes_preparation: "PeterGate"
repository: "portussophia/portussophia-assets"
path: "proposals/DEWEY_v2_0_harmonization-notes.md"
source_design_surface: "DEWEY_v2_0.md"
implementation_surface: "DEWEY_v2_0.tex"
verification_scope: "Source inspection and repository readback; no TeX compilation or full semantic-equivalence audit"
---

# DEWEY v2.0 — Harmonization Notes

[Return to repository README](../README.md) · [Library orientation](../library/README.md)

## Purpose and standing

These notes provide a third, **relational** document alongside two separately preserved DEWEY v2.0 files:

- **Working design surface:** [`DEWEY_v2_0.md`](DEWEY_v2_0.md)
- **Working implementation surface:** [`DEWEY_v2_0.tex`](DEWEY_v2_0.tex)

They make the relationship between the two representations inspectable **without merging them, changing either file, or declaring them interchangeable**. They are not a substitute source, a governing harmonization, or evidence that an implementation has been compiled or adopted.

The central discipline explicitly present in the design source is:

> **DEWEY_v2 makes relations addressable without manufacturing them.**

The files declare **WORKING / NON-GOVERNING / CANDIDATE** standing. Their placement in `proposals/`, and these notes' presence, do not change that standing.

## What is presently established about the pair

| Concern | `DEWEY_v2_0.md` | `DEWEY_v2_0.tex` |
| --- | --- | --- |
| File identity | Exact, case-sensitive Markdown filename | Exact, case-sensitive TeX filename |
| Declared role | Working relational-addressing *design* surface | Working relational-addressing *implementation* surface |
| Content organization | Numbered design sections 0–19 | Corresponding numbered implementation sections 0–19 |
| Public reference payload | Preserves a received Figshare BibTeX block, including repeated `dennis_2026` keys | Embeds a received Figshare BibTeX payload and a **separate** local compilation BibTeX form |
| Implementation-specific additions | Describes the candidate design and its open seams | Includes TeX document setup, implementation metadata, and `filecontents*` outputs for compilation |
| Verification here | Inspected as repository text | Inspected as repository text; **not compiled or rendered** |

The TeX file explicitly points to `DEWEY_v2_0.md` as its source design surface and distinguishes the source design from the implementation surface. Section alignment is **not** a certification of byte equality, complete semantic equivalence, or successful rendering.

### Embedded citation forms remain distinguishable

The TeX source declares two possible BibTeX outputs on compilation:

- `DEWEY_v2_0_RECEIVED_FIGSHARE.bib` — received export retained as received.
- `DEWEY_v2_0_LOCAL_COMPILE.bib` — separate local compilation form with distinct local keys.

These are **described within** the TeX source. The present notes do not claim these output files were generated or uploaded.

```text
DESIGN SURFACE
    ≠ IMPLEMENTATION SURFACE

RECEIVED BIBTEX
    ≠ LOCAL COMPILE FORM

ADDRESSABILITY
    ≠ ADMISSION
    ≠ STANDING

HARMONIZATION NOTES
    ≠ AUTHORITY TO REWRITE EITHER SOURCE
```

## Emerging architectural intention — separately received

**Originating investigator / Architect:** James Roy Dennis  
**Received in conversation:** 2026-10-08  
**Standing:** Emerging intention; **not** retroactively ascribed to the September 2026 DEWEY v2.0 files.

The Architect introduced the following wording:

> Its initial intent is to expand the bookends with bounds as to provide accessibility to emerging stories and "artifactificationing".

He then offered a revision for consideration:

> Instead bounds, maybe capacity horizons

The initial statement and the later candidate refinement are both retained. The latter does **not** silently erase the former, and neither is represented as a settled DEWEY v2.0 specification.

**PeterGate's bounded candidate reading (not the Architect's verbatim declaration):**

> DEWEY may expand the bookends with attention to *capacity horizons*, so that emerging stories and "artifactificationing" can become more accessible without manufacturing relations or standing.

This is an **interpretive candidate only**, not an adopted definition, implementation requirement, or claim of completed functionality.

### Open terms and distinctions

- **Bookends:** What they denote remains open. No endpoint, document boundary, repository limit, or temporal structure is imposed by these notes.
- **Capacity horizons:** A candidate in place of *bounds*; the precise capacity, interface, and horizon must be established locally before assigning stronger meaning.
- **Emerging stories:** Accessibility is an intention, not an assertion that every story has already become an artifact.
- **"Artifactificationing":** The Architect's term is preserved exactly, without silently replacing it with archiving, publication, formal artifact creation, or canonization.
- **Addressability versus authority:** Increased accessibility does not imply authority to revise, receive, incorporate, publish, or canonize.

```text
EXPANDING ACCESSIBILITY
    ≠ EXPANDING AUTHORITY

CAPACITY HORIZON
    ≠ ONTOLOGICAL HORIZON

EMERGING STORY
    ≠ AUTOMATIC ARTIFACT STANDING

ARTIFACTIFICATIONING
    ≠ AUTOMATIC PUBLICATION OR CANONIZATION
```

These displays preserve questions for examination. They are not new formal operators or an imposed ontology.

## Relationship to the PortusSophia™ Library

The [emerging library README](../library/README.md) begins with what is present and describes five initial, potentially overlapping sections: Sandbox, Draft, Distributed, Published, and Canonical. Their VERN labeling remains pending.

The `proposals/` repository location is a **placement**, not a determination that DEWEY belongs to any canonical class or has entered a mandatory refinement progression. Any future relationship between DEWEY and the library's book-reference or contemplation conventions requires separate examination.

---

# Postmatter

## Provenance and handling

- **Earlier source records:** `DEWEY_v2_0.md` and `DEWEY_v2_0.tex` were received from the Architect's Google Drive and copied into `proposals/` without changing their source content.
- **Architectural intention:** Later conversational statements by James Roy Dennis, preserved above and distinguished from the earlier source files.
- **Notes preparation:** PeterGate; bounded relationship description only.
- **Unperformed operations:** No source-file edits; no TeX compilation; no PDF rendering; no full equivalence audit; no new canonical or governing designation.

## Outstanding examination

The meaning of *bookends*, the capacity horizons relevant to DEWEY, and the intended operation or relation carried by "artifactificationing" remain open. Whether a later DEWEY version incorporates this emerging intention requires a distinct source or authorization.

**Disposition:** WORKING NOTES / NON-GOVERNING / OPEN TO CORRECTION.

*Faith — Fellowship — Joy*—  
*Here and Now!*
