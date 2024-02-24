# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This was a fun one. designed Mobile-First using CSS Grid and Flexbox to get the desired layout and to 
change it easily on desktop view using a media query of min-width 1000px.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

#### Mobile

![Mobile Screenshot](./screenshot_mobile.png)

#### Desktop

![Desktop Screenshot](./screenshot_desktop.png)

### Links

- Solution URL: [Solution Url](https://www.frontendmentor.io/solutions/mobilefirst-design-using-css-grid-flexbox-and-media-queries-NQ-OF0ALV6)
- Live Site URL: [Live Site Url](https://frontendmentor-ilyesab.github.io/single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using CSS Grid and Flexbox to achieve the desired layout and change it easily depending on the viewport
width.

I also for the first time used a bit of box-shadows for the container and the button. I didn't feel the need to add it. but I thought why not? I'm not sure if it made it more good looking or more bad looking.

There was also something that I discovered on this challenge which requires a border-radius for the top edges and the bottom edges of the container.

In the last challenge I acheived that by applying a boder-radius to the top edges of the first child of the container and the bottom edges of the last child.

However in this one I applied the border-radius to the parent and used `overflow: hidden;` to enforce the border-radius on the children (e.g anything that is outside the parent is hidden).

### Continued development

I'd like to continue practicing building different layouts using CSS Grid and Flexbox.

### Useful resources

- [Box Shadow Generator](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_backgrounds_and_borders/Box-shadow_generator) - This helped me to visualize different box-shadow configurations and to honestly better understand the property.

## Author
- Frontend Mentor - [@ilyesab](https://www.frontendmentor.io/profile/ilyesab)
