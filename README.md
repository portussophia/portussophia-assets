# portussophia-assets

Shared public style, image, favicon, and brand assets for PortusSophia™ web surfaces.

This repository is the common static-asset origin served through `assets.portussophia.com`. Individual PortusSophia sites retain their own content, markup, and genuine site-specific overrides.

## Repository role

This repository provides:

- canonical shared stylesheets;
- public image assets;
- the PortusSophia programme-mark reference;
- browser and application favicon assets;
- supporting brand illustrations and icon studies;
- brand briefs, review records, and manifests;
- and reusable web integration snippets.

It is a static asset repository. It does not require its own Jekyll or Ruby installation.

## Current structure

```text
.
├── styles/                  # Shared, versioned site styles
├── img/                     # Public image assets
├── official/
│   └── reference/           # Supplied programme-mark source references
├── brand/
│   ├── supporting-symbols/  # Harbor and triad studies
│   ├── icons/               # Structura, Ethica, and Lumen icons
│   ├── materials/           # Sailcloth and footer-wave studies
│   └── boards/              # Review boards and previews
├── favicons/                # Browser, touch, and application icons
├── docs/
│   ├── briefs/              # Governing visual briefs
│   ├── review/              # Review dispositions and changelogs
│   └── manifests/           # Asset inventory and checksums
├── web/
│   └── snippets/            # Reusable integration markup
├── CNAME
├── RIGHTS.md
└── README.md
```

## Official programme mark

The supplied PortusSophia programme mark remains the official mark.

The harbor study, Structura · Ethica · Lumen triad, and three-icon family are supporting or explanatory assets. They do not replace the programme mark.

The source raster is retained under:

```text
official/reference/portussophia-programme-mark-source-raster.png
```

It is a transparent PNG source reference, not an original vector master.

## Favicon boundary

The favicon system is derived from the supplied transparent programme-mark raster and places it within a fixed navy badge with a restrained grey rim.

This provides stable contrast on both light and dark browser chrome without changing the mark's colors.

The SVG favicon embeds the source raster. It is a faithful small-size derivative, not an original vector master or replacement logo.

## Brand asset standing

The current controlled brand package is **v0.2**.

- The official programme mark is unchanged.
- The Harbor study is a supporting symbol.
- The Structura · Ethica · Lumen triad is an explanatory asset and should retain its labels in public use.
- The Structura, Ethica, and Lumen icons form a supporting icon family.
- The sailcloth swatch documents the canonical navy material treatment.
- Review records and checksums are retained under `docs/`.

Do not overwrite official mark references or canonical stylesheet sources without a separate release decision.

## Rights and use

Copyright © 2026 PortusSophia, LLC. All rights reserved.

See [`RIGHTS.md`](RIGHTS.md) for the repository's full rights and use statement.

*Here and Now!*
