# Frontend Mentor - Blogr landing page solution

This is a solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![DESKTOP PAGE](\images\Blogr-desktop.png)
![MOBILE PAGE](\images\Blogr-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript

### What I learned

-- how to manipulate wit javascript using event Listerners and DOM

```js
//ACCORDION
var acc = document.getElementsByClassName("Navbar__accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function () {
    /* Toggle between adding and removing the "active" class,
    to highlight the button that controls the panel */
    this.classList.toggle("active");

    /* Toggle between hiding and showing the active panel */
    var panel = this.nextElementSibling;
    if (panel.style.display === "flex") {
      panel.style.display = "none";
    } else {
      panel.style.display = "flex";
    }
  });
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

- WRITING JAVAVSCRIPT COMFORTABLY
- CLEAN CODE

### Useful resources

- [W3SCHOOLS](https://www.w3schools.com/howto/default.html) - This helped me implement some features in javascipt and CSS

## Author

- Website - [MICHAEL ADEBAMBO](https://www.your-site.com)
- Frontend Mentor - [@BLAZING MIKE](https://www.frontendmentor.io/profile/Blazing-Mike)
- Twitter - [@BLAZING MIKE](https://www.twitter.com/Mike0xygen1)
