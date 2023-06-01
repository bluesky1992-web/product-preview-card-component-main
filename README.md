# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  
  
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
![desktop view](images/s-s-desktop.jpeg)

![mobile view](images/s-s-mobile.jpeg)


### Links

- Solution URL: [github.com/bluesky1992-web](https://github.com/bluesky1992-web/product-preview-card-component-main)
- Live Site URL: [bluesky1992-web.github.io](https://bluesky1992-web.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- Tailwindcss
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

it was a good opportunity to apply mobile first approach and i have learned how to show the images conditionally depends on the screen size with Tailwind css

```html
<img   
        class="w-0 lg:w-64 lg:rounded-tl-lg lg:rounded-bl-lg"
        src="./images/image-product-desktop.jpg"
        alt=" image-product-desktop"
      />
      <img
        class="w-64 lg:hidden rounded-tl-lg rounded-tr-lg"
        src="./images/image-product-mobile.jpg"
        alt="image-product-mobile "
      />
```






## Author

- Website - [Ali Ibrahim](https://bluesky1992-web.github.io/my-react-portfolio/#/)
- Frontend Mentor - [@bluesky1992-web](https://www.frontendmentor.io/profile/bluesky1992-web)



