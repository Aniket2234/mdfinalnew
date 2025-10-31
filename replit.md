# Malay Damania - Educational Platform

## Overview
This project is a static HTML/CSS/JavaScript website for Malay Damania's coaching and educational platform. The platform aims to be a professional educational resource featuring courses, a blog, testimonials, and contact information. The business vision is to empower individuals and businesses through high-quality educational content and coaching, helping them scale, lead, and succeed in competitive markets.

## User Preferences
The agent should prioritize consistent UI/UX across the entire website. All major CTAs should use cylindrical buttons with a border-radius of 50px. The brand accent color #00796b (teal) should be maintained consistently. Mobile-first responsive design is critical, ensuring proper layout on all devices from 320px to 1920px+ widths. Key headings should use the Oswald font family for visual hierarchy and brand consistency. Testimonial carousels should use CSS animations with infinite scroll and duplicated cards for seamless looping. Animations should be lazy-loaded and compatible with mobile devices.

## System Architecture
The platform is built as a static website using Pure HTML5, CSS3 with Bootstrap 4.5.3, and JavaScript with jQuery 3.6.0.

**UI/UX Decisions:**
- **Consistent Branding:** The logo (`logo-new.png`) is consistently used across all pages with responsive sizing (95px desktop, 60px tablet, 45px mobile). "Offerings" has been uniformly updated to "What I Offer".
- **Navigation:** Main navigation and CTA buttons (`Book a Consult`) are standardized with cylindrical designs and consistent icons (fa-phone). Header padding is reduced to 5px for a compact look.
- **Hero Section:** Optimized to 90vh height (max 750px, min 600px) on desktop, with responsive adjustments for mobile (minimum height 500px). Hero image transitions are slowed to a 2s fade with 15s intervals.
- **Offerings/Course Cards:** Redesigned with modern, compact layouts, rounded corners, subtle shadows, and hover effects. Ratings are displayed in a dark badge overlay on course images. Price display is prominent.
- **Testimonials:** Implemented as an auto-scrolling carousel with two horizontal rows animating in opposing directions (left-to-right, right-to-left). Features 40s linear infinite scroll with pause-on-hover.
- **About Page:** Features a 2-row layout for "Who Am I": text content + image in the top row, four stat cards in the middle, and centered buttons below. Stat cards are horizontal and equal height.
- **"What I Offer" Page:** Features a full-width design without a sidebar. A prominent, rounded search bar is centered at the top, offering real-time filtering. Course grid uses a responsive CSS Grid layout (3-column desktop, 2-column tablet, 1-column mobile) with toggle options.
- **Course Detail Pages:** Streamlined with only the course title visible in the header, removing category labels, badges, and star ratings for a cleaner presentation.
- **Footer:** Standardized across all pages as a 4-column responsive grid (About | Services | Resources | Contact) with green accents, circular social icons, and a clean flexbox copyright area.
- **Typography:** Oswald font is used for key headings. Specific font sizes and weights are defined for various sections (e.g., Counter section labels, Offerings heading, Who Am I section).
- **Animations:** Lazy loading animations (e.g., `fadeInUp`) are integrated using WOW.js throughout pages, with staggered delays for course cards. Animations reinitialize after search/filter operations.

**Technical Implementations:**
- **Responsive Design:** Comprehensive media queries are implemented for mobile (<480px), tablet (481-992px), and desktop (>992px) with a three-tier breakpoint system for JavaScript responsiveness.
- **Client-side Filtering:** JavaScript is used for instant search and filtering on the "What I Offer" page without page reloads.
- **Asset Management:** Images are organized within `assets/images/` with specific subfolders like `assets/images/about/`.

## External Dependencies
-   Bootstrap 4.5.3 (CSS Framework)
-   jQuery 3.6.0 (JavaScript Library)
-   Font Awesome 5.9.0 (Icons)
-   Slick (jQuery Carousel Plugin)
-   Magnific Popup (jQuery Lightbox Plugin)
-   WOW.js (Reveal Animations CSS Library)