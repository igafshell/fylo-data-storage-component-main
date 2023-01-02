# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful things](#Useful things)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screenshot](./images/screenshot.png)

### Links

- Solution URL: [Here](https://your-solution-url.com)
- Live Site URL: [Here](https://igafshell.github.io/fylo-data-storage-component-main/)

## My process

### Built with

- Basic HTML
- SCSS
- BEM markup

### What I learned

Positioning the message element was a bit of a struggle and I learned a lot how to use negative values with margins.

### Useful things

**For the responsive design, I used expresssions like:**
- `calc([fixed value] + [small responsive value])`

Example: `calc(7rem, .5vw)`

It's very useful for elements like text that need only slight changes in size, so this way you don't need to bother with media queries, keeping the code cleaner

- `max/min/clamp([responsive value],  [fixed value limit])`

Example: `min/max(30vw, 20rem)` 

It stops at 20rem if 30vw is bigger/smaller than that and acts as a max/min-width for the element. Useful to keep the code clean and avoid extra media queries

### Continued development

I'll continue to learn SCSS and build projects.

## Author

- Github - [igafshell](https://github.com/igafshell)
- Frontend Mentor - [@igafshell](https://www.frontendmentor.io/profile/igafshell)
- Twitter - [@igafshell](https://www.twitter.com/igafshell)

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io) for the awesome project!
