# Harmonia — working publication template (v0.1)

**Architect / originating direction:** James Roy Dennis (Architect-James)  
**Prepared by:** PeterGate, responding to the Architect's 2026-10-14 PDF review  
**Standing:** CURRENT WORKING PUBLICATION TEMPLATE / EXPERIMENTAL / NOT ADOPTED AS A CANONICAL STANDARD  
**Integration:** NOT YET INTEGRATED into the emerging PortusSophia™ extensibility, accessibility, and responsive/viewport-matter standard. No automatic inheritance or incorporation.

## What this is

A bounded, **working book-presentation template** for examining Harmonia's successful typography and expressive grammar without repeating defects observed in the 2026-10-14 *Integral — An Accounting of Passage* PDF. It is a **publication** surface, not a replacement for the separately active Jekyll **Harmonia v0.4 header** or the `_blank` viewport-aware baseline.

Reference for comparison: *Epistemology — Equanimity*, Harmonia View (visual composition), with the actual book manuscript and canonical art retaining their independent provenance. The reference PDF is an example of an accomplished presentation, **not** proof that its CSS or generating source is reproduced here.

Files in this working template:
- [`harmonia-print.css`](harmonia-print.css) — explicit 6 × 9-inch fixed-page starting point for HTML-to-PDF rendering.
- [`harmonia-reflow.css`](harmonia-reflow.css) — a distinct reflowable-EPUB/HTML presentation starting point; not equivalent to print pagination.

Neither stylesheet edits book prose or supplies a publisher upload configuration.

## Corrections embodied, without assuming adoption

**Cover and image geometry.** Preserve the **intrinsic proportions** of the chosen canonical source. Use proportional containment, never simultaneous forced width and height, CSS transforms, or unexamined full-bleed fill. If page and source ratios differ, **visible background/letterboxing is preferable to distortion**. A separately composed 2:3 cover may be designed and approved later. The active 1536 × 1536 Harmonia with-text identity is a *square web asset*, not silently a ready-made 6 × 9 book cover; the official PortusSophia programme mark is separately identified in this repository.

**Readable interior.** The print stylesheet offers a larger text size and less constricted 6 × 9 reading measure than the rejected rendering. These are **working values**, not validated final settings. Reflowable layouts defer where possible to reader font scaling and device dimensions.

**Pagination.** Do **not** force a new page before every `h1`, `.part-heading`, and `.chapter-heading`. That combination stranded Part headings and short passages in the rejected PDF. Instead, a *deliberately marked* `.ps-harmonia-opening` groups a Part label, Chapter title, and (if appropriate) a short opening, and may begin a new page as one unit. Headings keep with following content; ordinary narrative flows naturally. Avoid blanket `break-inside: avoid` on long sections, which can produce other empty pages.

**Explicit keep behavior.** `.ps-harmonia-keep-together` prevents breaking a **short** marked block; `.ps-harmonia-keep-with-next` keeps an explicitly selected heading or paragraph near its successor. Long blocks may require a different treatment rather than being forced to fit. The author reviews actual page images before adoption.

**Expressive elevation is a separate decision.** Do not automatically convert an isolated sentence (e.g. “It needs carriage.”), a distinction glyph, or other perceived stand-out text into a framed panel, oversized statement, or additional page. *Discuss candidate emphasis with the Architect first.* An optional `.ps-harmonia-approved-panel` hook exists only for explicitly approved placements; its presence does not approve any particular passage.

**Glyphs and symbols.** Preserve the original Unicode text. Do not normalize or swap `≠` or other operators as a cosmetic repair. Inspect **both visible glyphs and extracted/copyable characters**, with source-specific comparison. Different renderers and fonts require testing; a matching count alone is insufficient.

## Minimal markup illustration — placement, not manuscript editing

```html
<section class="ps-harmonia-opening ps-harmonia-new-page">
  <p class="ps-harmonia-part-label">Part I — [Part title]</p>
  <h1>Chapter [N] — [Chapter title]</h1>
</section>
<p>[Chapter opening remains ordinary narrative, not automatically elevated.]</p>
```

Use the wrapper only where a new page and grouped opening are actually intended. A continuous-flow chapter may simply use `<h1>` and paragraphs, without a forced break. Apply a keep class only to a bounded, intentional unit. For print cover, render the actual source art within `.ps-harmonia-cover` using `<img class="ps-harmonia-cover-image" ...>`; do not crop/stretch a historic PDF cover.

## Verification before a revised *Integral* edition

1. Inspect **source** artwork proportions and the chosen final cover placement; compare untransformed image reference and output side by side.
2. Inspect representative PDF pages at realistic reading size: ordinary prose, short passages, Part/Chapter boundaries, panels, and final lines. Confirm no Part-only pages, stranded heading, or preventable near-blank page.
3. Test any short-block keep rule against long-content fallback; confirm no clipped, overlapping, or missing text.
4. Inspect small/mobile presentation of PDF and actual reflowable EPUB readers separately. Fixed PDF **cannot** promise EPUB-like reflow.
5. Compare visible and extracted Unicode distinctions, passage order, and source prose; treat font glyph fallback, extraction, and semantic fidelity as separate checks.
6. Bring any proposed rhetorical elevation or cover redesign back to the Architect **before** changing the manuscript or selecting emphases.

**Status of testing:** Working source only. This entry does not claim renderer validation, Leanpub upload validation, a complete Sensa-Ubi implementation, or compliance with the still-emerging extensibility/accessibility/responsive standard.

## Scope boundaries

- No modifications to the active `styles/v1/jekyll-shell-harmonia.css`, Jekyll `default.html`, `_blank`, or existing sites.
- No modification to official logo/programme-mark assets, authorial manuscript, or previously distributed PDFs.
- No automatic succession into a governing template. Review of successful visual examples and bounded implementation trials remain available before any broader adoption.

*Faith — Fellowship — Joy*—  
*Here and Now!*
