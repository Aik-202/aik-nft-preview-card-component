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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshots/Screenshot%20(158).png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/css-flex-mobilefirst-workflow-semantic-html5-markup-9WAOCCGMvZ)
- Live Site URL: [Add live site URL here](https://aik-202.github.io/aik-nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Media Queries
- Flexbox
- Mobile-first workflow

### What I learned

I learnt how to perform fade in overlay, this is the first time I'm taking this kind of approach. I also took the mobile-first workflow approach, responsiveness was much easier! I wish to continue using this approach.

To see how you can add code snippets, see below:


```css
.svg {
    top: 40%;
    left: 42%;
    cursor: pointer;
    position: absolute;
    opacity: 0;
}

.hover {
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    cursor: pointer;
    position: absolute;
    background-color: hsl(178, 100%, 50%);
    opacity: 0;
}


.container>figure:hover .hover {
    opacity: 0.5;
    transition: 3s ease;
}

.container>figure:hover .svg {
    opacity: 1;
    transition: 3s ease;
}
```

### Useful resources

- [Example resource 1](https://www.w3schools.com/howto_css_image_overlay.asp) - This is an amazing article which helped me finally understand fade in overlay. I'd recommend it to anyone still learning this concept.


## Author
- Github - [@Aik-202](https://github.com/Aik-202/)
- Frontend Mentor - [@Aik-202](https://www.frontendmentor.io/profile/Aik-202)
- Twitter - [@chiomaikogwe](https://www.twitter.com/chiomaikogwe)

## Acknowledgement
I actually got this approach of the fade in overlay from a member of the frontend mentor's community.
