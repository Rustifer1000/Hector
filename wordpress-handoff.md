# HP Landscape WordPress Handoff

This prototype is designed to translate cleanly into a low-cost self-hosted WordPress.org site using Gutenberg.

## Recommended Stack

- Hosting: Hostinger or Namecheap EasyWP for lower recurring cost
- CMS: WordPress.org
- Editing: Gutenberg block editor
- Theme approach: lightweight block theme or custom child theme
- Plugins: keep minimal

## Recommended Theme Direction

Use one of these approaches:

- Option A: start from a lightweight block theme such as `Twenty Twenty-Six` and restyle it
- Option B: use a premium but restrained block theme if faster polish is needed
- Option C: create a very small custom theme based on this prototype once the design is approved

Best path for speed and low cost:

- Start with a lightweight default block theme
- Recreate the homepage as a single custom page template or homepage pattern
- Apply brand styles with theme variables and small custom CSS

## Page Structure

Create these pages first:

- Home
- Services
- Projects
- About
- Contact

Optional later pages:

- Individual project pages
- Separate service detail pages
- Testimonials

## Homepage WordPress Mapping

### Header

- `Site Title` or uploaded logo
- `Navigation` block
- button styled as primary CTA

### Hero

- `Cover` block
- eyebrow paragraph
- H1 heading
- supporting paragraph
- two buttons

### Intro

- `Group`
- `Columns`
- heading on left
- paragraph on right

### Services

- `Group`
- section heading
- `Columns` with three service cards

Each card:

- image
- heading
- paragraph
- text link or button

### Process

- `Group` with tinted background
- heading area
- four short steps in columns or stacked groups

### Featured Projects

- `Group`
- intro row
- image-forward project layout using columns

### Values

- `Group` with muted background
- four-column value grid

### Testimonial

- `Quote` block
- attribution paragraph

### About

- `Columns`
- image left
- text right
- button

### Final CTA

- `Group` with dark background
- heading
- body text
- CTA button

### Footer

- business name
- short descriptor
- contact details

## Global Style Settings

Add these into `theme.json` or the Site Editor:

- background color: `#f5f1ea`
- text color: `#2f312d`
- accent color: `#4d5a4a`
- muted background: `#e9e2d8`

Fonts:

- headings: `Cormorant Garamond`
- body: `Source Sans 3`

Spacing:

- section padding desktop: `96px`
- section padding mobile: `64px`
- card gap: `32px`
- text max width: about `720px`

## Editable Content Model

Everything in the design should be easily replaceable by the client or team:

- hero image
- hero headline and supporting copy
- services titles and blurbs
- project images and captions
- testimonial text
- about image and paragraph
- CTA text
- phone and email

## Suggested Minimal Plugins

Install only what is needed:

- SEO plugin
- forms plugin
- image optimization plugin
- backup plugin if host does not include backups

Avoid large page builders if possible.

## Immediate Build Order

1. Install WordPress on low-cost hosting.
2. Activate a lightweight block theme.
3. Set global colors and fonts.
4. Build homepage sections as reusable patterns.
5. Add placeholder images and copy from the prototype.
6. Create basic interior pages.
7. Connect contact form and domain.

## What To Replace First

Before showing the production-ready version to the client, replace:

- stock photography
- phone number
- email
- project names if needed
- testimonial attribution

## Notes

This prototype is intentionally simple so it can work in three ways:

- as a visual concept for Hector
- as a guide for a WordPress build
- as a fallback static version if you want the cheapest possible launch path
