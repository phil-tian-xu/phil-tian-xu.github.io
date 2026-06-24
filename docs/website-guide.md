# Website Guide

This file is a simple map of the website: what each part does, whether it is currently active, and where to edit it.

## Main Website

| Function | Status | What it does | Main files |
| --- | --- | --- | --- |
| Homepage | Active | Main landing page with profile photo, short bio, research interests, and social links. | `_pages/about.md`, `assets/img/01_body.jpg` |
| CV | Active | Shows the web CV and links to a PDF CV. | `_pages/cv.md`, `_data/cv.yml`, `assets/pdf/example_pdf.pdf` |
| Teaching | Active | Shows course pages, schedules, materials, and optional calendar. | `_pages/teaching.md`, `_teachings/` |
| Social links | Active | Controls email, LinkedIn, CV link, and other social icons. | `_data/socials.yml` |
| Site settings | Active | Controls site title, name, URL, search, dark mode, math, plugins, and global options. | `_config.yml` |

## Optional Sections

These features exist in the theme, but some are currently hidden or still contain sample content.

| Function | Status | What it does | Main files |
| --- | --- | --- | --- |
| Publications | Inactive / archived | Creates a publications page from BibTeX entries. Current bibliography still has demo Einstein entries. | `_pages_archive/publications.md`, `_bibliography/papers.bib`, `_layouts/bib.liquid` |
| Projects | Inactive / archived | Shows project cards and project detail pages. Current project files are mostly demo content. | `_pages_archive/projects.md`, `_projects/` |
| Blog | Inactive / archived | Shows blog posts and technical notes. Current posts are mostly al-folio examples. | `_pages_archive/blog.md`, `_posts/` |
| News | Inactive / archived | Shows announcements/news items. Homepage news is currently disabled. | `_pages_archive/news.md`, `_news/`, `_pages/about.md` |
| Bookshelf | Inactive / archived | Shows book review or bookshelf entries. | `_pages_archive/books.md`, `_books/` |
| People | Inactive / archived | Shows people/lab member profiles. | `_pages_archive/profiles.md`, `_layouts/profiles.liquid` |
| Repositories | Inactive / archived | Shows GitHub users/repositories and repository stats. | `_pages_archive/repositories.md`, `_data/repositories.yml` |

## Homepage Controls

The homepage is controlled mostly by `_pages/about.md`.

| Setting | Current status | Meaning |
| --- | --- | --- |
| `profile.image` | Active | Profile image shown on the homepage. |
| `social: true` | Active | Shows social icons. |
| `selected_papers: false` | Disabled | Hides selected publications on the homepage. |
| `announcements.enabled: false` | Disabled | Hides news on the homepage. |
| `latest_posts.enabled: false` | Disabled | Hides recent blog posts on the homepage. |

## Navigation

Pages appear in the top navigation when their front matter has:

```yaml
nav: true
```

Current active navigation pages:

- `_pages/cv.md`
- `_pages/teaching.md`

Archived pages are stored in `_pages_archive/` and generally have `nav: false`.

## Common Editing Tasks

| Task | Edit this file |
| --- | --- |
| Change short bio | `_pages/about.md` |
| Change profile photo | `assets/img/` and `_pages/about.md` |
| Update CV content | `_data/cv.yml` |
| Change CV page settings | `_pages/cv.md` |
| Replace CV PDF | `assets/pdf/` and `_pages/cv.md` |
| Update email or LinkedIn | `_data/socials.yml` |
| Add a publication | `_bibliography/papers.bib` |
| Add a teaching course | `_teachings/` |
| Add a blog post | `_posts/` |
| Add a project | `_projects/` |
| Change site title or URL | `_config.yml` |
| Enable or disable global features | `_config.yml` |

## Current Cleanup Notes

- `papers.bib` still contains demo Einstein publications.
- `_projects/` still contains demo project pages.
- `_posts/` still contains demo al-folio blog posts.
- `_news/` still contains demo announcements.
- The CV PDF path currently points to `assets/pdf/example_pdf.pdf`.
- `_data/socials.yml` still has a placeholder email.

This file is only a guide. It does not control the website.
