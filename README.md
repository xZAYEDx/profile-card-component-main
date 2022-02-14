# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided.

### Screenshot

- Desktop viewing
![image](https://user-images.githubusercontent.com/46198029/153934650-d39e9603-dbff-4ef4-9fdb-80459a309eba.png)

- Mobile view
![image](https://user-images.githubusercontent.com/46198029/153934817-8d002215-be86-4c60-889f-2f387ce896e4.png)

### Links

- Solution URL: [solution](https://github.com/xZAYEDx/profile-card-component-main)
- Live Site URL: [live site](https://xzayedx.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS custom properties
- Flexbox

### What I learned

- How to use two background images/svg for body and properly positioning it, that was a major task for me.
- how to use the :nth-child(n) selector, that matches every element that is the nth child, regardless of type, of its parent.

```css
  background-image: url(../images/bg-pattern-top.svg), url(../images/bg-pattern-bottom.svg);
  background-repeat: no-repeat;
  background-position: right 52vw bottom 35vh, left 48vw top 52vh;
```

```css
 &:nth-of-type(2) {
  padding-left: 48px;
 }
 &:last-of-type {
  padding-left: 58px;
 }
```

### Continued development

Background image postioning.

## Author

- Frontend Mentor - [@xZAYEDx](https://www.frontendmentor.io/profile/xZAYEDx)


## Acknowledgments

- Special thanks to [@anoshaahmed](https://www.frontendmentor.io/profile/anoshaahmed). Her solution helped me figure out how to add two svg's as background images and position it.
