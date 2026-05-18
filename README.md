# Jonathan Moyer Personal Site

Source code for [jonathan-moyer.com](https://jonathan-moyer.com), a lightweight static personal site focused on ecommerce measurement systems, digital transformation, search and discovery, governance, and reporting infrastructure.

## Overview

This is a framework-free static site built with HTML, CSS, local assets, and JSON-LD structured data.

The site is designed to:

- introduce my work across ecommerce analytics, measurement architecture, technical SEO, governance, and reporting systems
- communicate the overlap between growth disciplines, operating environments, and decision-making infrastructure
- provide a simple home for my resume, selected experiments, and professional context

## Stack

- HTML
- CSS
- Local image and PDF assets
- JSON-LD Person schema

## Key Files

- `index.html` — main site content, metadata, semantic structure, and structured data
- `styles.css` — layout, typography, responsive behavior, and section styling
- `jonathan-moyer-resume.pdf` — downloadable resume linked from the site navigation
- `assets/images/` — portrait and core image assets
- `assets/logos/` — brand and organization logos used in the logo strip
- `assets/projects/` — preview images for selected experiments

## Page Structure

- Hero
- Brand strip
- How I Got Here
- Where I Work Best
- Organizational Impact
- Systems for Humans and Machines
- Selected Experiments
- Offline

## Local Preview

Because the site is fully static, it can be previewed directly in a browser or served locally.

### Option 1

Open `index.html` directly in a browser.

### Option 2

Run a local server from the repo root:

```bash
python3 -m http.server 8000
```

Then visit:

[http://localhost:8000](http://localhost:8000)

## Notes

- There is no package manager, bundler, or build pipeline.
- Most updates are content, layout, accessibility, metadata, and asset-tuning changes.
- Logo assets use mixed source formats, so visual consistency is handled through CSS sizing and curated asset replacement.
- The site includes basic social metadata and JSON-LD Person schema.

## Deployment

This repository is intended for GitHub Pages style static hosting.
