# Frontend Mentor - Blog preview card solution (Bootstrap 5 Refactor)

This is a refactored solution to the [Blog preview card challenge on Frontend Mentor](https://frontendmentor.io) using **Bootstrap 5**.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [References & Resources](#references--resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size using Bootstrap's responsive grid system.
- See interactive `:hover` and `:focus-visible` states on the card title link.

### Links


## My process

### Built with

- **Semantic HTML5:** `<main>`, `<section>`, `<article>`, `<footer>`
- **Bootstrap :** Responsive grid (`container`, `row`, `col-*`), Flexbox alignment (`d-flex`, `flex-column`, `justify-content-center`, `align-items-center`, `min-vh-100`), spacing utilities (`p-4`, `gap-3`, `gap-4`, `px-3`, `py-1`), and typography/shape helpers (`fw-bold`, `fw-bolder`, `rounded-4`, `rounded-circle`, `text-decoration-none`)
- **Custom CSS3:** `:root` HSL color variables, solid offset `box-shadow: 8px 8px`, and interactive hover transitions
- **Google Fonts:** [Figtree](https://google.com) (`500` and `800` weights)

### What I learned

Refactoring an existing pure-CSS component into **Bootstrap 5** reinforced how utility-first frameworks streamline layout development while still allowing custom brand styling:

- **Replacing Layout Boilerplate with Utilities:** Replaced custom Flexbox centering and viewport height rules with Bootstrap's `d-flex flex-column justify-content-center align-items-center min-vh-100` on `<body>`, and prevented flex children from stretching full-width using `align-self-start` and `align-items-start`.

- **Balancing Bootstrap with Custom CSS:** Overrode Bootstrap's default soft card shadow and color palette with targeted custom CSS rules (`border: 1px solid hsl(0, 0%, 7%)` and `box-shadow: 8px 8px hsl(0, 0%, 7%)`) to match the exact Figma specifications.

### Continued development

In future projects, I want to continue practicing:

- Customizing Bootstrap's built-in Sass / CSS custom properties directly to reduce custom override rules even further.

## References & Resources

- **Challenge & Design Specs:** [Frontend Mentor – Blog Preview Card](https://frontendmentor.io)
- **CSS Framework:** [Bootstrap 5 Documentation](https://getbootstrap.com)
- **Typography:** [Google Fonts – Figtree](https://google.com)

## Author

- **Name:** Cedrick Mbuyamba
- **GitHub:** [@cedrickmmk](https://github.com)
- **Frontend Mentor:** [@cedrickmmk](https://frontendmentor.io)

