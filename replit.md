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
- 2025-10-31: First UI/UX Enhancement Package:
  - Increased logo size to 65px (desktop) and 50px (mobile) with responsive behavior
  - Optimized hero section to 90vh height (max 750px, min 600px) for single viewport display
  - Slowed hero image transitions to 2s fade with 15s interval for better visual experience
  - Updated navigation from "Offerings" to "What I Offer" across main pages
  - Enhanced "Who Am I" section with new professional image (malay-damania-photo.jpg)
  - Added Font Awesome icons to counter section: calendar (60+ years), diagram (2000+ projects), users (30+ team)
  - Redesigned offerings cards with vertical layout: 5 gold stars on top, eye icon with "1000+" below
  - Removed "Filter By Price" and "Filter By Level" sections from course-grid.html
  - Fixed typo in counter section ("expreesss" → "experience")

- 2025-10-31: Second UI/UX Enhancement Package:
  - **Logo**: Replaced with transparent background version (logo-new.png) and increased to 95px (desktop), 60px (tablet), 45px (mobile)
  - **Navigation**: Fixed "Book a Consult" icon from phone-alt to curved phone icon
  - **Hero Slider**: Removed left/right arrow buttons, kept dots-only navigation
  - **CTA Buttons**: Removed arrow icons from "Start Your Growth Journey" buttons
  - **Detail Cards**: Reduced padding (18px → 12px-15px), improved icons (chart-line, book-open, lightbulb, user-tie), lighter shadows, more compact design
  - **Rating Badges**: Made smaller (stars: 18px → 14px, text: 14px → 12px, padding reduced)
  - **Testimonials**: Redesigned from carousel to clean 3-column responsive grid, simplified layout, removed complex animations
  - **Footer**: Restructured into organized 4-column grid (About | Services | Resources | Contact), improved spacing and alignment

- 2025-10-31: Third UI/UX Enhancement Package (Spacing & Layout Refinements):
  - **Header**: Reduced padding from 10px to 5px for a more compact, cleaner look
  - **Who Am I Section**: Increased font sizes for better readability (title: 28px → 32px, text: 16px → 18px)
  - **Counter Section**: Streamlined design with reduced height (padding: 40px → 25px), updated icons (briefcase, rocket, user-tie), smaller fonts (icons: 42px → 32px, numbers: 40px → 34px, text: 16px → 14px)
  - **Section Spacing**: Reduced padding between all homepage sections for tighter layout (main: 80px → 50px, testimonials: 130px → 60px, engagement: 50px → 30px)
  - **Testimonials**: Added 3 additional reviews (6 total), fixed alignment issue by changing to align-items-start, added flex-shrink: 0 to profile images
  - **Footer**: Removed vacant space by reducing padding (50px → 30px) and copyright margin (30px → 20px)

- 2025-10-31: Fourth UI/UX Enhancement Package (Buttons, Typography & Animated Carousel):
  - **Counter Section Text**: Capitalized labels properly ("Years of Experience", "Projects Delivered", "Team Architects") and increased font size from 14px to 16px with font-weight 600
  - **Offerings Heading**: Replaced "Offerings" with "What Are Our Offerings" in both instances, changed font to Oswald 800 with 1px letter-spacing for bold, distinctive look
  - **GET STARTED Button**: Made fully cylindrical (border-radius: 50px), increased padding to 15px 45px, added min-width 220px, changed text to uppercase
  - **Book a Consult Button**: Made cylindrical (border-radius: 50px) with increased padding: 12px 28px (desktop), 12px 24px (mobile)
  - **Testimonials Carousel**: Completely redesigned as animated scrolling carousel with:
    - Two horizontal rows with opposing animations (Row 1: left-to-right, Row 2: right-to-left)
    - 40s linear infinite scroll with pause-on-hover functionality
    - Compact card design (380px min-width desktop, 280px mobile, 260px extra small)
    - Added 2 new dummy reviews (Neha Kapoor - Digital Marketing, Arjun Verma - Real Estate)
    - Duplicated cards for seamless infinite scroll effect
  - **Mobile Responsiveness**: Added comprehensive media queries for tablets (<768px) and phones (<480px):
    - Hero section minimum height adjusted to 500px on mobile
    - Counter section stacks vertically on mobile
    - Testimonial cards resize appropriately (380px → 280px → 260px)
    - Footer columns stack vertically with centered copyright
    - All typography scales down appropriately

## Notes
- Logo sizing and navigation updates applied to index.html and course-grid.html
- Other HTML pages (about.html, contact.html, etc.) may benefit from similar header updates for consistency
- Hero section uses viewport-based sizing to eliminate scrolling on first screen
- Offerings cards use high-contrast design with dark background for better visibility
- All new designs maintain #00796b (teal) as the brand accent color
- Responsive breakpoints implemented for mobile (<768px), tablet (<992px), and desktop
- Cylindrical buttons (border-radius: 50px) are now the standard for all major CTAs
- Testimonials carousel uses CSS animations with infinite scroll - duplicated cards ensure seamless looping
- Mobile-first responsive design ensures proper layout on all devices from 320px to 1920px+ widths
- Oswald font family used for key headings to create visual hierarchy and brand consistency
