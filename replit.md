# Fidely Website

## Overview

Fidely is a modern static website for a startup specializing in digital loyalty card management. The website serves as a showcase for the Fidely mobile application, targeting merchants and potential partners. Built with vanilla HTML, CSS, and JavaScript, it features a vibrant design with animated elements and responsive layout.

## System Architecture

### Frontend Architecture
- **Pure Static Website**: No server-side processing required
- **Single Page Application**: All content in one HTML file with smooth scrolling navigation
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced with animations and interactions
- **Mobile-First Design**: Responsive layout built with CSS Grid and Flexbox

### Technology Stack
- **HTML5**: Semantic markup structure
- **CSS3**: Custom properties (CSS variables) for consistent theming
- **Vanilla JavaScript**: DOM manipulation and event handling
- **External CDNs**: Google Fonts, Font Awesome icons, AOS animation library

## Key Components

### 1. Design System
- **Color Palette**: Four primary colors (#ffc400 yellow, #ec1c24 red, #9b4ea6 purple, #00b5d9 turquoise)
- **Gradient System**: Main gradient from red to turquoise, logo gradient with multi-color flame effect
- **Typography**: Poppins (headings) and Open Sans (body text) from Google Fonts
- **Component Library**: Custom CSS classes for buttons, cards, and layout components

### 2. Navigation System
- **Fixed Header**: Stays at top during scroll with background transition
- **Mobile Hamburger Menu**: Toggleable navigation for mobile devices
- **Smooth Scrolling**: Anchor-based navigation between sections

### 3. Visual Elements
- **SVG Logo**: Custom flame-shaped logo with gradient fill and glow effect
- **Animation Library**: AOS (Animate On Scroll) for entrance animations
- **Icon System**: Font Awesome icons throughout the interface

### 4. Page Sections
- Hero section with call-to-action
- Features showcase
- Benefits presentation
- How-it-works explanation
- Pricing tiers
- Contact information

## Data Flow

### Static Content Flow
1. **HTML Structure**: Semantic sections define page layout
2. **CSS Styling**: Custom properties cascade through component system
3. **JavaScript Enhancement**: Progressive enhancement for animations and interactions
4. **Asset Loading**: External fonts, icons, and animations loaded via CDN

### User Interaction Flow
1. User arrives at landing page
2. Navigation allows jumping to specific sections
3. Mobile users can toggle hamburger menu
4. Scroll-triggered animations enhance user experience
5. Call-to-action buttons guide users to mobile app

## External Dependencies

### CDN Services
- **Google Fonts**: Poppins and Open Sans font families
- **Font Awesome**: Icon library (v6.4.0)
- **AOS Library**: Animate On Scroll animations (v2.3.1)

### Browser APIs
- **Intersection Observer**: Used by AOS for scroll animations
- **CSS Custom Properties**: For consistent theming
- **Flexbox/Grid**: For responsive layout

## Deployment Strategy

### Current Setup
- **Development Server**: Python HTTP server on port 5000
- **Static Hosting Ready**: Can be deployed to any static hosting service
- **No Build Process**: Direct file serving without compilation

### Deployment Options
- **Replit Hosting**: Current development environment
- **Netlify/Vercel**: Recommended for production deployment
- **GitHub Pages**: Alternative static hosting option
- **CDN Integration**: Can be enhanced with CDN for global performance

### File Structure
```
/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Stylesheet with custom properties
├── js/
│   └── script.js       # JavaScript enhancements
├── assets/
│   └── logo.svg        # Custom SVG logo
└── .replit             # Replit configuration
```

## Changelog

Changelog:
- June 26, 2025. Initial setup

## User Preferences

Preferred communication style: Simple, everyday language.