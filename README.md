# Frontend Mentor - Product preview card component solution

This is my solution to the Product preview card component challenge on Frontend Mentor. The project helped me practice responsive layouts, semantic HTML, typography systems, CSS variables, and interactive button states.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product preview card screenshot](preview-mobile.png)
![Product preview card screenshot](preview-desktop.png)

### Links

- Solution URL: https://github.com/julie30/product-preview-card
- Live Site URL: https://julie30.github.io/product-preview-card/

---

## My process

### Built with

- Semantic HTML5
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow
- Responsive images using the `picture` element
- Google Fonts

---

## What I learned

During this project I practiced:

- Creating responsive card layouts
- Using the `picture` element for different mobile and desktop images
- Building reusable spacing and typography systems
- Combining Grid and Flexbox layouts
- Styling interactive button hover and focus states
- Working with custom typography and letter spacing
- Managing image scaling with `object-fit`

Example of variables used in the project:

```css
:root {
  --green: #3d8168;
  --green-hover: #1a4032;

  --font-heading: "Fraunces", serif;
  --font-body: "Montserrat", sans-serif;

  --spacing-24: 1.5rem;
  --spacing-32: 2rem;
}
````
````
<picture>
  <source
    srcset="images/image-product-desktop.jpg"
    media="(min-width: 48rem)"
  >

  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Essence Eau De Parfum bottle"
  >
</picture>
````

Continued development

In future projects I want to continue improving:

Responsive layouts
Accessibility
Component structure
CSS architecture
Interactive UI states
Cleaner responsive image handling
Useful resources
https://developer.mozilla.org/
https://css-tricks.com/
https://frontendmentor.io/

Author
Frontend Mentor - https://www.frontendmentor.io/profile/Julie30
