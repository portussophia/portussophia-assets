# Overrides

A PortusSophia surface may diverge where its purpose genuinely requires different composition. Divergence must be explicit and narrow.

## Permitted

- Site-specific navigation and footer data.
- Surface-specific title and role.
- Page-specific hero, archive, research, portfolio, or narrative composition.
- Additional local styles loaded after the canonical shell.
- A locally extended layout that declares the canonical `default` layout.

## Requires review

- Header height changes.
- Anchor position or size changes.
- Footer row reordering.
- Changes to canonical colors or sailcloth opacity.
- Removal of the programme rights link.

## Not permitted in v1

- Removing the gold lower header boundary.
- Replacing the anchor with the official programme mark or supporting imagery.
- Maintaining separate desktop and mobile navigation trees.
- Copying another surface's content-specific footer into the canonical include.

## Declaration format

A site with overrides should maintain a short file such as:

```text
docs/PORTUSSOPHIA-TEMPLATE-OVERRIDES.md
```

It should record the template version, changed selectors or includes, the reason for divergence, and the date reviewed.
