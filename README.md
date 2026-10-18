# Clay Wood website

Static HTML/CSS website for [clay-wood.github.io](https://clay-wood.github.io/).
The current site was copied from `reasearch-graphics` on October 17, 2026.

## Preview locally

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000. No build tools or dependencies are required.

## GitHub Pages

Publish the root of the `master` branch. `.nojekyll` keeps the HTML, CSS,
SVG figures, images, and PDFs served directly without a Jekyll build.

## Local archive

`archive/` contains the complete previous website, including its Jekyll setup,
old GitHub workflow, and uncommitted files. It is ignored by Git and is not
included in the published repository. Its `migration-manifest.json` records
SHA-256 checksums of the preserved files. Earlier committed versions remain
available in Git history.
