# Abdulmalik Ajisegiri Portfolio Website

## Overview
This is a personal portfolio website for Abdulmalik Ajisegiri, a Model Risk Engineer and AI/ML Specialist. The site showcases professional projects, technical skills, work experience, and contact information with modern animations and a clean design.

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
- **Complete portfolio customization for Abdulmalik Ajisegiri**:
  - Updated personal information (name, contact, social media links)
  - Rewrote About section to reflect Model Risk Engineer background
  - Replaced Skills section with AI/ML, Risk Analytics, and Systems Engineering tech stack
  - Updated Projects section with GenAI Risk-Bench, Metaheuristic Search Framework, RF Command Test Harness, and NIST CSF projects
  - Updated all meta tags and SEO information
  - Removed original developer's Google Analytics and Ko-fi widget
  - Updated resume PDF link to Abdulmalik-Ajisegiri-Resume.pdf
  - Updated footer and console messages
  - Updated README.md with new information

## Developer Notes
- The website uses CDN-hosted libraries (AOS, Google Fonts)
- No build step required - direct file serving
- Custom animations and interactions are all vanilla JavaScript
- Mobile-responsive with hamburger menu
- Resume PDF located at: src/pdf/Abdulmalik-Ajisegiri-Resume.pdf
- Contact: abdulmalikajisegiri@gmail.com
- LinkedIn: https://www.linkedin.com/in/malikajisegiri
- GitHub: https://github.com/Maleek23

## Next Steps (Optional Customization)
- **Add Personal Photos**: Replace emoji placeholders with actual photos:
  - Navbar logo: Update the briefcase emoji (💼) in line 70 of index.html
  - About section photo: Replace the developer emoji (👨‍💻) in the About section
  - Footer avatar: Replace the target emoji (🎯) in the footer
  - Recommended to add images to `src/png/` or `src/webp/` directories
- **Add Project Screenshots**: Replace gradient placeholders in Projects section with actual project images
- **Customize Colors**: Modify color scheme in style.css if desired
