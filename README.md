# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- View the recipe page layout optimized for their device's screen size
- See hover states for interactive elements

### Screenshot

![Recipe Page Screenshot](./design/desktop-design.jpg)

![Recipe Page Screenshot for Mobile](./design/mobile-design.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/recipe-page-solution-Adis_h_8tO](https://www.frontendmentor.io/solutions/recipe-page-solution-Adis_h_8tO)
- Live Site URL: [https://recipe-page-solution-101.netlify.app/](https://recipe-page-solution-101.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS Variables)
- Flexbox
- Mobile-first workflow
- Google Fonts (Young Serif & Outfit)
- Responsive design principles

### What I learned

During this project, I reinforced my knowledge of several key concepts:

**CSS Custom Properties**: Using CSS variables for consistent color management throughout the project made the design system more maintainable.

```css
:root {
  --white: hsl(0, 0%, 100%);
  --stone-100: hsl(30, 54%, 90%);
  --rose-800: hsl(332, 51%, 32%);
}
```

**Semantic HTML Structure**: Implementing proper semantic elements like `<main>`, `<section>`, and appropriate heading hierarchy for better accessibility.

```html
<main class="recipe-card">
  <section class="ingredients">
    <h2>Ingredients</h2>
    <!-- content -->
  </section>
</main>
```

**Custom List Styling**: Creating custom bullet points and numbered lists using CSS pseudo-elements:

```css
.ingredients li::before {
  content: "•";
  color: var(--brown-800);
  position: absolute;
  left: 0;
}
```

**Responsive Design**: Implementing mobile-first approach with media queries to ensure the design works well across different screen sizes.

### Continued development

Areas I want to continue focusing on in future projects:

- **CSS Grid**: While this project used Flexbox effectively, I want to explore more complex layouts using CSS Grid
- **Advanced CSS animations**: Adding subtle micro-interactions to enhance user experience
- **Accessibility improvements**: Implementing better screen reader support and keyboard navigation
- **Performance optimization**: Optimizing images and CSS for better loading times

### Useful resources

- [MDN Web Docs - CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This helped me understand how to effectively use CSS variables
- [CSS-Tricks - Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - An excellent reference for Flexbox properties and usage
- [Google Fonts](https://fonts.google.com/) - Used for typography choices (Young Serif and Outfit fonts)

## Author

- Website - [Seyed Ahmad Gholami](https://www.linkedin.com/in/seyedahmaddv/)
- Frontend Mentor - [@seyedahmaddv](https://www.frontendmentor.io/profile/seyedahmaddv)
- LinkedIn - [Seyed Ahmad Gholami](https://www.linkedin.com/in/seyedahmaddv/)

---

**Challenge completed as part of Frontend Mentor's design-to-code challenges.**#
