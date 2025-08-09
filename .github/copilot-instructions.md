# Copilot Instructions for Laura Martínez Ortega – Psicología Online Website

## Project Overview
This is a static website for a professional psychologist, built with plain HTML and CSS, and hosted on GitHub Pages. The site is designed to be responsive, accessible, and easy to update. There is no build process, backend, or JavaScript framework—just static assets.

## Key Files & Structure
- `index.html`: Main landing page. All primary content, layout, and navigation are here.
- `404.html`: Custom error page for not found routes.
- `aviso-legal.html`, `privacidad.html`, `cookies.html`: Legal compliance pages (templates, editable).
- `images/`: Contains all static images (logo, icons, etc). Use relative paths (e.g., `images/Logo.svg`).
- `.github/copilot-instructions.md`: (this file) AI agent guidance.
- `CNAME`: Contains the custom domain for GitHub Pages (if present).

## Editing & Deployment Workflow
- **Edit content directly in HTML files.** No templating or build step is used.
- **Images:** Add new images to `images/` and reference with relative paths.
- **Legal pages:** Update legal text in their respective HTML files.
- **Commit to `main` branch.** GitHub Pages will auto-deploy within minutes.
- **No npm, package.json, or build tools.**

## Conventions & Patterns
- **Responsive design:** Uses CSS flexbox and media queries. See `.sobre-mi-flex`, `.contact-cards`, and header/footer for layout patterns.
- **Navigation:** Hamburger menu for mobile is implemented with a small JS snippet in `index.html`.
- **Contact links:** WhatsApp uses wa.link for privacy; email is a mailto link with the custom domain.
- **Image placeholders:** If a professional photo is not available, use a styled `<div>` as a placeholder (see `.sobre-mi-img`).
- **Legal compliance:** All legal pages must be linked in the footer and kept up to date.
- **404 handling:** Custom `404.html` is required for GitHub Pages routing.

## External Integrations
- **GitHub Pages:** Site is published from the `main` branch. Custom domain is set via `CNAME` and DNS.
- **No analytics, forms, or third-party scripts** are present by default.

## Examples
- To add a new service, edit the `<ul>` in the `#servicios` section of `index.html`.
- To update contact info, change the relevant `<a>` tags in the `#contacto` section.
- To add a new image, place it in `images/` and reference it with `<img src="images/yourfile.png">`.

## What NOT to do
- Do not add build tools, frameworks, or package managers.
- Do not use absolute paths for images or links—always use relative paths.
- Do not remove or break legal compliance links in the footer.

## For AI Agents
- Always preserve the responsive and accessible design.
- When in doubt, follow the structure and style of existing sections.
- If updating navigation or layout, test on both desktop and mobile breakpoints.
- Reference this file and `README.md` for project context.

---
If any conventions or workflows are unclear, ask for clarification or check with the project maintainer.
