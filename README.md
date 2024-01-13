# Afro Solo UK

A fork of [Strength of our Mothers](https://ourmothers.org/).

## Installing

```
gh repo clone geeksforsocialchange/afrosolouk
cd afrosolouk
bundle
```

## Development server

```
bundle exec jekyll serve --livereload
```

## Deployment

Hosted on GFSC Cloudflare pages account.

Uses [Cloudflare pages app](https://github.com/apps/cloudflare-pages) to build and deploy.

- Generates a preview on creation of each Pull Request
- Releases to [production](https://afrosolouk.pages.dev) on push to `main` branch.
