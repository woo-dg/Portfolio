# Portfolio

Personal portfolio website for Dave Grewal.

**Live site:** [Your GitHub Pages URL]

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- Markdown content
- GitHub Pages hosting

## Development

```bash
# Serve locally
cd docs
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Structure

- `docs/index.html` - Main page
- `docs/*.md` - Content (about, projects)
- `docs/styles.css` - Styling
- `docs/script.js` - Functionality
- `docs/assets/` - Images and PDFs

## Deployment

This site is set up for GitHub Pages. The `docs/` folder contains all the files needed.

To deploy:
1. Push this repository to GitHub
2. Go to Settings > Pages
3. Set source to `docs/` folder
4. Your site will be live at `https://[username].github.io/[repo-name]`

Inspired by [astro-theme-cactus](https://astro-cactus.chriswilliams.dev/) :)
