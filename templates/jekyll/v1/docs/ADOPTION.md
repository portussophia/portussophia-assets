# Adoption

## Copy into a site repository

Copy these files into the adopting Jekyll site:

```text
_layouts/default.html
_layouts/home.html
_includes/head.html
_includes/header.html
_includes/footer.html
```

Create local data files from:

```text
_data/nav.example.yml    → _data/nav.yml
_data/footer.example.yml → _data/footer.yml
```

Merge the values from `config/portussophia.example.yml` into the site's `_config.yml` and adjust the surface label, role, rights URL, and asset version.

## Required plugins

The canonical `head.html` expects:

- `jekyll-seo-tag`;
- `jekyll-feed`.

Analytics remains optional.

## Review sequence

1. Copy on a branch.
2. Preserve content and declared local overrides.
3. Build the site locally.
4. Test the anchor menu by keyboard and pointer.
5. Verify the gold boundary on the homepage and subpages.
6. Verify the 16px and 32px favicon on light and dark browser chrome.
7. Verify all footer links and the rights destination.
8. Review the visual diff before merge.

## Source standing

The files in this directory are distribution sources. Each site must retain local copies for Jekyll compilation. A future update must be adopted through another reviewed change rather than by silent replacement.
