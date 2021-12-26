# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Deployed Site URL: https://nft-preview-card-fm.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Major learnings - Flexbox alignment, Position - absolute, relative

```html
<h1>Some HTML code I'm proud of</h1>
<header>
  <img class="image-equilibrium" src="./images/image-equilibrium.jpg" alt="icon-equilibrium">
  <div class="cover-overlay">
    <img class="icon-view" src="./images/icon-view.svg" alt="icon-view">
  </div>
</header>
```
```css - I'm proud of 
.cover-overlay {
    background-color: var(--clr-primary-cyan);
    border-radius: 1rem;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 99%;
    opacity: 0;
}

.icon-view {
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
}

.cover-overlay:hover {
    opacity: 0.5;
}
```

### Continued development

Concepts to be more comfortable
-Css properites - transform, box-shadow
