# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/shidqiiii/Interactive-rating-component)
- Live Site URL: [Netlify](https://rating-card-dev-arunika.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Javascript ES6

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Learn to use semantic HTML5 markup and CSS with javascript to save state.

To see how you can add code snippets, see below:

```js
rating.forEach((element) => {
  element.addEventListener("click", function () {
    rating.forEach((num) => {
      num.classList.remove("selected");

      this.classList.add("selected");
      number = this.id;
    });
    console.log(number);
  });
});
```

## Author

- Website - [Arunika](https://arunikaproject.netlify.app/)
- Frontend Mentor - [@shidqiiii](https://www.frontendmentor.io/profile/shidqiiii)
