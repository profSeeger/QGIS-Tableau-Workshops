# Quick Setup Checklist

Use this checklist to set up your workshop website step-by-step.

## Initial Setup

- [ ] Install Ruby (version 2.7 or higher)
- [ ] Install Bundler: `gem install bundler`
- [ ] Create GitHub account (if you don't have one)
- [ ] Create new repository on GitHub

## File Setup

- [ ] Copy all provided files to your local folder
- [ ] Create `assets/images/` folder
- [ ] Create `_data/` folder (if not exists)
- [ ] Create `_pages/` folder (if not exists)
- [ ] Create `_workshops/` folder (if not exists)
- [ ] Create `_tutorials/` folder (if not exists)

## Customization

### _config.yml
- [ ] Update `title` with your workshop title
- [ ] Update `name` with your name
- [ ] Update `description`
- [ ] Update `url` to your GitHub Pages URL
- [ ] Update `repository` to yourusername/repo-name
- [ ] Update `baseurl` (empty for user site, "/repo-name" for project site)
- [ ] Update author `name`
- [ ] Update author `email`
- [ ] Update author `bio`
- [ ] Update author `location`
- [ ] Add your GitHub username in author links
- [ ] Choose your `minimal_mistakes_skin` color theme

### Navigation
- [ ] Review `_data/navigation.yml`
- [ ] Customize menu items if needed

### Homepage (index.md)
- [ ] Update feature_row excerpts
- [ ] Update workshop URLs when you add more workshops
- [ ] Customize intro text

### Workshop Pages
- [ ] Update QGIS workshop with your details
  - [ ] Set correct workshop date
  - [ ] Update instructor name
  - [ ] Update GitHub data repository URLs
  - [ ] Customize agenda to your needs
  - [ ] Update contact email
- [ ] Update Tableau workshop with your details
  - [ ] Set correct workshop date
  - [ ] Update instructor name
  - [ ] Update GitHub data repository URLs
  - [ ] Customize agenda to your needs
  - [ ] Update contact email

### Other Pages
- [ ] Customize About page with your background
- [ ] Update Resources page (add/remove links as needed)
- [ ] Update Archive page with your past workshops
- [ ] Replace placeholder workshop archive entries

## Images

- [ ] Create or find splash-header.jpg (2048x1024px)
- [ ] Create or find qgis-thumbnail.jpg (600x400px)
- [ ] Create or find qgis-header.jpg (2048x1024px)
- [ ] Create or find tableau-thumbnail.jpg (600x400px)
- [ ] Create or find tableau-header.jpg (2048x1024px)
- [ ] Create or find resources-thumbnail.jpg (600x400px)
- [ ] Add logo.png (optional)
- [ ] Add bio-photo.jpg (optional)
- [ ] Add all images to `assets/images/`

## Workshop Data Repositories

- [ ] Create separate GitHub repo for QGIS workshop data
- [ ] Create separate GitHub repo for Tableau workshop data
- [ ] Upload sample datasets to each repo
- [ ] Update download URLs in workshop pages

## Testing Locally

- [ ] Run `bundle install`
- [ ] Run `bundle exec jekyll serve`
- [ ] Open http://localhost:4000 in browser
- [ ] Test all navigation links
- [ ] Test all internal page links
- [ ] Check images load correctly
- [ ] Review mobile responsiveness
- [ ] Fix any errors or broken links

## Deploy to GitHub

- [ ] Initialize git: `git init`
- [ ] Add files: `git add .`
- [ ] Commit: `git commit -m "Initial site setup"`
- [ ] Add remote: `git remote add origin https://github.com/yourusername/repo-name.git`
- [ ] Push: `git push -u origin main`

## GitHub Pages Configuration

- [ ] Go to repository Settings
- [ ] Click Pages in sidebar
- [ ] Set Source to "main" branch
- [ ] Click Save
- [ ] Wait for site to build (check Actions tab)
- [ ] Visit your site URL
- [ ] Test everything again on live site

## Post-Launch

- [ ] Share workshop site URL
- [ ] Test registration/contact forms (if added)
- [ ] Set up analytics (optional)
- [ ] Create social media graphics
- [ ] Promote upcoming workshops

## Before Each Workshop

- [ ] Update workshop page with final details
- [ ] Test all download links
- [ ] Verify software installation instructions are current
- [ ] Update agenda if needed
- [ ] Send reminder email with site link

## After Each Workshop

- [ ] Add workshop to archive page
- [ ] Upload workshop materials (slides, data, solutions)
- [ ] Change workshop status from "upcoming" to "past"
- [ ] Update homepage to remove completed workshop
- [ ] Gather feedback for improvements

## Ongoing Maintenance

- [ ] Update external resource links periodically
- [ ] Add new tutorials to Resources page
- [ ] Create custom tutorials in _tutorials/
- [ ] Check for broken links quarterly
- [ ] Update software version numbers in guides
- [ ] Keep archive organized

## Troubleshooting

If something doesn't work:
- [ ] Check Jekyll build errors in terminal
- [ ] Review GitHub Pages build logs (Actions tab)
- [ ] Verify file paths are correct (case-sensitive!)
- [ ] Check YAML front matter formatting
- [ ] Ensure all required files exist
- [ ] Clear Jekyll cache: `bundle exec jekyll clean`
- [ ] Rebuild: `bundle exec jekyll serve`

## Resources

- Minimal Mistakes docs: https://mmistakes.github.io/minimal-mistakes/
- Jekyll docs: https://jekyllrb.com/docs/
- GitHub Pages docs: https://docs.github.com/en/pages
- Markdown guide: https://www.markdownguide.org/

## Need Help?

- Review README.md for detailed instructions
- Check STRUCTURE.md for file organization
- Refer to existing workshop pages as templates
- Search Minimal Mistakes documentation
- Ask in Jekyll/GitHub Pages communities
