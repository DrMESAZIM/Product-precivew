# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/screenshot.png)
![](images/screenshot_mobile.png)

### Links

- Solution URL: [Github](https://github.com/jeremylloyd/frontend-mentor-product-preview-card-component)
- Live Site URL: [Hosted on Github Pages](https://jeremylloyd.github.io/frontend-mentor-product-preview-card-component/)

## My process

### Built with

- Plain old HTML5
- Plain old CSS

### What I learned

- Hover transitions:
  - ```
    .add-to-cart:hover {
      background-color: hsl(158, 44%, 31%);
    }
    ```
  - `transition: 300ms` on the parent element
- Semantic HTML5 with `<footer>`, `<section>`, `<article>` and `<figure>`
- Overwriting base styles
  - ```
    *, *:before, *:after {
      box-sizing: border-box;
      margin: 0px;
      font-family: 'Montserrat';
      text-decoration: none;
    }
    ```
  - Adding `border: 1px dashed black;` for debugging layout
- Using only one of the `max-width` or `width` CSS properties. Using one makes overwriting them in media queries easier