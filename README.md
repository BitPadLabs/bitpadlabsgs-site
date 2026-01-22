# 🎖️ BitPadLabs Government Solutions

Official website for BitPadLabs Government Solutions LLC - a Service-Disabled Veteran-Owned Small Business (SDVOSB) providing federal modernization, DevSecOps, cloud migration, and SAFe training services with a focus on Veterans Affairs contracting.

[![Built with Jekyll](https://img.shields.io/badge/Built_with-Jekyll-red.svg)](https://jekyllrb.com/)
[![Hosted on GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-black.svg)](https://pages.github.com/)
[![SDVOSB](https://img.shields.io/badge/SDVOSB-Certified-blue.svg)](https://bitpadlabsgs.com)

## 🌐 Live Website

[bitpadlabsgs.com](https://bitpadlabsgs.com)

## 🛠️ Tech Stack

- **Framework**: Jekyll (Ruby-based static site generator)
- **CSS**: SCSS with custom design system
- **Hosting**: GitHub Pages
- **Analytics**: Google Analytics

## 🎨 Color Palette

| Element | Color Name | Hex Code | Usage |
|---------|-----------|----------|-------|
| Title | Yellow Gold | #EBCB2A | Primary branding, buttons, accents |
| Subtitle / Heading 1 | Federal Blue | #0C3EA4 | Secondary branding, headings |
| Heading 2 / Normal Text / Primary Button Text / Dark Background | Navy Slate | #172030 | Body text, dark elements |
| Heading 3 / Secondary Text | Sage Gray | #59675B | Supporting text |
| Heading 4 / Warning | Yellow Gold | #EBCB2A | Secondary headings, warnings |
| Heading 5 / Divider / Border | Silver Sage | #ACB8AF | Tertiary headings, borders |
| Light Background / Secondary Button Text | Off White | #FCFCFC | Page backgrounds, light text |
| Secondary Button | Federal Blue | #0C3EA4 | Secondary actions |
| Success | Success Green | #4CAF50 | Success states, confirmations |
| Error | Error Red | #B91C1C | Error states, warnings |

## 🏗️ Local Development

### Prerequisites

- Ruby version 2.5.0 or higher
- RubyGems
- GCC and Make

### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/BitPadLabs/BitPadLabsGS-Site.git
   cd BitPadLabsGS-Site
   ```

2. Install Dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser to see the site.

## 📁 Project Structure

```
BitPadLabsGS-Site/
├── _config.yml         # Jekyll configuration
├── _data/              # Site data (YAML)
│   ├── team.yml        # Team member info
│   └── naics.yml       # NAICS codes
├── _includes/          # Reusable HTML components (header, footer, etc.)
├── _layouts/           # Page templates (default, post, etc.)
├── _posts/             # News posts (Markdown, YYYY-MM-DD-title.md)
├── _sass/              # SCSS partials (variables, base, layout)
├── assets/
│   ├── css/            # Compiled CSS from SCSS
│   ├── images/         # Images, graphics, and logos
│   │   ├── gs-logo.png
│   │   └── team/       # Team member photos
│   └── js/             # JavaScript files
├── .github/
│   └── workflows/      # GitHub Actions workflows
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services by VA use case
├── capabilities.html   # Capabilities page
├── team.html           # Team page
├── news.html           # News listing
├── contact.html        # Contact page
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## 🧩 Adding Content

### News Posts

Create a new Markdown file in the `_posts` directory with the filename format: `YYYY-MM-DD-title.md`

Add the following front matter at the top of the file:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS
author: BPL-GS Team
categories: [category1, category2]
tags: [tag1, tag2]
image: /assets/images/news/your-image.jpg
---
```

Write your post content in Markdown below the front matter. Posts will automatically appear on the news page.

### Team Members

Edit the `_data/team.yml` file following the existing format. Add team member photos to `assets/images/team/` directory.

## 🔄 Deployment

This site is automatically built and deployed using GitHub Pages and GitHub Actions:

1. Any push to the main branch triggers a build
2. GitHub Actions runs the Jekyll build process
3. The built site is deployed to GitHub Pages
4. The site is available at bitpadlabsgs.com

## 📄 License

© 2026 BitPadLabs Government Solutions LLC. All rights reserved.

## 📞 Contact

For any questions or inquiries:

- **Email**: info@bitpadlabsgs.com
- **CAGE Code**: ##
- **UEI**: ##

Last updated: January 21, 2026
