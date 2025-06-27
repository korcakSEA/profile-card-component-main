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
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./![alt text](image.png))

### Links

- Solution URL: (https://github.com/korcakSEA/profile-card-component-main.git)
- Live Site URL: (https://korcaksea.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned

Most difficult part is placing background images for me.

To see positioning, you can see the code snippets below.I guess It is more responsive than using percentges or pixel:

```css
    background-image: url('./images/bg-pattern-top.svg'),
                  url('./images/bg-pattern-bottom.svg');
    background-repeat: no-repeat, no-repeat;
    background-position: bottom -45vh right 45vw, top 40vh left 40vw;
```
```css
    /* Centering with Positioned layout */
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
```

## Author

- Frontend Mentor - [@korcakSEA](https://www.frontendmentor.io/profile/korcakSEA)


