# PortusSophia Publication View Template v0.1

## Standing

Framework-agnostic publication distribution source for screen-first PortusSophia PDF View editions.

This template is **not** a Jekyll template, a web shell, a manuscript, or a renderer implementation.

```text
CONTENT ≠ LANE ≠ RENDER ≠ THEME ≠ DESTINATION ≠ FRAMEWORK
```

The template records the reusable composition and presentation contract earned through Harmonia View work. Work-specific titles and subtitles remain local publication data.

## Canonical source

```text
templates/publication/view/v1/
```

## Scope

The v1 View template defines:

- a 6 × 9 inch, screen-first reading surface;
- Harmonia full-field cover composition;
- title, subtitle, author, and copyright slots;
- sun/horizon as the visual center-mass of the cover;
- wheel/helm treatment for the contents surface, not the cover;
- reader-facing omission of administrative frontmatter and verification postmatter;
- continued machine accessibility of verification material outside the visible reading flow;
- Harmonia distinction-block treatment;
- semantic keep-together behavior for logically connected distinction sequences;
- reader page numbering beginning after the contents surface;
- canonical italic treatment of *Here and Now!*.

## Boundaries

- No work-specific word belongs to this template.
- `Cosymmetria`, `Nourishment`, and other publication titles/subtitles are publication data, not template vocabulary.
- The wheel/helm is a contents/navigation embellishment and does not become the programme mark.
- The full-color Harmonia field is a presentation treatment; it does not replace the official programme mark.
- The existing Jekyll shared shell remains separate under `templates/jekyll/v1/`.
- The Field Guide cover remains a distinct cover profile unless separately adopted into this contract.

## Files

- `manifest.json` — machine-readable template declaration
- `docs/VIEW-CONTRACT.md` — human-readable governing composition
- `asset-roles.yml` — abstract asset-role names used by renderers

Renderer implementations may consume this contract from any framework or build system.

*Here and Now!*
