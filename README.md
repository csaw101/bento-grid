# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Learned how to use CSS Grid layout, using the `grid-template-areas` and `grid-area` properties

```css
.bento-grid {
  display: grid;
  grid-template-columns: repeat(4, 9em);
  grid-template-rows: repeat(10, 2.5em);
  grid-template-areas:
    "block-7 block-1 block-1 block-4"
  ...
  .block-1 {
    grid-area: block-1;
  }
  ...
  ;
}
```

## Author

- Github - [@csaw101](https://www.github.com/csaw101)
- Frontend Mentor - [@csaw101](https://www.frontendmentor.io/profile/csaw101)
