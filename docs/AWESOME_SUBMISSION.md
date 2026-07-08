# Official Awesome List Submission Checklist

Use this checklist when submitting `awesome-cesium` to [`sindresorhus/awesome`](https://github.com/sindresorhus/awesome).

Official references:

- [Create a list](https://github.com/sindresorhus/awesome/blob/main/create-list.md)
- [PR template / list guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md)
- [`awesome-lint`](https://github.com/sindresorhus/awesome-lint)

## Before Opening the PR

- [ ] Re-read the full [pull request template](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md).
- [ ] Confirm the list has existed for **30+ days** (this repo was created 2025-06-09).
- [ ] Repo name is lowercase slug: `awesome-cesium`.
- [ ] Heading is title case: `# Awesome Cesium`.
- [ ] License is Creative Commons (this repo uses `CC0-1.0`).
- [ ] README starts with a succinct description of the theme.
- [ ] First section after the intro is `## Contents`.
- [ ] Run `npx awesome-lint` and fix all reported issues.
- [ ] Remove empty placeholder sections and unfinished entries.
- [ ] Ensure entries are high-quality, maintained, and not duplicates of a better list.
- [ ] Do **not** open a Draft/WIP PR against `sindresorhus/awesome`.

## GitHub Discoverability (Do First)

Token used by CI/cloud agents may lack `Administration` permission. Set these in the GitHub UI if the API returns 403:

1. Repo → **About** → edit description / website
2. Suggested description: `A curated list of awesome CesiumJS resources, libraries, tools, and integrations for 3D geospatial apps`
3. Suggested website: `https://github.com/reed-soul/awesome-cesium#readme`
4. Suggested topics: `awesome`, `awesome-list`, `cesium`, `cesiumjs`, `3d-tiles`, `3d-globe`, `webgis`, `geospatial`, `gis`, `webgl`, `gltf`, `mapping`, `javascript`, `typescript`

- [ ] Add the topics above in the GitHub UI.
- [ ] Set repository homepage / description clearly.
- [ ] Optionally publish a simple GitHub Pages landing that redirects to the README.

## Community Cross-Links (Do Before or Alongside Submission)

These drive discovery more than the official listing alone:

- [ ] Ask to be linked from [Awesome 3D Tiles](https://github.com/pka/awesome-3d-tiles).
- [ ] Propose a Cesium / related entry in [Awesome Frontend GIS](https://github.com/JoeWDavies/awesome-frontend-gis).
- [ ] Propose a Cesium entry in [Awesome GIS](https://github.com/sshuair/awesome-gis) and/or [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial).
- [ ] Share in the [Cesium Community Forum](https://community.cesium.com/) and [Discord](https://discord.gg/cesium).
- [ ] Ask maintainers of high-star listed projects to add an “Awesome Cesium” link in their README Related section.

## Opening the `sindresorhus/awesome` PR

- [ ] Review **at least 4 other open PRs** thoroughly (point out real issues; “LGTM” does not count).
- [ ] Comment on your PR which PRs you reviewed.
- [ ] Confirm the list is **not** AI-generated spam; human curation must be evident.
- [ ] Fill every checkbox in their PR template honestly.
- [ ] Expect review feedback and iterate patiently; merges can take a long time.

## Suggested PR Description Snippet

```md
### Awesome Cesium

A curated list of CesiumJS libraries, tools, framework integrations, game-engine bindings, and learning resources for the 3D geospatial ecosystem.

- Repo: https://github.com/reed-soul/awesome-cesium
- Bilingual (EN / ZH)
- Actively maintained with link checks and quality automation
```

## After Merge

- [ ] Update README badge/link if needed.
- [ ] Announce in Cesium community channels.
- [ ] Keep the list lean: prefer removing stale entries over endless growth.
