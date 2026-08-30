# Agent guidance

## Purpose

This repository publishes Jian Hong Lee's public portfolio at [jianhonghong.github.io](https://jianhonghong.github.io/). GitHub Pages builds the Jekyll site from `main`.

## Repository layout

- `_data/profile.yml`: homepage, contact links, focus areas, and tools
- `_data/protocols.yml`: approved protocol landscape entries
- `_data/case_studies.yml`: representative, non-confidential case studies
- `_data/experience.yml`: professional experience
- `index.html`: Jekyll homepage template and data bindings
- `_layouts/default.html`: shared document shell and metadata
- `styles.css`: responsive visual system
- `README.md`: editing and publishing instructions

## Editing rules

- Preserve the site's restrained editorial style, semantic HTML, keyboard navigation, and responsive behavior.
- Keep copy specific, factual, and concise. Do not invent outcomes, metrics, dates, technologies, project ownership, or client relationships.
- Treat all employer and client work as confidential unless the repository owner explicitly approves the exact information for publication.
- Do not add credentials, internal repository URLs, private architecture, node inventories, incident details, customer data, unpublished metrics, or operational secrets.
- Do not add decorative animations, skill percentages, generic technology lists, or placeholder content.
- Use hyphens or commas instead of em dashes.
- Keep external links to GitHub and LinkedIn accurate. Do not change public contact details without explicit approval.

## Editing content

- For normal copy changes, edit only the relevant `_data/*.yml` file. Preserve YAML indentation and comments.
- Update a template only when changing page structure. Update `styles.css` only when changing presentation.
- Do not duplicate content in `index.html`; it belongs in `_data/`.
- Keep content fields factual, concise, and approved for public use.

## Verification

For template or style changes, use a local Jekyll environment:

```sh
jekyll serve
```

Open `http://127.0.0.1:4000` and check desktop and mobile layouts, visible copy, links, and horizontal overflow. For content-only changes, verify the rendered production site after GitHub Pages reports a successful build. Commit only the files required for the change.

## Deployment

GitHub Pages serves the root of the `main` branch. Pushing to `main` publishes the static site. Verify the deployed page at `https://jianhonghong.github.io/` after GitHub Pages reports a successful build.
