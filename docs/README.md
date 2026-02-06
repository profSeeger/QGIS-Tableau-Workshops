# Workshop Website

A Jekyll-based website using the Minimal Mistakes theme for hosting workshop materials, tutorials, and resources for QGIS, Tableau, and other geospatial/data visualization technologies.

## Features

- **Workshop Pages**: Detailed pages for each workshop with installation guides, agendas, and data downloads
- **Resource Library**: Curated external tutorials and learning resources
- **Workshop Archive**: Historical workshop materials and datasets
- **Responsive Design**: Mobile-friendly layout using Minimal Mistakes theme
- **Collections**: Organized workshops and tutorials using Jekyll collections

## Site Structure

```
.
├── _config.yml                 # Main Jekyll configuration
├── _data/
│   └── navigation.yml         # Site navigation menus
├── _pages/
│   ├── workshops.md           # Current workshops landing page
│   ├── resources.md           # Learning resources page
│   ├── archive.md             # Past workshops archive
│   └── about.md               # About page
├── _workshops/
│   ├── qgis-february-2026.md     # Individual workshop pages
│   └── tableau-february-2026.md
├── _tutorials/                # Future tutorial content
├── assets/
│   └── images/                # Site images, headers, thumbnails
└── index.md                   # Homepage with splash layout
```

## Setup Instructions

### Prerequisites

- Git
- Ruby 2.7 or higher
- Bundler

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Serve the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View in browser**
   Navigate to `http://localhost:4000`

### Deploy to GitHub Pages

1. **Update _config.yml**
   - Set `url` to your GitHub Pages URL
   - Set `repository` to your GitHub username/repo-name
   - If using a project site (not username.github.io), set `baseurl` to "/repository-name"

2. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial site setup"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Set source to "main" branch
   - Site will be published at `https://yourusername.github.io/repository-name`

## Customization Guide

### Update Site Information

Edit `_config.yml`:
```yaml
title: "Your Workshop Title"
name: "Your Name"
description: "Your description"
url: "https://yourusername.github.io"
author:
  name: "Your Name"
  email: "your.email@example.com"
```

### Add Your Images

Add images to `assets/images/`:
- `splash-header.jpg` - Homepage hero image (recommended: 2048x1024px)
- `qgis-thumbnail.jpg` - QGIS feature box (recommended: 600x400px)
- `tableau-thumbnail.jpg` - Tableau feature box (recommended: 600x400px)
- `qgis-header.jpg` - QGIS workshop page header (recommended: 2048x1024px)
- `tableau-header.jpg` - Tableau workshop page header (recommended: 2048x1024px)

### Change Theme Colors

Edit `_config.yml`:
```yaml
minimal_mistakes_skin: "default"  # Options: "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"
```

### Add a New Workshop

1. Create a new file in `_workshops/` (e.g., `python-march-2026.md`)
2. Use this front matter template:
   ```yaml
   ---
   title: "Workshop Title - Date"
   excerpt: "Brief description"
   date: 2026-03-15
   workshop_date: "March 15, 2026"
   software: "Python"
   status: "upcoming"
   level: "Beginner"
   duration: "Full day"
   ---
   ```
3. Add your content using the existing workshop files as templates
4. Update `_pages/workshops.md` to add a link to the new workshop

### Update Navigation

Edit `_data/navigation.yml` to modify menu items:
```yaml
main:
  - title: "New Page"
    url: /new-page/
```

### Add Tutorial Content

1. Create markdown files in `_tutorials/`
2. Use front matter similar to workshops
3. Files will automatically be available at `/tutorials/filename/`

## Workshop Data Repository

Each workshop should have an accompanying GitHub repository with data:
1. Create a separate repo (e.g., `qgis-workshop-data`)
2. Add datasets, example files, and completed exercises
3. Link to the repo in workshop pages using the download buttons

## Updating Content

### Regular Updates

1. Update workshop pages before each session
2. Add new entries to the archive after workshops
3. Keep resources page current with new links
4. Add your custom tutorials as you create them

### Moving Workshops to Archive

After a workshop concludes:
1. Copy the workshop page content to `_pages/archive.md`
2. Update the workshop status from "upcoming" to "past"
3. Ensure all materials are linked in the archive entry

## Troubleshooting

### Build Errors

If you see build errors:
```bash
bundle update
bundle exec jekyll clean
bundle exec jekyll serve
```

### Images Not Displaying

- Check file paths are correct (case-sensitive)
- Ensure images are in `assets/images/`
- Verify image references in markdown don't include `baseurl` (Jekyll handles this)

### Navigation Not Working

- Ensure `_data/navigation.yml` has correct formatting
- Check that URLs match page permalinks exactly
- Remember leading slashes: `/workshops/` not `workshops/`

## Additional Resources

- [Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

## Support

Questions or issues? [Open an issue](https://github.com/yourusername/your-repo-name/issues) or email [your.email@example.com](mailto:your.email@example.com).

## License

Content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
Code is licensed under the MIT License.
