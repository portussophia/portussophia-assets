# PortusSophia™ Jekyll Template v1

Canonical shared shell for PortusSophia Jekyll web surfaces.

This package standardizes the visible grammar of PortusSophia sites while allowing each surface to retain its own content, navigation, footer links, and genuinely site-specific overrides.

## Standing

- `portussophia-assets/templates/jekyll/v1/` is the canonical distribution source.
- `public.portussophia.com` is the reference implementation and first source used for extraction.
- Each deployed site keeps local copies of `_layouts`, `_includes`, and `_data` because Jekyll builds from the site repository.
- Sites must not load Liquid templates remotely at runtime.

## Brand contract

The v1 shell implements:

- a navy sailcloth header on every page;
- a continuous PortusSophia gold lower boundary beneath the header;
- the enlarged gold anchor as the navigation control;
- canonical shared typography and material styles;
- canonical favicon references;
- accessible single-source navigation;
- a two-row footer:
  1. site-specific context and links;
  2. a centered closing stack containing *Here and Now!*, copyright, and Rights and Use;
- configurable local navigation and footer data.

The anchor remains a navigation symbol. It does not replace the official PortusSophia programme mark, and the programme mark does not replace the anchor.

## Contents

```text
v1/
├── README.md
├── TEMPLATE-VERSION
├── _layouts/
│   ├── default.html
│   └── home.html
├── _includes/
│   ├── head.html
│   ├── header.html
│   └── footer.html
├── _data/
│   ├── nav.example.yml
│   └── footer.example.yml
├── config/
│   └── portussophia.example.yml
├── docs/
│   ├── ADOPTION.md
│   ├── OVERRIDES.md
│   └── TEMPLATE-CONTRACT.md
└── manifest.json
```

The shell also depends on:

```text
/styles/v1/site.css
/styles/v1/background-sailcloth.css
/styles/v1/jekyll-shell.css
/styles/v1/jekyll-shell-polish.css
/styles/v1/jekyll-shell-optical.css
/scripts/v1/navigation.js
/favicons/
```

## Adoption rule

Copy the template files into a site repository through a reviewed commit or pull request. Do not automatically overwrite local templates. Any local divergence must be documented as a deliberate override.

*Here and Now!*
