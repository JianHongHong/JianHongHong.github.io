# Jian Hong Lee Portfolio

Public portfolio for **Jian Hong Lee**, a Blockchain Infrastructure & DevOps Engineer focused on validator and node operations, platform automation, observability, and infrastructure security.

**Live site:** [jianhonghong.github.io](https://jianhonghong.github.io/)

## Editing content

You do not need to edit HTML for normal portfolio updates. Use GitHub's web editor to change the files in [`_data/`](_data/):

- [`profile.yml`](_data/profile.yml): homepage, contact links, focus areas, and tool list
- [`protocols.yml`](_data/protocols.yml): approved blockchain ecosystems
- [`case_studies.yml`](_data/case_studies.yml): case-study copy and technologies
- [`experience.yml`](_data/experience.yml): roles, employers, dates, and experience summaries

Each file contains comments describing its purpose and public-content boundaries. Commit changes to `main`; GitHub Pages rebuilds the site automatically.

## Stack

- Jekyll and Liquid templates for page generation
- YAML files in `_data/` for editable content
- `styles.css` for responsive styling
- GitHub Pages for hosting

## Editing the design

- `index.html` controls the homepage sections and their data bindings.
- `_layouts/default.html` controls the shared document shell and metadata.
- `styles.css` controls the visual design and responsive layout.

GitHub Pages is the normal preview path for content-only edits. For local template or style work, use a working Jekyll installation:

```sh
jekyll serve
```

Open `http://127.0.0.1:4000`. If Jekyll is not installed or does not run locally, commit the approved change and verify the GitHub Pages build and rendered production site instead.

## Publishing

GitHub Pages builds the root of the `main` branch with Jekyll. Push approved changes to `main`, then verify the deployment at [jianhonghong.github.io](https://jianhonghong.github.io/).

## Content boundaries

The portfolio contains only approved public information and non-confidential descriptions of professional work. Do not add credentials, private repository links, internal infrastructure details, client information, unpublished metrics, or incident data.

See [AGENTS.md](AGENTS.md) for contributor and AI-agent guidance.
