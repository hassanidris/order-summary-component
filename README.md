# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot
![screenshot-127 0 0 1_5501-2021 11 28-19_27_32](https://user-images.githubusercontent.com/69512496/143776945-11da986a-0918-4a1a-9307-b72d3aefa592.png)


### Links
- Solution URL: https://github.com/hassanidris/order-summary-component
- Live Site URL: https://hassanidris.github.io/order-summary-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to build Mobile first before desktop

To see how you can add code snippets, see below:

```
@media (min-width: 375px) {
      body {
          background: url(/assets/img/pattern-background-desktop.svg) no-repeat top hsl(var(--clr-paleBlue));
      }

      .order__cta__cost--change:hover,
      .order__cta__cost--change:focus {
          text-decoration: none;
          color: hsl(var(--clr-desaturatedBlue));
          
      }

      .order__cta--proceed:hover,
      .order__cta--proceed:focus {
        background-color: hsl(var(--clr-desaturatedBlue));
      }

      .order__cta--cancel:hover,
      .order__cta--cancel:focus {
        color: hsl(var(--clr-darkBlue));
      }

  }
```

## Author

- Github - [hassanidris](https://github.com/hassanidris)
- Frontend Mentor - [@hassanidris](https://www.frontendmentor.io/profile/hassanidris)


