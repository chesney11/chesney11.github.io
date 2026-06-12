# Chesney's Data Analytics Portfolio

A professional portfolio website showcasing data analytics projects and full-stack development work.

## Features

✨ **Aesthetic Design** - Neutral color palette with browns, nudes, and sage greens
📊 **Projects Showcase** - Dedicated section for data analytics work
📓 **Jupyter Integration** - Links to notebooks and detailed analysis
🎨 **Responsive** - Mobile-friendly design
⚡ **Fast** - Built with Jekyll for static site generation

## Color Palette

- **Primary Brown**: #8B7355
- **Dark Brown**: #5C4033
- **Light Brown**: #D2B48C
- **Nude**: #E8D5C4
- **Sage Green**: #9CAF88
- **Cream**: #FFFAF0

## Local Development

### Prerequisites
- Ruby 2.7+
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## Structure

```
.
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Main layout template
├── _projects/            # Project collection
│   ├── template-project-1.md
│   └── template-project-2.md
├── assets/
│   └── css/
│       └── custom.css    # Custom styling
├── index.md              # Homepage
├── projects.md           # Projects page
└── README.md             # This file
```

## Adding Projects

1. Create a new file in `_projects/` named `your-project-name.md`
2. Use this frontmatter template:

```yaml
---
title: "Project Title"
excerpt: "Short description of your project"
tags: ["Tag1", "Tag2", "Tag3"]
github_url: "https://github.com/..."
notebook_url: "https://nbviewer.jupyter.org/..."
---

## Overview
Project description and details...
```

3. Commit and push—GitHub Pages will automatically rebuild

## Customization

### Update Your Info
Edit `_config.yml` to update:
- Site title and description
- Author name and links
- GitHub/LinkedIn URLs

### Modify Colors
Edit `assets/css/custom.css` CSS variables:
```css
:root {
  --primary-brown: #8B7355;
  --sage-green: #9CAF88;
  /* etc... */
}
```

### Update Homepage
Edit `index.md` to customize:
- About section
- Skills list
- Personal statement

## Deployment

The site is automatically deployed to GitHub Pages whenever you push to the `main` branch.

**Live Site**: https://chesney11.github.io

## Resources

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages](https://pages.github.com/)
- [Minima Theme](https://github.com/jekyll/minima)

## License

MIT License - Feel free to use this template for your own portfolio.
