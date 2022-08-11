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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![NFT Card component](https://github.com/ejionaut/NFT-preview-card/blob/main/images/NFT%20Screenshot.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/nft-preview-card-component-KyLZe7XfCm)
- Live Site URL: [Netlify](https://poetic-dusk-6f0de1.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Was finally able to properly do image layering. With some help of other resources found online.
It was basically done with the position property and opacity manipulation.


```css
.Main-image-container {
  position: relative
}

.Image-to-layer {
  position: absolute;
  top: 0;
  left: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

### Continued development

From this point I want to further develop my CSS skills and get better at positioning. As well as master flex and grids.

### Useful resources

- [Image overlay](https://www.youtube.com/watch?v=exb2ab72Xhs) - Helped me with the hover overlay effect.

## Author

- Frontend Mentor - [@ejionaut](https://www.frontendmentor.io/profile/ejionaut)
