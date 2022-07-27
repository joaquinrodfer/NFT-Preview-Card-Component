# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- [Live Site URL](https://joaquinrodfer.github.io/NFT-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

It was very hard to me to implement the "hover" of the image:

```css
.div.img{
    display: flex;
    align-items: center;
    justify-content: center;

    margin-top: 25px;
    border-radius: 6px;
    max-height: 284.75px;
    background-color: hsl(178, 100%, 50%);
}

.div.img img.img.eye{
    position: absolute;
    z-index: 1;
}

.div.img img.img.equilibrium{
    z-index: 2;
    max-width: 100%;
    border-radius: 5px;
    cursor: pointer;
}

.div.img img.img.equilibrium:hover{
    opacity: 50%;
}
```

I´ll check other ways to make this work, because I didn´t end up satisfied.

## Author

- Frontend Mentor - [@joaquinrftech](https://www.frontendmentor.io/profile/joaquinrftech)
- Twitter - [@joaquinisreal](https://www.twitter.com/joaquinisreal)