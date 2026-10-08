# `_blank` — viewport-aware base layout (v0.1)

**Originating direction:** Architect-James (James Roy Dennis)  
**Implementation:** PeterGate  
**Standing:** Architect-requested **additive baseline**; opt-in; no adoption by existing sites.  
**Scope:** `templates/jekyll/v1/_layouts/_blank.html` and its independent CSS/placeholder image.

## Intent and boundary

`_blank` is the most restrained available **layout foundation** for future Jekyll layouts. It is not the existing `default.html`, and it does not override `home`, Shoreline, Harmonia, their styles, or their standing. Jekyll does **not** treat `_blank` as a global default automatically; pages and derived layouts must explicitly select it.

The baseline makes only technical presentation behaviors available: fluid width and spacing; small-width responsive adjustment; intrinsic media proportions; optional auto-fitting content grids; and reflowable HTML content. It does not infer a direct one-to-one mapping between **Fixed, Fluid, Responsive, Adaptive, Reflowable** and the Architect's separately raised **Eucleic, Geodesic, Geometric, Pedagogical, Ordinal**. Analogous depth correspondence remains an open investigation, not a feature claim.

## Installed parts

- `_layouts/_blank.html` — standalone accessible HTML document shell with viewport meta, skip link, image/header slot, `main` and `{{ content }}`.
- `../../../styles/v1/jekyll-shell-blank.css` — neutral width-aware CSS; independent of the existing site/shell styles.
- `assets/blank-logo-128.png` — exact **128 × 128 transparent RGBA PNG** with **no visible mark**. It is a neutral image placeholder, **not a replacement logo** or the official programme mark.

Because the fallback logo is transparent throughout, a site choosing to display a meaningful image should supply its own 128 × 128 transparent PNG URL and text alternative. The CSS scales its display proportionally at smaller widths without modifying the original pixels.

## Use in an adopting Jekyll site

Copy `_layouts/_blank.html` into the adopting site's `_layouts/` directory (Jekyll compiles from local layout sources). The CSS and neutral placeholder are served from `https://assets.portussophia.com` when `portussophia.asset_origin` is not set.

Use it directly on a page:

```yaml
---
layout: _blank
title: Example page
blank_logo_url: "https://example.org/128x128-transparent-logo.png"
blank_logo_alt: "Example organization"
blank_header_label: "Example reading surface"
---
```

Or derive a separate **local** layout. For instance, an adopting site may create `_layouts/reading.html`:

```html
---
layout: _blank
---
<section class="ps-blank-reading">
  {{ content }}
</section>
```

Then a page may specify `layout: reading`. Jekyll's native layout inheritance places the derived layout inside the `_blank` document shell.

Optional keys, supplied in page front matter or under `site.portussophia`, are `blank_logo_url`, `blank_logo_alt`, `blank_header_label`, and `blank_css_url`. The last loads an opt-in concrete stylesheet **after** the neutral baseline. The page's `title` supplies the document title; `page.lang` or `site.lang` supplies the language.

The baseline's reusable classes are:

- `.ps-blank-reading` — a legible maximum measure for prose.
- `.ps-blank-grid` — columns that fit and reflow to available width.
- `.ps-blank-overflow` — scroll containment for non-reflowable tables, wide notation, and similar materials.

No dummy text, navigation, footer, icon semantics, canonical logo, global site layout switch, or viewport-aspect-to-philosophical mapping is imposed.

## Verification guidance

Build an adopting test site with Jekyll, then inspect 320, 360, 390, 768 and 1024 CSS-pixel viewport widths in portrait/landscape where available. Confirm:

1. The page has **no unintended horizontal body scrolling**.
2. Images remain proportional; their intrinsic width/height attributes are 128 × 128 for the logo slot.
3. Content reading order and accessible landmarks remain stable.
4. Wrappable text reflows; wide material is deliberately contained when necessary.
5. An inheriting layout renders its own content without a nested document shell.
6. Existing `default`, Shoreline and Harmonia routes render without change.

A browser/real-device result is **not** claimed by publishing these source files. Responsive technical capability does not establish a tested depth correspondence.

**Disposition:** Implemented opt-in baseline; independent testing and site adoption remain separate decisions.
