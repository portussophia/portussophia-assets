# portussophia-assets

Shared public style, image, favicon, brand, and template assets for PortusSophia™ web and publication surfaces.

This repository is the common static-asset and template-distribution origin served through `assets.portussophia.com`. Individual PortusSophia sites retain their own content, local Jekyll copies, and genuine site-specific overrides. Publication renderers may consume publication contracts from this repository without depending on Jekyll.

## Repository role

This repository provides:

- canonical shared stylesheets;
- public image assets;
- the PortusSophia programme-mark reference;
- browser and application favicon assets;
- supporting brand illustrations and icon studies;
- canonical Jekyll layout and include distribution sources;
- framework-agnostic publication template contracts;
- shared navigation behavior;
- brand briefs, review records, and manifests;
- and reusable web integration snippets.

The repository remains a static asset and template-distribution origin. It does not require its own Jekyll or Ruby installation. Jekyll templates stored here are copied into adopting site repositories for compilation; they are not loaded remotely at runtime. Publication contracts are likewise consumed by renderers rather than executed by this repository.

## Current structure

```text
.
├── styles/                  # Shared, versioned site and shell styles
├── scripts/                 # Shared, versioned browser behavior
├── templates/
│   ├── jekyll/              # Canonical Jekyll distribution sources
│   └── publication/
│       └── view/            # Framework-agnostic View publication contract
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

## Jekyll template source

The canonical shared shell is maintained under:

```text
templates/jekyll/v1/
```

It standardizes the navy sailcloth header, gold lower header boundary, enlarged gold anchor navigation control, canonical favicon integration, accessible single-source navigation, and three-row footer architecture.

`public.portussophia.com` is the reference implementation and initial extraction source. After harmonization, the files in this repository are canonical for the shared shell. Public remains canonical for Public-specific content and composition.

Every adopting site retains local copies of `_layouts`, `_includes`, and `_data`. Adoption and later synchronization occur through reviewed commits rather than automatic overwrites.

## Publication View template source

The framework-agnostic Harmonia View publication contract is maintained under:

```text
templates/publication/view/v1/
```

It defines reusable View-edition composition and presentation without binding publication output to Jekyll, Vue, Angular, Python, LaTeX, Typst, Pandoc, or another renderer.

Its governing boundary is:

```text
PUBLICATION CONTRACT ≠ FRAMEWORK ADAPTER
```

Work-specific titles and subtitles remain local publication data and do not become template vocabulary.

## Official programme mark

The supplied PortusSophia programme mark remains the official mark.

The harbor study, Structura · Ethica · Lumen triad, and three-icon family are supporting or explanatory assets. They do not replace the programme mark.

The gold anchor remains the navigation control. It does not replace the programme mark, and the programme mark does not replace it.

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
- The Jekyll v1 shell implements the shared brand grammar across PortusSophia sites.
- The publication View v1 source records a framework-agnostic publication contract; it does not replace the Jekyll shell.
- Review records and checksums are retained under `docs/`.

Do not overwrite official mark references, canonical stylesheet sources, or canonical templates without a separate release decision.

## Rights and use

Copyright © 2026 PortusSophia, LLC. All rights reserved.

See [`RIGHTS.md`](RIGHTS.md) for the repository's full rights and use statement.

*Here and Now!*
