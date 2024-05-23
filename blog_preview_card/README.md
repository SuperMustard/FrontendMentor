# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to keep margin while shrink window.

```css
.imageContainer {
  display: flex;
  position: relative;
  align-content: center;
  justify-content: center;
  height: 200px;
  width: auto;
  overflow: hidden;
  border-radius: 10px;
  margin-left: 24px;
  margin-right: 24px;
}

.imageContainer img {
  object-fit: cover;
  width: 100%;
}
```

we must add `width:100%;` in img, otherwise, the image won't become smaller.
