# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

I learned how to add gap between unorder list and remove the first gap.

```css
li {
  margin-top: 16px;
}

li:first-child {
  margin-top: 0px;
}
```

I also learned how to change the text color of `<a>` element when the mouse hover on the `<li>` element.

We can set the color in `<a>` element to inherit, then when can directly change the color in `<li>`

```css
li:hover {
  background-color: var(--Green);
  color: var(--Dark-Grey);
}

li a {
  color: inherit;
}
```
