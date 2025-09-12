# Overview

**Status: COMPLETED** ✅

This is a bilingual (French) personal portfolio and training center website for Ange AKONDE, a Full Stack Developer. The project consists of two complete, standalone HTML pages: a personal portfolio showcasing development skills and projects, and a training center page highlighting educational services. The website emphasizes modern web design with a cohesive "Gecko" color palette, elegant typography, and comprehensive interactive features.

**Delivered Files:**
- `index.html` - Main portfolio page with hero video, projects grid, testimonials carousel, and contact form
- `center.html` - Training center page with programs, mission, and team testimonials
- `assets/README.md` - Complete guide for asset replacement and optimization

**Server Status:** Portfolio is running on port 5000 and fully functional.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
The project uses a vanilla HTML/CSS/JavaScript approach with all code contained within single-file components. Each HTML file is completely self-contained with embedded CSS in `<style>` tags and JavaScript in `<script>` tags, eliminating the need for build tools or external dependencies.

**Design System:**
- Gecko color palette with CSS custom properties for consistent theming
- Typography hierarchy using Playfair Display for headings and Poppins for body text
- Responsive grid system with mobile-first approach
- Component-based CSS organization with BEM-like naming conventions

**Interactive Features:**
- Smooth scrolling navigation with intersection observers for reveal animations
- Accessible mobile navigation with focus trapping and keyboard controls
- Lightbox gallery system with keyboard navigation
- Form validation with simulated success responses
- Video carousel with autoplay and hover controls
- Typing effect animations for hero sections

## Responsive Design Strategy
The architecture implements a mobile-first responsive design with:
- Fluid typography and spacing using CSS custom properties
- Flexible grid layouts that adapt from mobile to desktop
- Mobile navigation drawer with full-screen overlay
- Touch-optimized interactive elements
- Optimized media queries for common breakpoints

## Accessibility Implementation
The system prioritizes web accessibility through:
- Semantic HTML structure with proper heading hierarchy
- ARIA labels and roles for interactive components
- Keyboard navigation support for all interactive elements
- Focus management in modal dialogs and navigation
- High contrast ratios following WCAG guidelines
- Screen reader compatible content structure

## Asset Management
The project uses a centralized assets folder structure with specific naming conventions for:
- Profile and project images with defined dimensions
- Video assets for hero backgrounds and testimonials
- Downloadable documents (CV/resume)
- Clear documentation for asset replacement and optimization

# External Dependencies

## Typography Services
- **Google Fonts**: Playfair Display and Poppins font families loaded via CDN for consistent typography across devices

## Media Assets
- **Local Assets Folder**: Centralized management of images, videos, and documents
- **Optimized Media**: Specific requirements for image dimensions and video formats for performance

## Third-Party Integrations
- **Social Media Platforms**: Direct links to Facebook, Instagram, Twitter/X, and LinkedIn profiles
- **Communication Channels**: WhatsApp and email contact integration
- **No External JavaScript Libraries**: Pure vanilla JavaScript implementation for all interactive features

The architecture emphasizes performance, accessibility, and maintainability while providing a rich user experience without external framework dependencies.