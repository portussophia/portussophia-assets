---
title: "PortusSophia™ — _default Viewport-Matter TRI — Minimum Specification"
identifier: "PS-TPL-DEFAULT-VIEWPORT-MATTER-TRI-MINSPEC-001"
version: "0.1"
date: "2026-10-08"
originating_architect: "James Roy Dennis (Architect-James)"
rendering: "PeterGate"
standing: "ARCHITECT-DIRECTED MINIMUM DESIGN STANDARD — _default SCOPE ONLY"
implementation_status: "SPECIFICATION RECORDED; _default CODE NOT YET IMPLEMENTED"
incorporation: "NO AUTOMATIC REPOSITORY INCORPORATION"
---

# `_default` — Viewport-Matter TRI

## Governing body, standards, and reference URLs

**Internal design authority:** PortusSophia™ — Architect-James (James Roy Dennis). This internal minimum design standard governs only the proposed `_default` scaffold layered over `_blank`; it does not amend existing template implementations.

| Body | Standard or reference | URL | Scope |
| --- | --- | --- | --- |
| WHATWG | HTML Living Standard | https://html.spec.whatwg.org/multipage/ | HTML document structure |
| W3C | Media Queries Level 4 | https://www.w3.org/TR/mediaqueries-4/ | Conditional viewport rendering if later specified |
| Jekyll project | Layouts documentation | https://jekyllrb.com/docs/layouts/ | Layout inheritance convention |
| Jekyll project | Front Matter documentation | https://jekyllrb.com/docs/front-matter/ | Build-time metadata; not the proposed viewport-matter `frontmatter` |

These external references do not independently standardize the proposed three viewport-matter properties.

## Relationship and scope

- `_default` is proposed to inherit `_blank`. It is **not yet implemented**.
- PCM: **P — Persistence; C — Coherecy; M — Minimalism**. Preserve **Coherecy** as the Architect supplied it.
- Architect's relation: **PCM is TRI insofar as SC, SI, RR**.
- SC: Sequential Consequence; SI: Singular Inextractability; RR: Relational Regimentation.
- No one-to-one equivalence or operational correspondence is declared.
- **Viewport-matter TRI:** `frontmatter` · `bodymatter` · `postmatter`, distinguishable from Jekyll YAML front matter.

## Three properties — declared scope and intent

| Property | Declared scope | Declared intent |
| --- | --- | --- |
| **`frontmatter`** | Front-facing viewport-matter region of the proposed `_default` presentation; content, dimensions, position, and style unspecified. | Preserve an addressable place for introductory or orienting matter if supplied by a derived template. |
| **`bodymatter`** | Primary viewport-matter region; contents and viewport behavior unspecified. | Preserve an addressable place for principal presented material without prescribing fixed or reflow strategy. |
| **`postmatter`** | Following or closing viewport-matter region; no mandatory footer, content, size, or treatment. | Preserve an addressable place for completion, continuation, or subsequent orientation when supplied. |

The TRI does not require population of every region, establish a geometric partition, set breakpoints, or settle rendering order.

## Minimum PCM boundary

1. **Persistence:** Three names and their scopes remain distinguishable in future intentional implementations, without fixing their content.
2. **Coherecy:** Three named properties constitute one viewport-matter TRI without collapsing distinctions; this is limited to this document, not a formal definition of PCM beyond it.
3. **Minimalism:** No additional geometry, styling, placeholders, validation, viewport mandates, or philosophical mappings are specified.

No correspondence is established between Fixed / Fluid / Responsive / Adaptive / Reflowable and Eucleic / Geodesic / Geometric / Pedagogical / Ordinal. Any analogy remains investigational.

## Implementation boundary

Specification and pointer-recording do not implement `_default` or alter `default.html`, `_blank`, Shoreline, or Harmonia. Publication, testing, and wider adoption are separate acts.

**Disposition:** MINIMUM SPECIFICATION RECORDED / ARCHITECT-DECLARED SCOPE / IMPLEMENTATION NOT YET PERFORMED.

*Faith — Fellowship — Joy*—  
*Here and Now!*
