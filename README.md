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
- [AuthorAuthor Links](#author-links)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![desktop screenshot](./screenshot-desktop.png)

### Links

- Solution URL: [Frontend Mentor Solution Page](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/product-preview-card-component-C4bAJWMQEP)
- Live Site URL: [Live Github Page](https://john-csm-tate.github.io/fem-product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flexbox
- Mobile-first workflow

### What I learned

Using html picture tag to change picture with a media query 

```html
<picture class="product-image">
  <source 
    srcset="src/images/image-product-desktop.jpg"
    media="(min-width:600px)">
  <img 
    src="./src/images/image-product-mobile.jpg" 
    alt="Gabrielle Essence Eau De Parfum Bottle laying on a table with leaves.">
</picture>
```

## Author Links

- Frontend Mentor - [@John-CSM-Tate](https://www.frontendmentor.io/profile/John-CSM-Tate)
- ![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn - [@John-CSM-Tate](https://www.linkedin.com/in/john-csm-tate/)
