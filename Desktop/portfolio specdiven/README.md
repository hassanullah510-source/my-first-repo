# Hassan Ullah — Portfolio

Static single-page portfolio for Hassan Ullah, Full Stack & JavaScript Developer.

## Live

<https://hassanullah510-source.github.io/hassan-portfolio/>

## Projects

| # | Project | Live | Repository |
|---|---------|------|------------|
| 01 | E-Commerce Website | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/e-commerce-website> |
| 02 | Admin Dashboard | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/admin-dashboard> |
| 03 | Full Stack Banking System | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/banking-system> |
| 04 | Task Management App | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/task-management> |
| 05 | Portfolio / CMS | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/portfolio-cms> |
| 06 | Real-Time Chat Application | pending | <https://github.com/hassanullah510-source/hassan-portfolio/tree/main/site/projects/chat-application> |

**Status:** All six links currently show `Link pending` — no dead anchors. URLs are tracked here and in `site/index.html`.

## Editing Workflow

### Add or update a project

1. Open `site/index.html`.
2. Copy one `work-item` block inside the `<ul class="work-list">`.
3. Change the `id` attributes on the `<h3 class="work-title">` and associated elements to be unique.
4. Update the project title, description, and tag list.
5. Replace the `<a href="...">Link pending</a>` in the `.work-meta` div with the live and repo URLs.
6. Update the accent variable `style="--acid: var(--acid)"` if the project uses a different accent.

### Update a link URL

1. Edit the `<a href="...">` inside the relevant `.work-meta` div in `site/index.html`.
2. Update the corresponding entry in `README.md` Projects table.

### Colours (accent variable)

The SIGNAL design system uses the `--acid` CSS custom property. All project rows share the same acid value defined in `:root`. To change the accent for a specific project, add `style="--acid: var(--acid)"` to its `.work-item` div with a custom value from the acid palette (e.g., `--acid: #c6ff00`).

### Colours (text)

Text colour is inherited from `.work-item` styling. No inline colour overrides are needed for body copy.

### New section or page

- Content is static; add markup directly in `site/index.html`.
- No CMS or data-source is required.
- All seven sections (hero, work, about, skills, experience, services, contact) are defined in the spec.

## Open Items

- [x] Replace `Link pending` with real live/demo URLs for all six projects
- [ ] Add project-specific deployment URLs (Vercel/Netlify) if applicable
- [ ] Verify all links resolve or remain explicitly marked pending
- [ ] Run HTML validation (`npx vnu-jar`)
- [ ] Run Lighthouse mobile audits (Perf ≥95, Accy 100, BP ≥95, SEO 100)
- [ ] Deploy to GitHub Pages and confirm live URL

## Credits

Designed and built by Hassan Ullah. SIGNAL design system. Self-hosted fonts (Space Grotesk, JetBrains Mono). No third-party requests at runtime.