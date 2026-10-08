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
| IETF (BCP 47) | RFC 5646 — Tags for Identifying Languages | https://www.rfc-editor.org/info/rfc5646/ | Structure and meaning of language tags for language identification; does not specify viewport geometry |
| IETF (BCP 47) | RFC 4647 — Matching of Language Tags | https://www.rfc-editor.org/info/rfc4647/ | Language-range matching if a locality later requires content-language selection |
| Jekyll project | Layouts documentation | https://jekyllrb.com/docs/layouts/ | Layout inheritance convention |
| Jekyll project | Front Matter documentation | https://jekyllrb.com/docs/front-matter/ | Build-time metadata; not the proposed viewport-matter `frontmatter` |

**BCP 47** is the IETF Best Current Practice encompassing RFC 5646 and RFC 4647 (https://www.rfc-editor.org/info/bcp47/). Its relevance here is language identification and, where selected, matching—not an assertion that a language tag alone specifies geography, text direction, styling, or an entire locality standard.

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


## Investigational carry pointer — here be dragons

[LOGOS's reflection on carry across tool boundaries and success-criterion saliency](https://docs.google.com/document/d/1YUI9heTEhkjYtM-u4OpiIzP200NWdHuPi8cXpk35P2o/edit) distinguishes **semantic**, **operational**, and **verification** carry as candidate research relations; it does **not** establish their identity or prescribe a protocol. Carry may remain available while operational saliency degrades.

**Here be dragons:** no correspondence is presently established between those three carry relations and viewport-matter `frontmatter`, `bodymatter`, or `postmatter`. This pointer preserves the research question; it does not impose a locality standard, carry mechanism, validation obligation, or implementation.


## Suggestions — exploratory viewport-space CSS and locality discussion

**Standing:** PeterGate suggestions for discussion with Architect-James; not adopted standards, not implemented CSS, and not authority to change templates. The Architect directs that `_default` remain untouched while ideas are examined within the associated viewport-matter documentation.

1. **Preserve the necessary gap.** `_blank` already has an opt-in, presentation-neutral technical CSS baseline (`styles/v1/jekyll-shell-blank.css`). Treat its responsive safety measures as existing capabilities, not a license to introduce locality or PortusSophia branding into the gap. No change to `_blank` is proposed at this stage.
2. **Clarify locality before prescribing CSS.** Investigate whether `_default` locality concerns viewport conditions, adopting-site conventions, language and writing direction, reading conditions, accessibility, or relationships among them. BCP 47 offers language-tagging and matching standards for part of that discussion; it is not itself a universal locality or CSS standard. Keep HTML `lang` distinct from `dir` and from a site’s visual style.
3. **Keep the viewport-matter TRI addressable but unforced.** Explore optional presentation of `frontmatter`, `bodymatter`, and `postmatter` when supplied; absent matter should not require dummy content. No required three-row, three-column, equal-area, fixed-position, or fixed-order CSS layout is selected. The TRI remains distinct from Jekyll YAML front matter.
4. **Explore CSS separation as candidates only.** One possible future distribution is `viewport-locality.css` for agreed locality behavior and `ps-viewportmatter.css` for an opt-in PortusSophia-specific expression. These filenames, their responsibilities, and any loading sequence remain suggestions. Existing `_blank` support for optional `blank_css_url` is a technical capability to examine, not an adoption decision.
5. **Test a bounded example before styling the system.** If later authorized, use a separate test page with prose, a long heading, an image, and wide tabular material. Examine narrow/mobile and wider viewports, text reflow, overflow, keyboard focus, readable measure, and content order. Proposed checkpoints include 320, 360, 390, 768, and 1024 CSS pixels. No browser or device verification is claimed now.
6. **Preserve standing and layer distinctions.** `_blank` is reserved as a necessary gap; `_default` is for locality standards; PortusSophia™ is to honor both by way of `ps-viewport-matter.md` (Architect's reflection). The semantic/operational/verification carry hypothesis from LOGOS is a research pointer, not a mandated mapping to the three matter regions.

**Current hold:** Discussion and candidate documentation only. Do not implement or alter `_layouts/_default.html`, `_layouts/_blank.html`, `_layouts/ps_default.html`, any existing stylesheets, or adopting-site templates until the Architect directs the next step.

## Implementation boundary

This file does not replace or rename `PS-MINSPEC-DEFAULT-VIEWPORT-MATTER-TRI_v0_1.md`. The original `_default`-scoped minimum specification remains separately preserved. This document does not implement `_default` or alter `default.html`, `_blank`, Shoreline, or Harmonia. Publication, testing, and wider adoption are separate acts.

**Disposition:** `viewport-matter.md` CREATED / DISTINCT PARENT SPECIFICATION / IMPLEMENTATION NOT YET PERFORMED.

*Faith — Fellowship — Joy*—  
*Here and Now!*
