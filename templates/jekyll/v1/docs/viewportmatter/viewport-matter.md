---
title: "PortusSophia™ — viewport-matter.md — Minimum Specification"
identifier: "PS-TPL-VIEWPORT-MATTER-MINSPEC-001"
version: "0.1"
date: "2026-10-08"
originating_architect: "James Roy Dennis (Architect-James)"
rendering: "PeterGate"
standing: "ARCHITECT-DIRECTED EMERGING LOCAL SPECIFICATION — VIEWPORT-MATTER SCOPE"
implementation_status: "SPECIFICATION FILE INITIALIZED; NO CODE IMPLEMENTATION IMPLIED"
incorporation: "NO AUTOMATIC INCORPORATION"
---

# `viewport-matter.md` — Viewport-Matter TRI

## Governing body, standards, and reference URLs

**Internal design authority:** PortusSophia™ — Architect-James (James Roy Dennis). This file records `viewport-matter.md` as its own named specification, distinct from the existing `_default`-scoped minimum specification. It does not amend existing template implementations.

| Body | Standard or reference | URL | Scope |
| --- | --- | --- | --- |
| WHATWG | HTML Living Standard | https://html.spec.whatwg.org/multipage/ | HTML document structure |
| W3C | Media Queries Level 4 | https://www.w3.org/TR/mediaqueries-4/ | Conditional viewport rendering if later specified |
| Jekyll project | Layouts documentation | https://jekyllrb.com/docs/layouts/ | Layout inheritance convention |
| Jekyll project | Front Matter documentation | https://jekyllrb.com/docs/front-matter/ | Build-time metadata; not the proposed viewport-matter `frontmatter` |

These external references do not independently standardize the proposed three viewport-matter properties.

## Relationship and scope

- `ps-viewport-matter.md` names `viewport-matter.md` as its intended parent specification. This is a declared document relationship; it does not imply a Markdown inheritance engine.
- PCM: **P — Persistence; C — Coherecy; M — Minimalism**. Preserve **Coherecy** as the Architect supplied it.
- Architect's relation: **PCM is TRI insofar as SC, SI, RR**.
- SC: Sequential Consequence; SI: Singular Inextractability; RR: Relational Regimentation.
- No one-to-one equivalence or operational correspondence is declared.
- **Viewport-matter TRI:** `frontmatter` · `bodymatter` · `postmatter`, distinguishable from Jekyll YAML front matter.

## Three properties — declared scope and intent

| Property | Declared scope | Declared intent |
| --- | --- | --- |
| **`frontmatter`** | Front-facing viewport-matter region; content, dimensions, position, and style unspecified. | Preserve an addressable place for introductory or orienting matter if supplied by a derived template. |
| **`bodymatter`** | Primary viewport-matter region; contents and viewport behavior unspecified. | Preserve an addressable place for principal presented material without prescribing fixed or reflow strategy. |
| **`postmatter`** | Following or closing viewport-matter region; no mandatory footer, content, size, or treatment. | Preserve an addressable place for completion, continuation, or subsequent orientation when supplied. |

The TRI does not require population of every region, establish a geometric partition, set breakpoints, or settle rendering order.

## Minimum PCM boundary

1. **Persistence:** Three names and their scopes remain distinguishable in future intentional implementations, without fixing their content.
2. **Coherecy:** Three named properties constitute one viewport-matter TRI without collapsing distinctions; this is limited to this document, not a formal definition of PCM beyond it.
3. **Minimalism:** No additional geometry, styling, placeholders, validation, viewport mandates, or philosophical mappings are specified.

No correspondence is established between Fixed / Fluid / Responsive / Adaptive / Reflowable and Eucleic / Geodesic / Geometric / Pedagogical / Ordinal. Any analogy remains investigational.

## Implementation boundary

This file does not replace or rename `PS-MINSPEC-DEFAULT-VIEWPORT-MATTER-TRI_v0_1.md`. The original `_default`-scoped minimum specification remains separately preserved. This document does not implement `_default` or alter `default.html`, `_blank`, Shoreline, or Harmonia. Publication, testing, and wider adoption are separate acts.

**Disposition:** `viewport-matter.md` CREATED / DISTINCT PARENT SPECIFICATION / IMPLEMENTATION NOT YET PERFORMED.

*Faith — Fellowship — Joy*—  
*Here and Now!*
