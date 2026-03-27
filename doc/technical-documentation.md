# Technical Documentation

## 1. Project Overview

This project is an interactive front-end portfolio website built using HTML, CSS, and JavaScript.
It extends Assignment 1 by adding dynamic behavior, improved user experience, and interactive features.
---

## 2. Structure
```
202280240-DanhAlsawad-assignment-2/
│
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── images/
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
│
└── .gitignore
```


### index.html
Contains:
- Navigation bar with section links (About, Projects, Contact)
- Hero section with introduction and call-to-action buttons
- About section
- Projects section with filter buttons
- Contact form with validation
- Theme toggle button (icon-based)

### styles.css
Handles:
- Layout and spacing
- Hero section design
- Card and project styling
- Button and hover effects
- Responsive design (media queries)
- Dark/Light theme variables
- Animations (fade-in / reveal)
- Form styling and feedback states

### script.js
JavaScript was used to implement multiple interactive features:

- Theme toggle with localStorage (remembers user preference)
- Project filtering using button clicks and category matching
- Contact form validation with error/success messages
- Scroll-based section highlighting in navigation
- Reveal animations triggered on scroll

---

## 3. Responsive Design

- Used flexible layouts (Flexbox and Grid)
- Applied percentage-based widths
- Used media queries for tablets and mobile screens
- Ensured proper spacing and readability across devices

---

## 4. Dark Mode Implementation

- A .light class is toggled on the body element
- JavaScript stores theme preference using localStorage
- CSS variables (--bg, --text, etc.) control colors
- Ensures consistent styling across the entire page

---

5. Interactive Features
Project Filtering
- Buttons allow filtering projects by category
- JavaScript updates visibility of project cards
- Displays message if no results are found
Contact Form Validation
- Checks for empty fields
- Validates email format
- Displays error or success messages dynamically
Navigation Highlighting
- Active section is detected during scroll
- Corresponding navigation link is highlighted
Scroll Reveal Animation
- Sections animate into view when scrolling
- Improves visual experience and engagemen

---
## 6. Image Handling
- Images stored in assets/images
- Styled with:
- - width: 100%
- - height: auto
- - object-fit: cover
- - border-radius for visual consistency
- Responsive across screen sizes

## 7. Browser Testing

Tested on:
- Google Chrome
- Microsoft Edge

No major compatibility issues found.