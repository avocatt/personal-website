# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal portfolio website for Emre Terzi, showcasing software development projects including AI/RAG applications, mobile apps, and desktop software. The site is built with vanilla HTML/CSS and designed with a clean, minimal aesthetic.

## Development Workflow

### Local Development
```bash
# Open the website locally
open index.html
# Or serve with any static server
python -m http.server 8000
```

### Deployment
This is a static website that can be deployed to:
- GitHub Pages
- Netlify  
- Vercel
- Any static hosting service

Simply upload the HTML file to any web server.

## Architecture

### File Structure
- `index.html` - Single-page portfolio with embedded CSS
- `README.md` - Project documentation

### Design System
- **Typography**: Inter font from Google Fonts (400, 500 weights)
- **Color Scheme**: Minimal grayscale (#1a1a1a, #666, #999, #fafafa)
- **Layout**: Single-column, max-width 720px, mobile-first responsive design
- **Styling**: All CSS embedded in HTML head, no external stylesheets

### Content Structure
1. **Header** - Name and bio
2. **Projects Section** - Featured portfolio items with:
   - Project title and tech stack
   - Description
   - Demo and source links
3. **Footer** - Contact links (GitHub, LinkedIn, Email)

### Current Projects Featured
- TBK Rental Law Assistant (Python, FastAPI, RAG)
- CMK Checklist (React Native, TypeScript) 
- Jewelry Inventory (React, Firebase, TypeScript)
- KuyumPro (Electron, React, SQLite)

## Notes for Future Development

- Site uses placeholder URLs for some project links that need to be updated
- GitHub username links need to be updated from "yourusername" placeholders
- Email contact uses mailto placeholder that needs real email
- No build process - changes can be made directly to index.html
- Responsive breakpoint at 640px for mobile layout