# Agent guidance

## Purpose

This repository publishes Jian Hong Lee's public portfolio at [jianhonghong.github.io](https://jianhonghong.github.io/). It is a static site with no build step.

## Repository layout

- `index.html`: page structure and portfolio copy
- `styles.css`: responsive visual system
- `README.md`: local preview and deployment instructions

## Editing rules

- Preserve the site's restrained editorial style, semantic HTML, keyboard navigation, and responsive behavior.
- Keep copy specific, factual, and concise. Do not invent outcomes, metrics, dates, technologies, project ownership, or client relationships.
- Treat all employer and client work as confidential unless the repository owner explicitly approves the exact information for publication.
- Do not add credentials, internal repository URLs, private architecture, node inventories, incident details, customer data, unpublished metrics, or operational secrets.
- Do not add decorative animations, skill percentages, generic technology lists, or placeholder content.
- Use hyphens or commas instead of em dashes.
- Keep external links to GitHub and LinkedIn accurate. Do not change public contact details without explicit approval.

## Verification

After changing the site, preview it locally:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open `http://127.0.0.1:4173` and check desktop and mobile layouts, visible copy, links, and horizontal overflow. Commit only the files required for the change.

## Deployment

GitHub Pages serves the root of the `main` branch. Pushing to `main` publishes the static site. Verify the deployed page at `https://jianhonghong.github.io/` after GitHub Pages reports a successful build.
