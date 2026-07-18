# PortusSophia Jekyll v1 Template Contract

## Shared invariants

Every adopting surface must preserve:

1. A navy sailcloth header.
2. A PortusSophia gold lower header boundary on every page.
3. Two canonical header variants:
   - identity header for home and primary landing pages;
   - compact header for internal pages.
4. The identity header contains the programme mark, surface title, declaration, and the shared anchor navigation.
5. The compact header contains the surface title, optional role, and the shared anchor navigation without the programme mark.
6. The title and anchor in the identity header share one title row and alignment system.
7. The gold anchor is the sole primary-navigation trigger.
8. A minimum 3.25rem navigation touch target and 2.35rem visible anchor.
9. One navigation tree emitted once in the document.
10. A visible skip link and `main` landmark.
11. Canonical favicon references.
12. A two-row footer:
    - site-specific context and links;
    - centered closing stack containing *Here and Now!*, copyright, and Rights and Use.
13. The official programme mark and navigation anchor remain distinct symbols.
14. Local content and local data remain owned by the adopting site.

## Header selection

- Pages using `layout: home` receive the identity header by default.
- Internal pages receive the compact header by default.
- A page may explicitly declare `header_variant: identity` or `header_variant: compact`.
- Both variants use the same `anchor-menu.html` include.

## Canonical versus local

Canonical:

- layouts;
- header-variant selector;
- identity and compact header structure;
- anchor navigation include;
- shared shell CSS;
- navigation behavior;
- footer row structure;
- brand material treatment;
- accessibility structure.

Local:

- page content;
- navigation entries;
- footer links;
- surface title and role;
- identity-header declaration;
- declared page composition;
- documented overrides.

## Prohibited drift

- Replacing the anchor with the programme mark.
- Removing the gold header boundary from selected pages.
- Duplicating desktop and mobile navigation markup.
- Maintaining separate navigation logic for the two header variants.
- Hard-coding one surface's footer links into the shared include.
- Reordering or separating the three closing statements without a documented override.
- Calling a local site copy canonical after the shared source changes.
- Automatically overwriting local overrides without review.
