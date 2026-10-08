# Personal Portfolio

## About

This project is a personal portfolio website built from scratch using HTML5, CSS3, and JavaScript ES6+.

The portfolio presents my background, technical skills, previous projects, hobbies, and a contact form.

## Technologies

- HTML5
- CSS3
- JavaScript ES6+
- Git

No frameworks, templates, or UI libraries were used.

## Website Sections

The portfolio contains:

- Header and navigation
- About Me
- Skills
- Project Showcase
- Hobbies
- Contact Form
- Footer

## Projects

The Project Showcase includes my previous work from:

- Project 00 — Linux, Git & GitHub
- Project 01 — HTML Fundamentals
- Project 02 — CSS & Visual Presentation
- Project 03 — JavaScript & Interactivity

## Responsive Design

The website uses CSS Flexbox and media queries to adapt the layout to smaller screens.

A media query is used at `600px` to change the navigation layout and adjust the size of cards, images, and the contact form for mobile devices.

## JavaScript Theme Switcher

The portfolio includes an interactive theme switcher.

When the user clicks the **Toggle Theme** button, JavaScript toggles the `dark` class on the `<body>` element.

### Event Lifecycle

The complete event lifecycle is:

1. **User action** — The user clicks the Toggle Theme button.
2. **Event firing** — The browser detects the `click` event.
3. **JavaScript callback** — The function registered with `addEventListener()` runs.
4. **DOM mutation** — `classList.toggle("dark")` adds or removes the `dark` class from the `<body>`.
5. **CSS mutation/effect** — The CSS rules targeting `body.dark` become active or inactive, changing the page appearance.

This demonstrates how JavaScript can respond to user events and dynamically modify the DOM and CSS.

## Contact Form

The contact form includes:

- Name
- Email
- Message

HTML5 validation is used to require valid input before submission.

## Author

Ali Al Nessir
