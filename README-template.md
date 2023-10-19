# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/nft-preview-card-component-main/mydesign/screenshot.jpg)

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

## What I learned

## Structuring HTML

#### Html code 
```html
  <div class="card">
    <div class="header">
      <img 
        src="images/image-equilibrium.jpg" 
        alt="card image"
        class="cover">
    </div>
    <h2 class="title">
      Equilibrium #3429
    </h2>
    <p class="body">
      Our Equilibrium collection
      promotes balance and calm.
    </p>
    <div class="details">
      <p class="currency">
        <img 
          src="images/icon-ethereum.svg"
          alt="">
        0.041 ETH
      </p>
      <p class="time">
        <img
          src="images/icon-clock.svg" 
          alt="">
        3 days left
      </p>
    </div>
    <div class="author">
      <img 
        src="images/image-avatar.png" 
        alt="author pic"
        class="profile">
      <p>
        Creation of
        <span class="name">Jules Wyvern</span>
      </p>
    </div>

```

## Css Variables

#### Css code
```css
:root {
  --main-bg: hsl(217, 54%, 11%);
  --card-bg: hsl(216, 50%, 16%);
  --line-cl: hsl(215, 32%, 27%);
  --cl-soft: hsl(215, 51%, 70%);
  --cl-cyan: hsl(178, 100%, 50%);
  --cl-white: hsl(0, 0%, 100%);
  --overlay: hsl(178, 100%, 50%, .5);

  --fw-300: 300;
  --fw-400: 400;
  --fw-600: 600;

  --fz-base: 18px;

  --sm: 375px;
  --lg: 1440px;
}

```

- Created css variables from the style guide.
- Helps to create a consise and consistent look in the card
-  Also kept my code more maintainable in the long run.


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development


I would love to sharpen my skills creation of more UI Components like nav-bars menus dropdowns etc...


### Useful resources

- [Kelvin Powell's turning design to code video on youtube](https://youtu.be/kmFr_8U81vU?si=meaoPPD8GDg49ULv) - This helped me gain more insight on how to approach the challenge. I really liked this pattern and will use it going forward.

## Author

- Linkedn - [David Imafidon](https://www.linkedin.com/in/david-imafidon-202289222)
- Frontend Mentor - [@Davemafy](https://www.frontendmentor.io/profile/davemafy)
- Twitter - [@david_imafidon8](https://www.twitter.com/david_imafidon8)
- Facebook - [David Imafidon](https://www.facebook.com/profile.php?id=100073958401432&mibextid=ZbWKwL)

## Acknowledgment
Giving a big shoutout yo kelvin powell
on his video about effectively turning figma design files to well wirttem css code.
