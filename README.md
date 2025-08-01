# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the design in two main responsive layouts: small screens (around 350px) and large screens (above 1200px).

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/KonieK981/bento-grid](https://github.com/KonieK981/bento-grid)
- Live Site URL: [https://bento-grid-mp3y.vercel.app/](https://bento-grid-mp3y.vercel.app/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

I had the opportunity to practice grid layout and image positioning. The following section was particularly challenging because the almost transparent background of this image did not adapt well to the container's background. I applied some gradients and masking to different areas of the image to achieve a better effect.

```html
<article class="card-2">
  <img
    src="/images/illustration-multiple-platforms.webp"
    alt="Multiple platforms illustration"
  />
  <h3 class="title">Manage multiple accounts and platforms.</h3>
</article>
```

```css
.card-2 img {
  width: 100%;
  height: auto;
  display: block;
  -webkit-mask-image: radial-gradient(...);
  /* ...other styles... */
}
```

### Continued Development

To further improve the app, the next step would be to make it fully responsive, as I only worked on the smallest and largest breakpoints. I am still unsure about the best way to position images and how to adapt images with shadows or semi-transparent backgrounds so they fit nicely within their containers.

## Author

- Frontend Mentor - [@KonieK981](https://www.frontendmentor.io/profile/KonieK981)
