# Vinod Jangid Portfolio Website

## Overview
This is a personal portfolio website for Vinod Jangid, a web developer and digital visual artist. The site showcases projects, skills, experience, and contact information with modern animations and a clean design.

## Project Type
- **Frontend**: Static HTML/CSS/JavaScript website
- **No Backend**: Pure client-side application
- **No Build Process**: Vanilla web technologies, no bundler required

## Technology Stack
- **HTML5**: Structure and content
- **CSS3**: Styling with custom animations
- **Vanilla JavaScript**: Interactive features and animations
- **External Libraries**:
  - AOS (Animate On Scroll) - for scroll animations
  - Google Fonts - custom typography

## Project Structure
```
├── index.html          # Main HTML file
├── style.css          # Main stylesheet
├── main.js            # JavaScript functionality
├── server.js          # Node.js HTTP server for Replit
├── src/               # Assets directory
│   ├── png/          # PNG images (logos, icons, photos)
│   ├── webp/         # WebP images (project previews)
│   ├── svg/          # SVG graphics
│   ├── ico/          # Favicon files
│   ├── mp3/          # Audio files
│   └── pdf/          # Resume PDFs
└── Formatted code/    # Formatted versions of CSS/JS
```

## Features
- Responsive design for all devices
- Dark/Light mode toggle
- Custom cursor animation
- Scroll-triggered animations (AOS library)
- Audio controls
- Interactive navigation
- Project showcase section
- Skills display
- Contact information
- Resume download

## Setup for Replit
- **Server**: Simple Node.js HTTP server (server.js)
- **Port**: 5000
- **Host**: 0.0.0.0 (required for Replit preview)
- **Cache Control**: Disabled for development

## Current Status
- ✅ Server running on port 5000
- ✅ Website fully functional
- ✅ All assets loading correctly
- ✅ Animations working
- ✅ Responsive design active

## Recent Changes (October 19, 2025)
- Initial Replit setup
- Created Node.js server to serve static files
- Configured workflow for automatic server startup
- Added .gitignore for Replit-specific files
- Documented project structure in replit.md

## Developer Notes
- The website uses CDN-hosted libraries (AOS, Google Fonts)
- No build step required - direct file serving
- Custom animations and interactions are all vanilla JavaScript
- Mobile-responsive with hamburger menu
- Includes Google Analytics (should be updated if forking)
