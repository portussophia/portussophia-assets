---
title: "[Book Title]"
subtitle: "[Subtitle]"
author: "[Author]"
publisher: "PortusSophia, LLC"
copyright: "© [YEAR] PortusSophia, LLC"
publication_status: "draft"
theme: "Harmonia"
view_profile: "6x9"
semantic_markup: "PortusSophia rhetorical roles v0.1"
---

<!--
PORTUSSOPHIA MANUSCRIPT MARKDOWN TEMPLATE
Version: v0.1

PURPOSE
This manuscript source records rhetorical structure without binding that
structure to a single visual renderer.

SOURCE SEMANTICS ≠ RENDERING DEVICE

Core rhetorical roles:

.accretion         ~ run-time build
.reveal            ~ compiled reveal
.hinge             ~ major relational turn
.distinction       ~ formal relation / established distinction
.canonical-closing ~ canonical closing rendered through distinction treatment

The relation is analogical, not identity:

ACCRETION ~ run-time build
REVEAL / HINGE ~ compile

REFERENCE RENDERING BEHAVIOR
A renderer may present:

- accretion units as a lightly bordered sequence/table body;
- reveal as a materially heavier footer/bottom boundary;
- hinge in the established distinction field with white italic text;
- distinction in the established distinction field with gold italic text;
- canonical closing through the distinction treatment.

Those are rendering choices. The manuscript source declares rhetorical role.

USE ACCRETION WHEN
Successive prose units acquire force cumulatively and ordering increases
interpretive weight. Do not use it merely because several paragraphs are
short, parallel, or visually list-like.

USE REVEAL WHEN
The accretion resolves into a sentence, paragraph, distinction, or closing
whose force depends materially on the accumulated state before it.
A reveal is optional; not every accretion compiles locally.

USE HINGE WHEN
A sentence or short passage turns the reader into a materially different
relational or interpretive condition without itself being a formal
symbolic distinction.

USE DISTINCTION WHEN
The manuscript explicitly states a formal relation, inequality, separation,
or named structural distinction.

NESTED CONTAINER RULE
When one semantic container appears inside another, the outer container must
use more colons than the inner container.

Example hierarchy:

::::: outer accretion
::::  reveal
:::   distinction

This preserves balanced Markdown container syntax.
-->

# Part I — [Part Title]

## Chapter I — [Chapter Title]

[Opening prose.]

[Ordinary paragraphs remain ordinary Markdown paragraphs.]

<!--
ACCRETION WITHOUT LOCAL REVEAL

Use four-colon outer fences when there is no nested semantic block:

:::: {.accretion}
First cumulative unit.

Second cumulative unit.

Third cumulative unit.
::::
-->

<!--
ACCRETION WITH COMPILED REVEAL

:::: {.accretion}
First cumulative unit.

Second cumulative unit.

Third cumulative unit.

::: {.reveal}
The relation that becomes legible because the preceding units accumulated.
:::
::::
-->

<!--
HINGE

::: {.hinge}
*A major relational turn.*
:::
-->

<!--
FORMAL DISTINCTION

::: {.distinction}
TERM A ≠ TERM B
:::
-->

<!--
ACCRETION WHOSE REVEAL IS ITSELF A DISTINCTION

Use five, four, and three colons so the nesting remains unambiguous:

::::: {.accretion}
First cumulative unit.

Second cumulative unit.

Third cumulative unit.

:::: {.reveal}
::: {.distinction}
ACCUMULATED CONDITION ≠ EXHAUSTIVE EXPLANATION
:::
::::
:::::
-->

<!--
CANONICAL CLOSING

If the closing is both the compiled reveal of a final accretion and the
canonical closing, the nesting may be:

::::: {.accretion}
Final cumulative unit.

Another cumulative unit.

Another cumulative unit.

:::: {.reveal}
::: {.distinction .canonical-closing}
*Here and Now!*
:::
::::
:::::

If the closing is not a reveal, it may stand alone:

::: {.distinction .canonical-closing}
*Here and Now!*
:::
-->

[Continue manuscript prose.]

---

# Part II — [Part Title]

## Chapter III — [Chapter Title]

[Continue manuscript.]

<!--
EDITORIAL / RENDERING GUARDS

1. Do not convert accretions into ordinary bullet or numbered lists unless
   the manuscript itself intends enumeration as such.

2. Do not infer a reveal merely from brevity or paragraph position.
   The reveal must depend materially on accumulated prior state.

3. Do not collapse hinge and distinction into one semantic class.
   Their visual treatments may share a field while their roles remain distinct.

4. Do not replace ~ with = in the run-time-build / compile analogy.

5. Preserve manuscript wording exactly when adding semantic wrappers.
   Semantic markup should disclose structure already present in the prose,
   not manufacture new meaning.

6. Rendering may vary across Markdown, Print PDF, View PDF, web, or other
   publication surfaces while preserving the declared semantic role.
-->
