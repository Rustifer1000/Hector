# Hector

Static website mock for `hp-landscape.com`.

This repo is being used for the design and review phase before any production build or CMS migration.

## Project Purpose

- Present a client-facing homepage mock for HP Landscape
- Iterate quickly with Hector using Netlify preview links
- Keep copy, imagery, and branding easy to update
- Avoid early WordPress overhead while the design is still evolving

## Current Structure

```text
Hector/
  index.html
  styles.css
  assets/
```

## Main Files

- `index.html`: homepage structure and content
- `styles.css`: visual styling and layout
- `assets/`: logos and photography used by the mock

## How To Preview Locally

Open `index.html` in a browser.

For the most accurate review workflow, use Netlify and share the deployed preview URL.

## How To Publish A Preview

1. Push this repo to GitHub.
2. Connect the repo to Netlify.
3. Let Netlify deploy the site.
4. Share the generated preview URL for review.

## Editing Notes

- Update copy directly in `index.html`
- Update styling in `styles.css`
- Replace images or logos inside `assets/`
- Keep asset filenames stable when possible to avoid extra path changes

## Collaboration Workflow

- Use GitHub for version history
- Use Netlify for live previews
- Review changes in the browser before sharing
- Keep edits simple and incremental between review rounds

## Later Phase

If the static mock is approved, this design can either:

- continue as a static site, or
- be translated into a WordPress.org build for long-term client editing
