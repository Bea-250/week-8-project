# week-8-project
# CreativeFlow - Digital Agency Website

A modern, responsive multi-page website for a creative digital agency built with HTML5, CSS3, and JavaScript. This project demonstrates professional web development practices, responsive design, and interactive user experiences.


## 📋 Project Overview

CreativeFlow is a comprehensive digital agency website featuring:
- Purpose: Showcase digital services and attract potential clients
- Target Audience: Businesses looking for web design, development, and digital marketing services
- Goal: Convert visitors into leads through compelling design and clear calls-to-action

## 🏗️ Site Structure

### Pages Overview
1. Home (`index.html`) - Hero section, services preview, testimonials, and stats
2. About (`about.html`) - Company story, values, and team members
3. Services (`services.html`) - Detailed service offerings and process
4. Portfolio (`portfolio.html`) - Project showcase with filtering functionality
5. Contact (`contact.html`) - Contact form with validation and company information

### Navigation Flow
```
Home → About/Services/Portfolio → Contact
     ↘ Direct CTAs to Contact
```

## ✨ Core Features

- Responsive Design: Mobile-first approach with breakpoints at 768px and 1024px
- Interactive Navigation: Mobile hamburger menu with smooth transitions
- Form Validation: Real-time validation with user feedback
- Portfolio Filtering: Dynamic project filtering by category
- Animated Counters: Statistics that animate when scrolled into view
- Testimonial Slider: Auto-advancing testimonials with manual controls
- FAQ Accordion: Expandable frequently asked questions
- Scroll Animations: Elements fade in as they enter the viewport

## 🎨 Design Elements

Color System
- Primary: `#6366f1` (Indigo)
- Secondary: `#8b5cf6` (Purple)
- Accent: `#f59e0b` (Amber)
- Success: `#10b981` (Emerald)
- Background: `#f8fafc` (Slate 50)
- Text: `#1e293b` (Slate 800)

Typography
- Font: Inter (Google Fonts)
- Weights: 300, 400, 500, 600, 700
- Scale: Responsive typography using `clamp()`

 Layout Principles
- 8px Grid System: Consistent spacing throughout
- Visual Hierarchy: Clear typography and spacing
- White Space: Intentional use for improved readability
- Accessibility: Proper contrast ratios and semantic HTML

## 📁 File Organization

```
/
├── index.html              # Home page
├── about.html              # About page  
├── services.html           # Services page
├── portfolio.html          # Portfolio page
├── contact.html            # Contact page
├── README.md               # Project documentation
├── css/
│   └── style.css           # Main stylesheet (organized sections)
└── js/
    └── main.js             # JavaScript functionality
```

Code Organization Highlights
- Modular CSS: Organized by components and sections
- Semantic HTML5: Proper use of header, main, section, article elements
- JavaScript Modules: Functions organized by feature
- Consistent Naming: BEM-like methodology for CSS classes
- Comments: Comprehensive code documentation

## 🚀 Technologies Used

Frontend
- HTML5: Semantic markup with proper meta tags
- CSS3: Modern features including Grid, Flexbox, and CSS Variables
- JavaScript (ES6+)**: Vanilla JS with modern APIs
- Google Fonts**: Inter font family

Features Implemented
- Intersection Observer API: For scroll animations
- CSS Grid & Flexbox: For responsive layouts
- CSS Transitions: For smooth interactions
- Form API: For contact form validation
- LocalStorage: For storing user preferences (future enhancement)

## 📱 Responsive Design

Breakpoints
- Mobile: < 768px (Single column layouts)
- Tablet: 768px - 1024px (Adapted two-column layouts)
- Desktop: > 1024px (Full multi-column layouts)

Mobile Optimizations
- Touch-friendly button sizes (44px minimum)
- Collapsible navigation menu
- Optimized image sizes
- Single-column layouts
- Larger text for readability

## 🎯 Interactive Features

JavaScript Functionality
1. Mobile Navigation: Hamburger menu with slide animation
2. Scroll Effects: Header changes on scroll, smooth scrolling
3. Form Validation: Real-time validation with error messages
4. Portfolio Filter: Category-based project filtering
5. Testimonial Slider: Auto-advancing with manual controls
6. FAQ Accordion: Expandable Q&A sections
7. Counter Animation: Numbers animate when in viewport
8. AOS (Animate On Scroll): Custom implementation

Form Features
- Required field validation
- Email format validation
- Character count validation
- Success/error states
- Loading indicators
- Accessibility features
