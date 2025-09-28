# Overview

This is a static restaurant website template called "Restoran" built with Bootstrap 5. The website appears to be a multi-page restaurant site featuring sections for home, about, menu, services, team, testimonials, booking, and contact. The template includes modern responsive design with animations, carousels, and interactive elements typical of restaurant websites.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture

The application follows a traditional multi-page website structure using pure HTML, CSS, and JavaScript:

- **Static HTML Pages**: Multiple standalone HTML files (index.html, about.html, menu.html, booking.html, contact.html, etc.) representing different sections of the restaurant website
- **Bootstrap Framework**: Uses Bootstrap 5 for responsive grid system and component styling
- **Custom Styling**: Custom CSS in `css/style.css` with CSS custom properties for theming (primary color: #FEA116, dark: #0F172B)
- **Typography**: Uses Google Fonts (Heebo, Nunito, Pacifico) for varied typography needs

## Interactive Components

- **jQuery-based Interactions**: Main JavaScript functionality in `js/main.js` handles:
  - Page loading spinner
  - Sticky navigation on scroll
  - Dropdown hover effects for desktop
  - Animation initialization with WOW.js
- **Third-party Libraries**: 
  - Owl Carousel for image/content sliders
  - Animate.css for entrance animations
  - WOW.js for scroll-triggered animations
  - Tempus Dominus for date/time picking (likely for reservations)
  - Various easing and waypoint libraries for smooth interactions

## Design System

- **Color Scheme**: Orange primary (#FEA116), dark navy (#0F172B), light blue (#F1F8FF)
- **Font Strategy**: 
  - Pacifico for decorative/brand elements
  - Nunito for headings
  - Heebo for body text
- **Icon System**: Font Awesome 5 and Bootstrap Icons for UI elements

## Page Structure

Each page follows a consistent structure:
- Loading spinner
- Navigation bar with brand logo
- Page-specific content sections
- Likely includes footer (not visible in provided files)

The template includes standard restaurant website pages:
- **Home** (index.html): Main landing page
- **About** (about.html): Restaurant information
- **Menu** (menu.html): Food offerings
- **Services** (service.html): Restaurant services
- **Team** (team.html): Staff information
- **Testimonials** (testimonial.html): Customer reviews
- **Booking** (booking.html): Reservation system
- **Contact** (contact.html): Contact information
- **Legal Pages**: Privacy policy, terms, cookies, FAQ, help

# External Dependencies

## Third-party Libraries
- **Bootstrap 5.0.0**: CSS framework for responsive design and components
- **jQuery**: Required for interactive functionality and third-party plugins
- **Google Fonts API**: Typography (Heebo, Nunito, Pacifico fonts)
- **Font Awesome 5.10.0**: Icon library via CDN
- **Bootstrap Icons 1.4.1**: Additional icon set via CDN

## Animation and Interaction Libraries
- **Animate.css 3.5.2**: CSS animation library
- **WOW.js 1.3.0**: Scroll-triggered animations
- **Owl Carousel 2.2.1**: Responsive carousel/slider component
- **jQuery Easing 1.4.1**: Enhanced animation easing functions
- **Waypoints 4.0.1**: Scroll position detection
- **CounterUp 2.1.0**: Animated number counting
- **Tempus Dominus Bootstrap 4 v5.1.2**: Date/time picker component with Moment.js

## Advertising Integration
- **Google AdSense**: Integrated with publisher ID pub-4755491683835459
- **ads.txt**: Configured for programmatic advertising verification

## Asset Dependencies
- **Images**: Stored in `img/` directory (favicon.svg and likely other restaurant images)
- **Static Assets**: All CSS, JavaScript, and library files served locally rather than from CDNs (except Google Fonts and some icon libraries)

The architecture prioritizes simplicity and performance with a traditional multi-page approach, making it easy to customize for different restaurant brands while maintaining consistent functionality across all pages.