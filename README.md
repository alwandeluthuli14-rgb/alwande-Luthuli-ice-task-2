# ICE Task 2 — Styling Your Profile Page with CSS

**Student:** Alwande Luthuli  
**Student Number:** ST10509451  
**Task:** ICE Task 2 — Styling Your Profile Page with CSS  
**Year:** 2026

## 1. Project Overview

This project continues the single-page Profile Page from ICE Task 1. The HTML structure was extended with an internal navigation menu and a contact form, while the visual presentation was moved into an external CSS stylesheet.

The page is designed as a clean personal/professional profile with sections for Home, About, Education, Skills and Contact.

## 2. Navigation

The page uses a semantic `<nav>` element. Each navigation item uses an anchor link such as `href="#about"` to move to a section with the matching `id` attribute.

The navigation sections are:

- Home
- About
- Education
- Skills
- Contact

This keeps the project as a single webpage while allowing visitors to move quickly between important sections.

## 3. Contact Form

The Contact section contains an HTML `<form>` with:

- Visitor Name — text input
- Email Address — email input
- Social Contact — text input
- Message / Reason for Contact — textarea
- Submit button
- Cancel / Reset button

Each input has an associated `<label>` using matching `for` and `id` attributes. The form is an HTML/CSS exercise and does not require JavaScript, a server or email functionality.

## 4. Layout

CSS Grid is used for the main hero area, two-column information areas, skills cards and contact area. Grid makes it possible to organise related content into clear columns.

Flexbox is used for navigation, buttons, quick-fact tags and footer alignment. Flexbox is useful where content needs to be arranged in a row and wrapped when necessary.

## 5. CSS Selectors

The stylesheet demonstrates different selector types:

- Element selectors such as `body`, `a`, `h3` and `label`
- Class selectors such as `.container`, `.skill-card`, `.button` and `.contact-form`
- ID selectors such as `#home`, `#about`, `#education`, `#skills` and `#contact`

No inline CSS is used.

## 6. Design Decisions

The design uses a restrained teal, white, off-white and dark-text colour scheme. The colours create contrast while keeping the page professional and easy to read.

Spacing, padding, borders, rounded corners and subtle shadows are used to separate content without making the page visually crowded.

Typography uses a simple system font stack so that the page remains readable and does not depend on an external font service.

The profile image area is presented as an initials-based placeholder so that the page remains complete even when a personal photograph is not supplied. It can be replaced with the student's own photograph without changing the page structure.

## 7. Learning Reflection

### One CSS concept I understand better

I understand the CSS box model better. Every element can be considered in terms of its content, padding, border and margin. This helped me control the spacing between sections, cards, form fields and buttons.

### One CSS concept that was challenging

Creating a balanced multi-column layout was challenging because different sections contain different amounts of information. Using CSS Grid made the relationships between columns easier to control.

### How I solved the problem

I separated the page into logical sections and used Grid for larger page structures and Flexbox for smaller horizontal groups. I also used consistent spacing and reusable classes so that the design remained coherent.

### One new HTML feature added

I added an HTML contact form containing labels, text inputs, an email input, a textarea and buttons. I also added internal anchor navigation using section IDs.

## 8. Final Checklist

- [x] HTML file is present
- [x] External CSS file is present
- [x] CSS is correctly linked to HTML
- [x] Internal navigation menu is included
- [x] Navigation links point to page sections
- [x] Contact form is included
- [x] Labels are associated with form controls
- [x] Submit and Reset buttons are included
- [x] Element selectors are used
- [x] Class selectors are used
- [x] ID selectors are used
- [x] Consistent colour scheme is used
- [x] Typography is styled
- [x] Margin and padding are used
- [x] Borders/backgrounds are used
- [x] Profile image area is styled
- [x] Navigation is styled
- [x] Contact form is styled
- [x] Form controls and buttons are styled
- [x] Flexbox and CSS Grid are used
- [x] No inline CSS is used
- [x] No CSS framework is used
- [x] Learning reflection is included

## Files

- `index.html` — completed Profile Page
- `style.css` — external stylesheet
- `README.md` — explanation and learning reflection
- `profile-placeholder.svg` — profile image placeholder
