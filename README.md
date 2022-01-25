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

![](./)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

The new thing i leant here is how to create overlay on hover status of an elemet.

```css
.overlay {
     width: 100%;
     height: 99%;
     border-radius: 10px;
     position: absolute;
     top: 0;
     opacity: 0;
     background: hsl(178, 100%, 50%);
     transition: all 0.5s ease-in;
     display: flex;
     justify-content: center;
     align-items: center;
     
}

.img-container:hover .overlay {
     opacity: .3;
     transition: all 0.5s ease-in-out;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development


### Useful resources


## Author

- LinkedIn - [Hassan A Yahya](https://www.linkedin.com/in/hassan-a-yahya-729558177/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BS472eQnDRuKrz5YeC1CWhw%3D%3D)
- Frontend Mentor - [@hsn-ng](https://www.frontendmentor.io/profile/hsn-ng)
- Twitter - [@bro_riyadh](https://www.twitter.com/bro_riyadh)

## Acknowledgments

