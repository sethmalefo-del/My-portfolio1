# Week 2 - HTML + CSS Portfolio

## Live Demo

Add your deployed portfolio URL here:

- Live site: `http://127.0.0.1:5502/index.html`

Note: The project can only be marked "styled portfolio live" after this URL is added and accessible.

## Project Overview

This project is a personal portfolio for Setlhomara Malefo.  
It uses semantic HTML5, external CSS, and Bootstrap 5 via CDN to create a responsive multi-section layout.

## Design Layout Choices

1. Structure
- Semantic tags are used for clarity and accessibility: `header`, `nav`, `main`, `section`, `article`, and `footer`.
- Content is split into four sections: About, Skills, Projects, and Contact.

2. Navigation
- A Bootstrap responsive navbar (`navbar`, `navbar-expand-lg`) is used for consistent navigation across screen sizes.
- Nav links use anchor targets (`#about`, `#skills`, `#projects`, `#contact`) for fast section jumps.

3. Grid System
- Bootstrap containers and grid are used throughout:
- `container` for centered content width.
- `row` and `col-*` for responsive columns in About, Skills, Projects, and Contact sections.

4. Visual Styling
- Custom styles are defined in `style.css` (external stylesheet).
- The design uses:
- A readable sans-serif font stack.
- Soft background and high-contrast text colors.
- Consistent section spacing using padding.
- Hover effects on links, navbar items, buttons, and project cards.

5. Form Design
- Contact form uses Bootstrap form components:
- `form-label`, `form-control`, spacing utilities, and `btn btn-primary`.
- Labels are associated with inputs using `for` + matching `id` for accessibility.

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5 (CDN)

## File Structure

```text
index.html
style.css
README.md
seth.jpg
coding-image.jpg
icon-image.jpg
real-ai-image.png
```

## Before/After Screenshots

Add your screenshots in the repository and link them here:

- Before: `PASTE_BEFORE_SCREENSHOT_PATH_OR_LINK`
- After: `PASTE_AFTER_SCREENSHOT_PATH_OR_LINK`

## How to Run Locally

1. Open the project folder.
2. Open `index.html` in a browser.
3. Ensure internet is available so Bootstrap CDN loads.

## Author

Setlhomara Malefo. All rights reserved.
