# Portfolio Website

A simple, clean portfolio website for a writer and musician, built with Jekyll and hosted on GitHub Pages.

## Setup for GitHub Pages

1. Push this repository to GitHub
2. Go to Settings > Pages in your GitHub repository
3. Select the main branch as the source
4. Your site will be available at `https://[your-username].github.io/[repository-name]`

## Local Development

To preview the site locally:

1. Install Jekyll: `gem install bundler jekyll`
2. Run: `bundle install` (if you add a Gemfile) or just `jekyll serve`
3. Visit: `http://localhost:4000`

## Editing Content

### Update Navigation Menu
Edit `_includes/nav.html` - changes will appear on all pages.

### Update Header/Footer
- Header: `_includes/header.html`
- Footer: `_includes/footer.html`

### Edit Pages
- Homepage: `index.html`
- About: `about.html`
- Contact: `contact.html` (update email/phone)
- Music: `music.html` (add your music links)
- Writing: `writing.html` (add your writing links)

### Add Your Photo
1. Add your photo to the `images/` folder
2. Name it `photo.jpg` (or update the filename in `index.html`)

### Customize Colors/Fonts
Edit `css/main.css` - look for the `:root` section at the top to change colors and fonts easily.

## File Structure

```
├── _config.yml          # Jekyll configuration
├── _includes/           # Reusable components (header, nav, footer)
├── _layouts/            # Page templates
├── css/                 # Stylesheets
├── images/              # Images (add your photo here)
├── index.html           # Homepage
├── about.html           # About page
├── contact.html         # Contact page
├── music.html           # Music page
└── writing.html         # Writing page
```

## Tips

- All pages use the same layout, so navigation updates automatically
- The site is mobile-responsive by default
- Keep it simple - edit the HTML files directly, no build step needed for basic changes
