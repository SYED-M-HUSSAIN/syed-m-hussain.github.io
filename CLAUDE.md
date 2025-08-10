# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based academic portfolio website built on the Academic Pages theme. It's designed to showcase research, publications, teaching experience, and professional work for academics and researchers.

## Development Commands

### Jekyll Site Commands
```bash
# Install Ruby dependencies
bundle install

# Serve the Jekyll site locally with live reload
bundle exec jekyll serve

# Build the Jekyll site for production
bundle exec jekyll build

# Serve with drafts visible
bundle exec jekyll serve --drafts
```

### JavaScript Build Commands
```bash
# Install Node.js dependencies
npm install

# Build and minify JavaScript assets
npm run build:js

# Watch JavaScript files for changes and auto-rebuild
npm run watch:js
```

## Architecture and Structure

### Core Jekyll Components

**Collections** (_publications/, _portfolio/, _posts/, _talks/, _teaching/):
- Each collection represents a content type with its own layout and display logic
- Front matter in each file controls metadata and display options
- Collections are configured in _config.yml

**Data Files** (_data/):
- `navigation.yml`: Main site navigation structure
- `ui-text.yml`: UI text strings for internationalization
- `authors.yml`: Author information for multi-author sites
- Comments data stored in `_data/comments/` for static comments

**Layouts** (_layouts/):
- `default.html`: Base layout for all pages
- `single.html`: Individual post/page layout
- `archive.html`: Collection and category archive pages
- `talk.html`: Specific layout for talk/presentation pages

**Includes** (_includes/):
- Reusable components like headers, footers, navigation
- Analytics and comment system integrations
- SEO and social sharing components

### Content Management

**Pages** (_pages/):
- Static pages like About, CV, Publications list
- Archive pages for browsing content by category/tag/year
- `talkmap.html`: Interactive map showing talk locations

**Assets**:
- CSS: SASS files in `_sass/`, compiled to `assets/css/main.scss`
- JS: Source files in `assets/js/`, minified to `main.min.js`
- Images and files stored in `images/` and `files/` respectively

### Key Configuration

The site is configured through `_config.yml` which controls:
- Site metadata and author information
- Social media links and academic profiles
- Jekyll plugins and build settings
- Collection definitions and permalinks
- Comment system configuration (Disqus/Staticman)

### Markdown Generator

The `markdown_generator/` directory contains Python scripts to convert publication and talk data from TSV/BibTeX formats into Jekyll-compatible markdown files.

## Deployment

This site is designed for GitHub Pages deployment:
- Push changes to the repository's main branch
- GitHub Pages will automatically build and deploy using Jekyll
- Custom domain can be configured through GitHub repository settings

## Important Notes

- When editing content, preserve the front matter structure in markdown files
- JavaScript changes require rebuilding with `npm run build:js`
- Test locally with `bundle exec jekyll serve` before pushing changes
- The site uses the github-pages gem to ensure compatibility with GitHub Pages environment