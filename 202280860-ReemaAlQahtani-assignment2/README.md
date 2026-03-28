# Personal Portfolio Website

**Assignment 2 — Interactive Portfolio Enhancements**

---

## Project Description

This project represents the **second phase** of my personal portfolio website.
It extends the foundation built in Assignment 1 by adding **interactive features, improved UI components, and enhanced JavaScript functionality**.

The website is developed using **HTML, CSS, and JavaScript** and demonstrates structured front-end development, responsive design, and dynamic user interaction.

The website contains four main sections:

- **About Me** — Personal introduction with dynamic time-based greeting
- **Skills** — Interactive skills section with category filtering
- **Projects** — Featured academic and technical projects
- **Contact** — Interactive frontend form with validation

Assignment 2 focuses on improving **interactivity, accessibility, and user experience**.

---

## Technologies Used

- **HTML5** (Semantic structure & accessibility)
- **CSS3**
  - Flexbox
  - CSS Grid
  - Media Queries
  - CSS Variables
  - Glassmorphism UI styling
- **Vanilla JavaScript**
  - DOM Manipulation
  - Event Handling
  - LocalStorage API
  - Dynamic content rendering
- **ARIA attributes** for accessibility

---

## Key Features

- Fully responsive layout (Desktop, Tablet, Mobile)
- Light/Dark theme toggle stored in `LocalStorage`
- Time-based dynamic greeting
- Mobile navigation menu with accessibility support
- Interactive **Skills filtering system**
- Glass-style segmented filter buttons
- Dynamic rendering of skills from a JavaScript data array
- Client-side contact form validation
- Accessibility improvements (ARIA attributes and keyboard navigation)
- Organized project cards with responsive images using `aspect-ratio`

---

## Skills Section (Assignment 2 Feature)

A dynamic Skills section was implemented as a major interactive feature.

Features include:

- Category filtering (All, Frontend, Backend, Tools)
- Glass-style segmented filter buttons
- Dynamic skill rendering using JavaScript
- Keyboard accessibility support
- Active filter highlighting

Skills are stored as structured JavaScript objects and rendered dynamically into the DOM.

Example:

```js
const SKILLS = [
  { name: "HTML", level: "Good", category: "frontend" }
];
```

This approach improves maintainability and demonstrates **dynamic UI rendering using JavaScript**.

---

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/ReemaAlqahtani1/202280860-ReemaAlQahtani-assignment2.git
```

2. Open the project folder.

3. Open `index.html` in your browser:

- Double-click the file
OR
- Right-click → Open with your browser

No installation or dependencies are required.

---

## AI Usage Summary

AI tools were used to assist with:

- Improving JavaScript structure and filtering logic
- UI/UX design suggestions
- Responsive layout refinement
- Debugging and optimization
- Documentation formatting

A detailed explanation of AI assistance is provided in:

```
docs/ai-usage-report.md
```

---

## Author

**Reema S. AlQahtani**
Software Engineering Student