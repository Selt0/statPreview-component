# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screenshot%202022-06-06%20114703.png)

### Links

- Live Site URL: [https://selt0.github.io/statPreview-component/](https://selt0.github.io/statPreview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I was able to add my own overlay to the image and use img src set to load the appropriate image depending on the users device

```html
      <section class="right-side">
        <div class="layer"></div>
        <img alt="people working on a pc"
             srcset="./images/image-header-mobile.jpg 1x,
             ./images/image-header-desktop.jpg 2x">
      </section>
```

## Author

- Website - [Michael Martinez](https://michael-martinez.netlify.app/)
- Twitter - [@MMocomochi](https://twitter.com/MMocomochi)
