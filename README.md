## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover and focus states for interactive elements

### Links


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```html
```using picture tag, for responsive img
<picture class="product_image">
      <source media="(max-width: 768px)" srcset="/images/image-product-mobile.jpg">
      <img src="/images/image-product-desktop.jpg" alt="A floral, solar and voluptuous interpretation composed by Olivier Polge, 
      Perfumer-Creator for the House of CHANEL.">
</picture>
```
```css
```using css flexbox property instead of margin and padding in spacing elements... to achieve equal spaces

.product_content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 2rem;
}

```for small screen sizes

.product .product_content {
    padding: 1.5rem;
    gap: 1rem;
}

using flexbox for adding icons on buttons instead of the traditional absolute positioning
```
### Continued development

focusing more on flexbox and grid, on when to use...and how to use it propely, also other type of responsive spacing of elements..

### Useful resources

https://youtu.be/B2WL6KkqhLQ -- this help me gives an idea on how to use flexbox on spacing elements instead of padding and margin. Grid for responsive layouts and how to use the picture tag for responsive images.

https://developer.mozilla.org/en-US/docs/Web/CSS/gap

## Author

https://www.frontendmentor.io/profile/akosimakoy

## Acknowledgments

thanks to kevin powell youtube tutorial, I got some idea on how to do the challenge

