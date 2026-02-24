# Directory Structure Guide

Complete file structure for your Minimal Mistakes workshop website:

```
your-workshop-site/
│
├── _config.yml                    # Main site configuration
├── Gemfile                        # Ruby dependencies
├── README.md                      # Documentation
├── index.md                       # Homepage (splash layout)
│
├── _data/
│   └── navigation.yml            # Site navigation menus
│
├── _pages/                        # Static pages
│   ├── workshops.md              # Current workshops listing
│   ├── resources.md              # Learning resources
│   ├── archive.md                # Workshop archive
│   └── about.md                  # About page
│
├── _workshops/                    # Workshop collection (auto-generates pages)
│   ├── qgis-february-2026.md
│   ├── tableau-february-2026.md
│   └── [future-workshop].md
│
├── _tutorials/                    # Tutorial collection (for your custom tutorials)
│   └── [your-tutorials].md
│
├── assets/
│   ├── images/                   # All site images
│   │   ├── splash-header.jpg     # Homepage hero image
│   │   ├── logo.png              # Site logo (optional)
│   │   ├── bio-photo.jpg         # Author photo (optional)
│   │   ├── qgis-thumbnail.jpg    # QGIS feature box image
│   │   ├── qgis-header.jpg       # QGIS workshop header
│   │   ├── tableau-thumbnail.jpg # Tableau feature box image
│   │   ├── tableau-header.jpg    # Tableau workshop header
│   │   └── resources-thumbnail.jpg # Resources feature box
│   │
│   ├── css/                      # Custom CSS (optional)
│   │   └── main.scss
│   │
│   └── js/                       # Custom JavaScript (optional)
│       └── custom.js
│
├── _includes/                     # Custom includes (optional overrides)
│   └── [minimal-mistakes-overrides]
│
├── _layouts/                      # Custom layouts (optional overrides)
│   └── [minimal-mistakes-overrides]
│
├── _sass/                         # Custom Sass (optional)
│   └── [custom-styles].scss
│
└── .gitignore                     # Git ignore file

```

## Required Files

You MUST have these files:
1. `_config.yml` - Site configuration
2. `index.md` - Homepage
3. `_data/navigation.yml` - Navigation menu
4. `Gemfile` - Ruby dependencies

## Collections Folders

Create these folders for collections:
- `_workshops/` - Individual workshop pages
- `_tutorials/` - Your custom tutorial content
- `_pages/` - Static pages (about, resources, etc.)

## Assets Folder

Create `assets/images/` and add your images:
- Homepage splash image
- Workshop thumbnails and headers
- Logo and bio photo (optional)

## What You'll Need to Add

### 1. Images
Add these images to `assets/images/`:
- `splash-header.jpg` (2048x1024px recommended)
- `qgis-thumbnail.jpg` (600x400px)
- `qgis-header.jpg` (2048x1024px)
- `tableau-thumbnail.jpg` (600x400px)
- `tableau-header.jpg` (2048x1024px)
- `resources-thumbnail.jpg` (600x400px)

### 2. Personalization
Update in `_config.yml`:
- Your name
- Your email
- Your GitHub username
- Site title and description
- Social media links

### 3. Workshop Data Repositories
Create separate GitHub repos for workshop data:
- `qgis-workshop-data`
- `tableau-workshop-data`

Update download links in workshop pages to point to these repos.

## Optional Customizations

### Custom CSS
Create `assets/css/main.scss`:
```scss
---
---

@import "minimal-mistakes/skins/{{ site.minimal_mistakes_skin | default: 'default' }}";
@import "minimal-mistakes";

// Your custom CSS here
```

### Custom JavaScript
Create `assets/js/custom.js` for any custom functionality.

### Override Layouts
Copy layouts from Minimal Mistakes to `_layouts/` and customize them.

## GitHub Pages Setup

1. Create a repository named:
   - `yourusername.github.io` (for user/org site), OR
   - `any-name` (for project site)

2. Push all files to the repository

3. Enable GitHub Pages in repository settings:
   - Settings > Pages
   - Source: main branch
   - Save

4. Site will be available at:
   - User site: `https://yourusername.github.io`
   - Project site: `https://yourusername.github.io/repository-name`

## Next Steps

1. Create the directory structure shown above
2. Copy the configuration files I've provided
3. Add your images to `assets/images/`
4. Customize `_config.yml` with your information
5. Test locally with `bundle exec jekyll serve`
6. Deploy to GitHub Pages

## Tips

- Keep image file sizes reasonable (compress before uploading)
- Use consistent naming conventions
- Test all links before deploying
- Keep workshop materials in separate data repositories
- Update archive regularly after workshops
- Back up your content

## Questions?

Refer to:
- README.md for detailed setup instructions
- [Minimal Mistakes Docs](https://mmistakes.github.io/minimal-mistakes/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
