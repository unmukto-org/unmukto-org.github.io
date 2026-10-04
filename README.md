# Unmukto

The landing page for https://unmukto.org, maintained by [unmukto-org](https://github.com/unmukto-org).

One static HTML page and CSS. No application JavaScript, framework, build dependencies, analytics or external font requests. Obadh's app icon and self-hosted typefaces come from the Obadh website; font licenses are beside the font files.

## Preview

```sh
python3 -m http.server 4322 --directory site --bind 127.0.0.1
```

## Publish

Push to `main`. The Pages workflow publishes only `site/`. Enable GitHub Pages with GitHub Actions as its source. Set its custom domain to `unmukto.org` after the DNS records point to GitHub Pages, then enable HTTPS enforcement when the certificate is ready.

Canonical and social URLs assume `https://unmukto.org/`. The sitemap lists the homepage; the 404 page is excluded from indexing.

The Obadh card uses the unmodified `typing-dark.png` release screenshot from the App Store assets, stored as `site/assets/obadh-iphone.png`. CSS frames the message field and complete keyboard, excluding the unused conversation area.

The approved Unmukto calligraphic উ logo is stored in `site/assets/unmukto-logo.png`. The favicon, Apple touch icon, and social preview use the same artwork.
