# Booki — project guide

HTML/CSS accommodation and activities interface for Marseille, created as a responsive integration exercise.

## Scope and source

This guide describes the default branch `main` reviewed on 3 October 2026. Commands were checked against committed manifests and configuration; applications and external integrations were not executed as part of this documentation update.

## Repository map

- `index.html`
- `css/style.css`
- `images/hebergements`
- `images/activites`

## Prerequisites and local use

Clone the repository and enter its root directory:

```sh
git clone https://github.com/sarabranco92/Booki.git
cd Booki
```

Use a modern browser. No npm install is required for the static frontend. With Python installed, serve the site locally:

```sh
python -m http.server 8000
```

On Windows, use `py -m http.server 8000` if `python` is unavailable. Open http://localhost:8000/. This is a local preview server, not production hosting.

## Configuration and implementation notes

The search button is disabled in the HTML. Filters and booking links are interface examples, not a working search or reservation service. Fonts and icons use external providers.

## Verification checklist

Check navigation anchors, accommodation cards, ratings and activity images at mobile, tablet and desktop widths.

No dedicated automated test/spec files were found in the reviewed application tree. Where a test script exists, its presence alone does not establish test coverage.

## Maintenance

Keep this guide in sync when routes, commands, environment variables or hosting paths change. Use development databases/accounts for integration checks. Keep private credentials in server-side environment configuration and out of documentation. No new license or ownership terms are introduced by this guide; retain existing repository notices.
