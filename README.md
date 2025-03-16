# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

Responsive blog preview card with reduced font size on mobile version

### The challenge

Reduce font size for smaller screens without using media queries.

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/Screenshot.jpg)

### Links

- Solution URL: [https://github.com/mci3x/Blog-Preview-Card](https://github.com/mci3x/Blog-Preview-Card)
- Live Site URL: [https://mci3x.github.io/Blog-Preview-Card/](https://mci3x.github.io/Blog-Preview-Card/)

## My process

Started with a HTML and made my way from the top in CSS.
At first I used pixels trying to achieve exact look like in Figma.
After tweaking and resolving flexbox issues I've converted all necessary units form px to rem.
Spent some time with setting up media queries and after that went on to resizing fonts without using them.
That was completely new to me and after fair amount of googling I started to test `clamp()` function.
It involved a lot of calculations and frustrations but in the end it worked.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- I know more about responsive design and practical flexbox use
- Never used custom properties before
- `clamp()` function was completely new to me
  I don't know if it was that what were supposed to be used to "reduce font size for smaller screens without using media queries" but I'm happy with the effect and it is definitely new tool in my toolbox

### Continued development

Proper responsive design practices, using custom properties, getting comfortable with media queries, Flexbox, Grid, Git

### Useful resources

Good old google search which usually leads to MDN, CSS Tricks or stackoverflow.
VSCode copilot came in handy with calculations

## Author

- GitHub - [mci3x](https://github.com/mci3x)
- Frontend Mentor - [@mci3x](https://www.frontendmentor.io/profile/mci3x)
- Bluesky - [@mci3x.bsky.social](https://bsky.app/profile/mci3x.bsky.social)
- X - [@mci3x](https://www.x.com/mci3x)

## Acknowledgments

I often use final project of the Jonas Schmedtmann's course on Udemy as a point of reference.
His "Build Responsive Real-World Websites with HTML and CSS" course is a solid starting point
