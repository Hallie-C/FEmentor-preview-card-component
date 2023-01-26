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

![](./screenshot.jpg)

![desktop view](https://github.com/Hallie-C/FEmentor-preview-card-component/tree/main/screenshots/screenshot-desktop-view.jpg?raw=true)
![mobile view](https://github.com/Hallie-C/FEmentor-preview-card-component/tree/main/screenshots/screenshot-mobile-view.jpg?raw=true)

### Links

- Solution URL: (https://github.com/Hallie-C/FEmentor-preview-card-component)
- Live Site URL: (https://hallie-c.github.io/FEmentor-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Through working with this project, I have more chance to work with flexbox and understand more about how it works with just simple design. I can also apply my CSS knowledge to design typgraphy, align items at required position.

```css
/* The flexbox here is used to center the card vertically with the device view */
.container {
    margin: auto;
    max-width: 600px;
    height: 100vh;
    display: flex;
    align-items: center;
}

/* The second flex is used to design the card with 2 equal columns */
article {
    display: flex;
}

article > * {
    width: 50%;
}
```

### Useful resources

- [resource 1](https://www.youtube.com/watch?v=u044iM9xsWU) - This helped me to understand basic concepts of flexbox. The instruction and example is really clear and easy to follow
- [resource 2](https://www.w3schools.com/css/default.asp) - Help me have a deep understanding of html and css. 

## Author
- Frontend Mentor - [@HaanLinn](https://www.frontendmentor.io/profile/HaanLinn)

