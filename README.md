# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/showcase/desktop.png)
![](./images/showcase/mobile.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

My greatest learning other than continuing to practice CSS grids is my implementation of the <picture>-element as seen below.
I have never used this feature of HTML before but found it most useful for this scenario!

```html
<picture>
  <source media="(max-width: 999px)" srcset="images/image-product-mobile.jpg" />
  <img src="images/image-product-desktop.jpg" alt="A perfume bottle">
</picture>
```

### Continued development

Next time I want to start trying out making things in JSX/React rather than just plain html. I also want to continue my use of grids in order to learn even more about how to apply them.

### Useful resources

- [MDN Documentation for \<picture\>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - A great resource for learning more about the picture element.

## Author

- Website - [Sixten Peterson](https://snicon.rip)
- Frontend Mentor - [@Snicon](https://www.frontendmentor.io/profile/Snicon)