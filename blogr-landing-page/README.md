# Blogr Landing Page

This is a solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add your repository URL here]
- Live Site URL: [Add your live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Overpass](https://fonts.google.com/specimen/Overpass) & [Ubuntu](https://fonts.google.com/specimen/Ubuntu) fonts

### What I learned

I used CSS variables to manage the theme colors and leveraged `details` and `summary` tags for accessible, JavaScript-free dropdown menus.

```html
<details>
  <summary>Product</summary>
  <ul class="dropdown-menu">...</ul>
</details>
```

```css
:root {
  --clr-primary-light-red: hsl(356, 100%, 66%);
}
```



