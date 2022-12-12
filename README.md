# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![screenshot](/productPreviewScreenshot.jpg)

### Links

- Solution URL: [frontendmentor.io/solutions/product-preview-card-component-BkhSf7vYoE](https://www.frontendmentor.io/solutions/product-preview-card-component-BkhSf7vYoE)
- Live Site URL: [vejtheguy.github.io/product-preview-card](https://vejtheguy.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

With this project, I learned the use of the html picture tag and how you can apply a differnet image for different widths:

```html
  <picture class="product-image">
      <source srcset="images/image-product-mobile.jpg" media="(max-width: 600px)">
      <img src="images/image-product-desktop.jpg" alt="Square perfume bottle by Gabrielle CHANEL"/>
  </picture>
```

### Useful resources

- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - The best flexbox guide.

## Author

- CodePen - [@vejtheguy](https://codepen.io/vejtheguy)
- Frontend Mentor - [@vejtheguy](https://www.frontendmentor.io/profile/vejtheguy)
- Twitter - [@aworthlessgamer](https://twitter.com/aworthlessgamer)
