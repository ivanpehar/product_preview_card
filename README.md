# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size.
- See hover and focus states for interactive elements.

### Screenshot

![](./images/screenshot1.jpeg)
![](./images/screenshot2.jpeg)


### Links

- Solution URL: [GitHub Repository](https://github.com/ivanpehar/product_preview_card)
- Live Site URL: [Live Demo](https://ivanpehar.github.io/product_preview_card/)

## My process

### Built with

- Semantic HTML5
- CSS custom properties
- **CSS Grid & Flexbox**
- Mobile-first workflow

### What I learned

One major challenge I faced was **structuring the layout with CSS Grid**. Initially, the content wouldn’t stack properly when switching to mobile view. The problem was that I **forgot to define `grid-template-columns: 1fr;`** in my media query. After identifying this issue, I corrected it by applying the following:

/* ```css*/
@media (max-width: 430px) {
    .mc {
        display: grid;
        grid-template-columns: 1fr; /* This fixed the issue */
    }
}*/

## Continued development

For future projects, I want to:

- Improve my use of **CSS Grid** for better layout structuring.
- Experiment with **CSS animations** to enhance UI interactivity.
- Get more comfortable using **CSS media queries** to handle responsiveness efficiently.

## Useful resources

- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - Helped me understand how to structure grid layouts correctly.
- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Provided great visual explanations of grid behavior.

## Author

- **GitHub**: [ivanpehar](https://github.com/ivanpehar)
- **Frontend Mentor**: [@ivanpehar](https://www.frontendmentor.io/profile/ivanpehar)

## Acknowledgments

A big thanks to **Frontend Mentor** for providing these awesome challenges! 