# PortusSophia Publication View v1 — View Contract

## 1. Purpose

The View profile is a reader-first PDF presentation intended primarily for phones and screens.

It is not the Print profile and should not be constrained by print-ink economy.

```text
VIEW PDF ≠ PRINT PDF
```

The View profile may therefore use the full Harmonia color field where that treatment improves orientation and identity.

## 2. Cover composition

The cover uses an approved Harmonia field as the visual ground.

The controlling relation is:

```text
SUN / HORIZON
    → VISUAL CENTER-MASS

TITLE / SUBTITLE
    → PUBLICATION IDENTITY

AUTHOR / COPYRIGHT
    → QUIET LOWER ANCHOR
```

The sun and horizon are not displaced merely to center the typography geometrically. Optical balance governs the composition.

### Slots

Renderers receive only:

- `title`
- `subtitle`
- `author`
- `copyright`

No publication-specific word is encoded into the template.

The title is large, centered, gold serif. The subtitle remains materially smaller and uses an italic serif treatment corresponding to the established Harmonia subtitle language.

The author and copyright remain centered near the lower edge and must not compete with the center-mass.

The wheel/helm does not appear on the cover.

## 3. Contents surface

The contents page may use the wheel/helm as a navigation ornament.

The wheel/helm is:

```text
CONTENTS / NAVIGATION EMBELLISHMENT
    ≠
PROGRAMME MARK
    ≠
PRIMARY COVER IDENTITY
```

It should remain subordinate to the contents structure.

The contents surface follows the cover. Reader-facing page numbering begins with the reading work after the contents surface.

## 4. Visible matter and verification matter

The View edition may omit visible administrative frontmatter and visible verification postmatter.

Omission from the reader flow does not authorize deletion.

```text
VISIBLE TO READER
    ≠
AVAILABLE TO SYSTEM
```

Verification material should remain recoverable through embedded attachments, source packages, sidecar records, or another declared machine-accessible surface.

Where notation or formal distinctions occur, the verification record should include **Notation and Representation Control** sufficient to distinguish operative relation from visible representation.

## 5. Reading profile

Baseline v1 values:

- page: 6 × 9 inches;
- body: approximately 14 pt;
- leading: approximately 21 pt;
- generous screen-oriented margins;
- restrained running furniture;
- reading pages remain materially quieter than the cover.

Exact font metrics may vary with the renderer, but readability and hierarchy should remain equivalent.

## 6. Distinction presentation

Distinctions are not source-code decorations.

A distinction should remain extractable as ordinary text while receiving a Harmonia presentation treatment.

Preferred visual form:

```text
┌────────────────────────────────────┐
│ THIS ≠ THAT                        │
└────────────────────────────────────┘
```

Presentation:

- deep navy field;
- gold italic serif text;
- subtitle-adjacent typographic character;
- restrained thin gold rules;
- rounded field may be used where supported;
- no gray code-console treatment in View.

When line length permits, render `THIS ≠ THAT` as one relation. When wrapping is necessary, preserve relational clarity rather than forcing a syntactic-looking stack.

## 7. Semantic keep-groups

Pagination must respect logical relation, not only individual block geometry.

A lead-in, distinction, connective phrase, adjacent distinction, and immediate interpretive sentence may form one semantic keep-group.

Example:

```text
lead-in
DISTINCTION A
and:
DISTINCTION B
interpretive sentence
```

If the group cannot fit responsibly, move the group rather than splitting the relation across pages.

This rule is stronger than `keepWithNext` applied to a single heading or paragraph.

## 8. Canonical closing

The canonical closing is rendered:

*Here and Now!*

The italics are canonical typography, not optional emphasis.

## 9. Framework boundary

This contract is framework-agnostic.

It may be consumed by Python, LaTeX, Typst, Pandoc, Vue, Angular, Jekyll, or another implementation without changing its standing.

```text
PUBLICATION CONTRACT ≠ FRAMEWORK ADAPTER
```

The existing Jekyll shared shell remains governed separately by `templates/jekyll/v1/`.

## 10. Field Guide boundary

The established *A Field Guide to Epistemic Failure* cover is not silently normalized into this cover family.

Its cover remains a distinct profile unless a later explicit decision brings it under this contract.

*Here and Now!*
