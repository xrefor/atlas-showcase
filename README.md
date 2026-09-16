<p align="center">
  <img src="assets/atlas.svg" alt="ATLAS" width="260">
</p>

# ATLAS showcase

**Carbon surfaces. Warm ivory text. Signal orange.**

The interactive showcase for ATLAS, an appearance bundle for Omarchy.

**[Explore ATLAS ↗](https://xrefor.github.io/atlas-showcase/)**

[![Ember Seam wallpaper](backgrounds/atlas-ember-seam.png)](https://xrefor.github.io/atlas-showcase/)

This repository contains the website and its media. The theme source remains
private; installation commands and technical guides linked from the site require
repository access.

The demo shows the desktop, opening Python in Neovim, file browsing, and a brief
NymVPN panel. All terminal scenes use the normal **9 pt** font size.

## Development

```bash
python3 tools/build_site.py
python3 -m http.server 8000 --directory dist/site --bind 127.0.0.1
```

The builder stages only files referenced by the page. The GitHub Actions workflow
deploys that output to Pages when the website changes on `main`.

Original ATLAS artwork and palette: ATLAS contributors. Website source is
distributed under the [MIT license](LICENSE).
