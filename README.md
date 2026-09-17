# Trend Dashboard Pages release

This repository contains only the public static dashboard release.

- Images are served from `https://static-dashff.fnf.co.kr/`.
- The release includes only assets whose Base and Detail VLM stages are final.
- Active `ahspirin` work, local file paths, Meta CDN URLs, credentials, raw API
  responses, and local review artifacts are excluded.
- `release_report.json` binds this release to its validated source dashboard and
  durable-media overlay hashes.

The site is deployed by `.github/workflows/pages.yml` after updates to `main`.
