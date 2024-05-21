# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Links

- Solution URL: [Git Repo](https://github.com/N1Dovud/grid)
- Live URL: [Git liveserver](https://n1dovud.github.io/grid)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned


```css
#svg {
    position: absolute;
    top: 1%;
    right: 10%;
    opacity: 70%;
    z-index: 1;
}
@media (min-width: 900px) {
    main {
        grid-template-columns: repeat(4, 1fr);
    }
    .bigger {
        grid-row: 1 / 3;
        grid-column: 4 / 5;
    }
}
```

### Continued development
I need to learn more about how to change the behaviour of grid as the screen size gets bigger and bigger. I need to learn more about responsiveness.

## Author
- Frontend Mentor - [N1Dovud](https://www.frontendmentor.io/profile/N1Dovud)
