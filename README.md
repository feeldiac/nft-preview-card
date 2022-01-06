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
  - [Continued development](#continued-development))
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![image](https://user-images.githubusercontent.com/75231007/147865582-f21ea177-c5ca-44ed-9be4-9dedecd61e90.png)

![image](https://user-images.githubusercontent.com/75231007/147865628-cbe66d03-c29a-46c7-acb6-3ba4f9d9580b.png)

![image](https://user-images.githubusercontent.com/75231007/147865593-c5892f83-6088-4086-9dec-c0ce6523b2e6.png)

### Links

- Solution URL: [Click here](https://www.frontendmentor.io/solutions/responsive-nft-card-using-flexbox-and-bem-eqzo3Hj0i)
- Live Site URL: [Click here](https://feeldiac.github.io/nft-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I had the opportunity to remenber some positioning and hover stuff. For example:

```css
.card--img::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: transparent;
    background-position: center center;
    border-radius: 1rem;
    cursor: pointer;
    transition: all 0.25s ease-in-out;
}
```

```css
.card--img:hover::before {
    background-color: rgba(0,255,247,0.45);
    background-image: url('../images/icon-view.svg');
    background-repeat: no-repeat;
}
```


### Continued development

In next projects it worth to practice using SASS and Grid.


## Author

- LinkedIn - [Fernando Díaz](https://www.linkedin.com/in/feeldiac1/)
- Frontend Mentor - [@feeldiac](https://www.frontendmentor.io/profile/feeldiac)
- Twitter - [@feeldiac](https://twitter.com/feeldiac)




