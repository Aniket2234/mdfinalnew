# Malay Damania - Educational Platform

## Overview
Static HTML/CSS/JavaScript website for Malay Damania's coaching and educational platform. This is a professional educational website featuring courses, blog, testimonials, and contact information.

## Project Structure
- **HTML Pages**: Multiple pages including index, about, courses, blog, contact, etc.
- **Assets**: 
  - `assets/css/`: Stylesheets (Bootstrap, custom styles)
  - `assets/js/`: JavaScript libraries (jQuery, Slick, etc.)
  - `assets/images/`: All images organized by category
  - `assets/fonts/`: Font files
  - `assets/sass/`: SASS source files

## Technology Stack
- Pure HTML5
- CSS3 with Bootstrap 4.5.3
- JavaScript with jQuery 3.6.0
- Font Awesome 5.9.0
- Various jQuery plugins (Slick slider, Magnific Popup, etc.)

## Setup
This is a static website served by a simple Node.js HTTP server on port 5000.

## Recent Changes
- 2025-10-31: Initial Replit environment setup with HTTP server
- 2025-10-31: UI/UX Enhancement Package:
  - Increased logo size to 65px (desktop) and 50px (mobile) with responsive behavior
  - Optimized hero section to 90vh height (max 750px, min 600px) for single viewport display
  - Slowed hero image transitions to 2s fade with 15s interval for better visual experience
  - Updated navigation from "Offerings" to "What I Offer" across main pages
  - Enhanced "Who Am I" section with new professional image (malay-damania-photo.jpg)
  - Added Font Awesome icons to counter section: calendar (60+ years), diagram (2000+ projects), users (30+ team)
  - Redesigned offerings cards with vertical layout: 5 gold stars on top, eye icon with "1000+" below
  - Removed "Filter By Price" and "Filter By Level" sections from course-grid.html
  - Fixed typo in counter section ("expreesss" → "experience")

## Notes
- Logo sizing and navigation updates applied to index.html and course-grid.html
- Other HTML pages (about.html, contact.html, etc.) may benefit from similar header updates for consistency
- Hero section uses viewport-based sizing to eliminate scrolling on first screen
- Offerings cards use high-contrast design with dark background for better visibility
