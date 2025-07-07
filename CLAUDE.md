# Gap Tap Support Website

## Project Overview
This is a Jekyll-based support website for Gap Tap, a floor gap fixing tool. The site uses the Minimal Mistakes theme and provides customer support documentation, guides, and contact information.

## Development Commands

### Local Development
```bash
bundle install          # Install Ruby dependencies
bundle exec jekyll serve # Start local development server
```

### Testing & Quality
```bash
bundle exec jekyll build # Build the site
bundle exec htmlproofer _site # Test HTML (if configured)
```

## Site Structure
- `index.md` - Main support page with getting started guide
- `docs/_posts/` - Individual support articles (safety, getting started, suction performance)
- `_includes/` - Custom includes (footer, masthead)
- `_layouts/` - Custom layouts (custom-home)
- `_sass/` - Custom styles
- `assets/` - Images, CSS, and other static assets

## Key Features
- Responsive design with mobile navigation
- Custom home layout with logo
- Support articles organized by topic
- Email contact integration
- Video tutorial embedding

## Customer Support Focus
The site addresses common Gap Tap issues:
- Suction cup performance problems
- Floor compatibility questions
- Safety guidelines
- Proper usage techniques
- Maintenance and care instructions

## Contact Information
- Support Email: support@gap-tap.com
- GitHub Repository: potable-anarchy/support.gap-tap.com
- Live Site: https://support.gap-tap.com (redirects to GitHub Pages)