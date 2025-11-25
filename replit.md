# Sentieri di Libertà

**Personal Portfolio Website for Martina**  
*Explorer, Storyteller, Freedom Lover*

## Overview

This is a static HTML portfolio website showcasing Martina's travel experiences and stories. The site was imported from a GitHub repository and has been configured to run on Replit.

## Project Structure

```
.
├── public/              # Web-accessible directory
│   ├── index.html      # Main homepage (Sentieri di libertà)
│   ├── trip.html       # "A Trip With Me" page
│   ├── cities.html     # Cities destinations
│   ├── cv.html         # Curriculum Vitae
│   ├── lakes.html      # Lakes destinations
│   ├── mountains.html  # Mountains destinations
│   ├── sea-beach.html  # Sea and Beach destinations
│   └── contact.html    # Contact page
├── README.md
└── replit.md
```

## Recent Changes (November 24, 2025)

### Initial Setup
- **Reorganized file structure**: Created `public/` directory to hold all HTML files
- **Normalized filenames**: Renamed HTML files from Italian names with spaces to URL-friendly names
  - `Sentieri di libertà.html` → `index.html`
  - `A Trip With Me - Sentieri di libertà.html` → `trip.html`
  - And similar for all other pages
- **Updated internal links**: Converted all absolute GitHub Pages URLs to relative paths for local serving
- **Configured workflow**: Set up Python HTTP server to serve static files on port 5000
- **Configured deployment**: Set deployment type to static with `public` as the public directory

## Technology Stack

- **Frontend**: Pure HTML5 with inline CSS (no frameworks)
- **Server**: Python 3.11 built-in HTTP server for development
- **Deployment**: Static site hosting

## Workflow

The site runs a single workflow:
- **Static Web Server**: Serves the `public/` directory on port 5000 using Python's built-in HTTP server

## Known Issues

- **Missing Images**: The original GitHub export did not include image assets. The HTML references images that are not present in the repository:
  - `Logo.jpg` (site logo)
  - Various travel photos
  
  These need to be added to the `public/` directory to display properly. The site functions without them but is missing visual content.

## Development

To modify the site:
1. Edit HTML files in the `public/` directory
2. The workflow will automatically serve the updated files
3. Refresh your browser to see changes

## Deployment

The site is configured for static deployment. When you publish:
- Deployment type: Static
- Public directory: `public/`
- All HTML files will be served from the `public/` directory

## Pages

- **Home** (`index.html`): Main landing page with about section
- **A Trip With Me** (`trip.html`): Personalized travel experiences
- **Destinations**: 
  - Mountains (`mountains.html`)
  - Sea & Beach (`sea-beach.html`)
  - Cities (`cities.html`)
  - Lakes (`lakes.html`)
- **Curriculum Vitae** (`cv.html`): Professional background
- **Contact** (`contact.html`): Contact form/information

## Notes

- All navigation uses relative paths
- The site is designed with a responsive layout
- Pink/coral gradient background theme throughout
- No external dependencies or build process required
