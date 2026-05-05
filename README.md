# Shen Research Group Website

Static Hugo rebuild of the Shen Research Group website, based on the HugoBlox Research Group starter and deployed with GitHub Pages.

Temporary publishing target: `https://jieshenlab-NTU.github.io/`.

## Local development

```sh
HUGO_CACHEDIR=/tmp/hugo-cache hugo server
```

## Production build

```sh
HUGO_CACHEDIR=/tmp/hugo-cache hugo --gc --minify
```

The HugoBlox Bootstrap theme is vendored under `themes/` so the site builds without requiring Go module resolution locally.
