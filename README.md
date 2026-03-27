# Chetan Mishra Portfolio Website

A personal portfolio website built with HTML, CSS, JavaScript, Bootstrap, and jQuery plugins.

## Overview

This project is a static, single-page portfolio site with sections for:

- Home (hero banner + typing animation)
- About (bio, profile details, skills with progress bars)
- Resume (experience and education)
- Projects (GitHub project cards)
- Contact (contact details + social links)

The base layout and component structure are adapted from a Colorlib template and then customized with personal content, links, and visuals.

## Tech Stack

- HTML5
- CSS3 / SCSS
- Bootstrap 4
- JavaScript (vanilla + jQuery)
- Owl Carousel
- AOS (Animate On Scroll)
- Magnific Popup
- Waypoints + AnimateNumber + Scrollax

## Project Structure

- `index.html`: Main single-page site and inline custom styles/scripts.
- `css/`: Compiled CSS assets (theme, animation, icons, plugin styles).
- `js/`: Main JavaScript and plugin scripts used by the page.
- `images/`: Images used across hero/about/projects/backgrounds.
- `scss/`: SCSS source files (including Bootstrap partials).
- `fonts/`: Icon and font files.
- `lib/`: Vendor library copies.

## Run Locally

Because this is a static site, you can run it in either of these ways:

1. Open `index.html` directly in a browser.
2. Serve it with a lightweight local server (recommended):

```bash
# Python 3
python -m http.server 5500
```

Then open: `http://localhost:5500`

## Customization Guide

- Update personal information in `index.html` (name, bio, skills, links).
- Replace portfolio images in `images/` and keep filenames in sync.
- Edit theme styling in `css/style.css` or source SCSS in `scss/style.scss`.
- Modify interactive behavior in `js/main.js`.
- Update project cards and external links in the Projects section of `index.html`.

## Deployment

This repository is suitable for GitHub Pages hosting.

If this repo is the Pages source, pushing changes to the configured branch (commonly `main`) will publish the latest version.

## License

- Project includes a `LICENSE` file.
- Template attribution in the footer references Colorlib; keep attribution/license compliance based on template terms.

## Git Note (Important)

If Git shows a path with mode `160000`, it means a nested Git repository (submodule-like entry) was committed instead of normal files.

To commit this website as regular files in the parent repo, remove the nested `.git` inside this folder and re-add files from the parent repository.
