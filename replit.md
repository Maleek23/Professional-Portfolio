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

## UI/UX Improvements (October 19, 2025)
- **Darker/Futuristic Color Scheme**:
  - Background: #0a0a0f (darker black)
  - Accent colors: #00d4ff (cyan), #9d4edd (purple)
  - Enhanced visual hierarchy with cyan glow effects
- **Optimized Image Sizing**:
  - Navbar avatar: 50×50px circular with cyan glow
  - About section photo: 280×280px with soft shadow
  - Footer avatar: 180×180px circular with cyan glow
- **Section IDs added**: Certifications and Honors sections now have anchor links
- **Professional Tech Stack Logos**: 
  - Replaced all emoji icons with transparent PNG logos for 13 technologies
  - Custom generated logos: Python, MATLAB, SQL, TypeScript, PyTorch, TensorFlow, Hugging Face, LangChain, Tableau, Power BI, AWS, Docker, Jupyter
  - All logos stored in src/png/ directory
- **Illuminating Glow Effects**:
  - Tech stack boxes: Multi-layer cyan/purple glow with hover amplification
  - Name heading: Animated pulsing glow effect
  - Section headings: Triple-layer text shadow glow
  - Project cards: Glowing borders with hover effects
  - All avatars: Enhanced cyan glow halos
  - Buttons: Illuminating glow on hover
  - Social icons: Drop-shadow glow effects
  - Navigation: Active link glow indicators
  - Back to top button: Glowing effect

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
- **LinkedIn Profile Integration (October 19, 2025)**:
  - Added personal photo (malik-photo.jpg) to About section and footer
  - Added custom avatar (nav-avatar.png) to navbar
  - Added phone number (346) 297-8021 to footer contact section
  - Updated About section with compelling LinkedIn summary intro
  - Added new Certifications section (CISA, MATLAB Certified, Bloomberg Market Concepts, Simulink Onramp)
  - Added Honors & Awards section (Maverick Academic CSE Scholarship, Next Gen Leaders Scholarship)
  - Added Pareto.AI Financial Engineer project card (DCF/LBO modeling for LLM training)
  - Integrated current roles: DTCC Model Risk Engineer, Pareto.AI Financial Engineer, OU Graduate RA/TA, Leekshotit Studios Founder

## Developer Notes
- The website uses CDN-hosted libraries (AOS, Google Fonts)
- No build step required - direct file serving
- Custom animations and interactions are all vanilla JavaScript
- Mobile-responsive with hamburger menu
- Resume PDF located at: src/pdf/Abdulmalik-Ajisegiri-Resume.pdf
- Personal photo: src/png/malik-photo.jpg (About section & footer)
- Navbar avatar: src/png/nav-avatar.png
- Contact: 
  - Email: abdulmalikajisegiri@gmail.com
  - Phone: (346) 297-8021
  - LinkedIn: https://www.linkedin.com/in/malikajisegiri
  - GitHub: https://github.com/Maleek23

## Portfolio Sections
1. **Home**: Hero section with name, title, and animated text
2. **About**: Personal introduction with photo, LinkedIn summary, and resume download
3. **Skills**: Tech stack showcase (Python, MATLAB, SQL, PyTorch, TensorFlow, AWS, Docker, etc.)
4. **Certifications**: Professional certifications (CISA, MATLAB, Bloomberg, Simulink)
5. **Honors & Awards**: Academic achievements and scholarships
6. **Projects**: 
   - Pareto.AI - Financial Engineering (DCF/LBO models for LLM training)
   - GenAI Risk-Bench Model (LLM validation framework)
   - Metaheuristic Search Framework (SA, GA, PSO algorithms)
   - RF Command Test Harness (Collins Aerospace automation)
   - NIST CSF Risk Assessment (Deloitte security project)
7. **Footer**: Contact info, social media links, and avatar

## Next Steps (Optional Future Enhancements)
- **Add Project Screenshots**: Replace gradient placeholders in Projects section with actual project screenshots
- **Customize Colors**: Modify color scheme in style.css if desired
- **Add More Projects**: Expand portfolio with additional work from LinkedIn experience
- **Add Blog/Publications Section**: If applicable, showcase technical writing or research
- **Deploy to Production**: Use Replit's deployment feature to publish the portfolio live
