# Frontend Mentor - Single price grid component solution 👋🏾

This the [Single price grid component](design/desktop-preview.jpg). Thanks for checking it out

## Table of contents 🧳

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is a welcoming subscription banner component built mainly with CSS Grid.

### The objective

Users are be able to:

- View the optimal layout for the sign up banner depending on their device's screen size.
- See a slight button movement when they hover on the Sign Up 'call-to-action' button.

### Screenshot

![Mobile View](design/mobile-design.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/franco2ke/single-price-grid-component)
- Live Site URL: [Add live site URL here](https://franco2ke.github.io/single-price-grid-component/)

## My process

I started by creating the layout container via CSS Grid. It was a little tougher than I thought centering the component without using absolute positioning. Next step was to create the desktop view afterwhich I scaled down and ensured it was looking good at all sizes between 1440px to 320px. Breakpoints used; 800px and 600px.

Also added a small transition on the signup button to emphasize the hover state.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop first workflow
- [SASS](https://sass-guidelin.es) - Sassy Sass
- [BEM](http://getbem.com/introduction/) - BEM methodology

### What I learned

I started by creating the layout container via CSS Grid. It was a little tougher than I thought centering the component without using absolute positioning. Next step was to create the desktop view afterwhich I scaled down and ensured it was looking good at all sizes between 1440px to 320px;

I learn't that CSS Grid seems to make work easier when setting up layouts, however the resizing or scaling with different screen widths needs special attention in order to make things flow well. I require more practice on minmax, min-content and use of fractional units.

Also using the alpha transparency really helped with getting alternate display shades, for example the background color on the benefits section.

I also found writing the readme and inserting code comments, slightly challenging though it is much easier as the README template has been provided and I'm comparing with readme's solutions posted by others.

```css
.signup__benefits {
  background-color: rgba(42, 178, 175, 0.9);
}
```

### Useful resources

- [Github Publishing](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) - This simple article helped me with the details of posting my solution online. I found it quite simple to post using github pages.

## Author

- Website - [Francis Wafula](https://www.paon.co.ke)
- Frontend Mentor - [@franco2ke](https://www.frontendmentor.io/profile/franco2ke)
- Twitter - [@franco2ke](https://twitter.com/franco2ke)

Happy Coding 🎯
