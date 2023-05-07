# Frontend Mentor - Results summary component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Results summary component solution](#frontend-mentor---results-summary-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

!['Screenshot desktop'](./screenshots/desktop.png)
!['Screenshot desktop:hover'](./screenshots/desktop-hover.png)
!['Screenshot mobile'](./screenshots/mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/maciej-szeremeta/Product-preview-card-component)
- Live Site URL: [GitHub Page](https://maciej-szeremeta.github.io/Product-preview-card-component)

## My process

### Built with

- HTML
- CSS variables
- SCSS
- BEM
- Flexbox

### What I learned

In the current projection, I have attempted to apply the SCSS.

```html
<div class="card__left">
  <img
    src="./images/image-product-desktop.jpg"
    alt="Chanel Paris Perfume"
    class="card__image"
  />
</div>
```

```scss
.card {
  &__left {
    width: 50%;
  }
  &__image {
    width: 100%;
    height: 100%;
  }
}
@media (max-width: 375px) {
  .card {
    &__left {
      width: 100%;
      height: 40%;
    }
    &__image {
      object-fit: cover;
    }
```

### Continued development

In the next task I will explore the secrets of the preprocessor.

### Useful resources

- [SCSS](https://sass-lang.com/) - This page helped me understand how SCSS works.

## Author

- Frontend Mentor - [@maciej-szeremeta](https://www.frontendmentor.io/profile/maciej-szeremeta)
