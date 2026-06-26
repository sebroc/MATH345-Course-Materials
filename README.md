# MATH 345 Course Materials

Static public course materials for MATH 345.

## Layout

- `site/`: department-site files for manual upload.
- `games/`: static puzzle games published by GitHub Pages.
- `scripts/`: local maintenance helpers.

The PreTeXt textbook remains separate and public at:

```text
https://sebroc.github.io/MATH345-Textbook/
```

Canonical lab notebooks live in the textbook repo:

```text
../MATH345-Textbook-v0.2/notebooks/
```

Run `python3 scripts/sync_site_notebooks.py` before publishing the department
site if `site/notebooks/` should carry local notebook downloads.

## Publishing

Department site:

1. Review `site/` locally over HTTP.
2. Upload the contents of `site/` to the department server.
3. Preserve the relative directory structure.

Games:

1. Add each game under `games/<game-slug>/index.html`.
2. Record it in `games/games.json`.
3. Publish through GitHub Pages.

Expected games URL after creating the public GitHub repo:

```text
https://sebroc.github.io/MATH345-Course-Materials/games/
```

