# Frontend Mentor - Huddle landing solution by Maame

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Solution URL: [Maame's Huddle Landing Page solution](https://github.com/mobonamensa/fem_huddle-landing-page)
- Live Site URL: [Huddle landing Page](https://mbonamensa.github.io/fem_huddle-landing-page)
- Figma file: [I created my own figma file](https://www.figma.com/file/6MMnRZacTFuO0UJGSTU0U8/Frontend-Mentor---FAQ-Accordion-Card?node-id=0%3A1&t=8gMJQ0Wz7Dc2fDkR-1)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- Grids
- Mobile-first workflow

### What I learned

Building this landing page taught me the importance of planning the structure of your page and the markup to use before actually coding. I found myself going back to the markup to make changes to fit the styles I wanted to implement. I practiced form validation with just CSS by using the `:invalid` psuedo selector. Here's the code I used: 


```html
  <form action="">
    <input type="email" id="email" placeholder="Email">
    <span></span>
    <button>Subscribe</button>
  </form>
```

```CSS
  &:focus:invalid {
    outline: 1px solid $invalid;

    + span::before {
      content: "Check your email please";
      position: absolute;
      left: 0;
      bottom: 34px;
      font-size: 0.6rem;
      color: $invalid;
    }
  }
```

The outcome:

![](./img/Screenshot%20(67).png)

### Continued development

I'd want to practice the various types form validation and get familiar with them.

### Useful resources

- [Styling Form Inputs in CSS](https://www.digitalocean.com/community/tutorials/css-styling-form-input-validity) 
- [CSS Invalid Syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/:invalid) 


## Author

- Website - [Maame Yaa Serwaa Bona-Mensa](https://mbonamensa.netlify.app)
- Frontend Mentor - [@mbonamensa](https://www.frontendmentor.io/profile/mbonamensa)
- Twitter - [@mys_bm](https://www.twitter.com/mys_bm)