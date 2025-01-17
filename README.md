# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-landing-page-pCuXz8B8Cf)
- Live Site URL: [GitHub Pages](https://valeriamontoya.github.io/skilled-elearning-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Syntactically Awesome Style Sheets](https://sass-lang.com/)

### What I learned

For this project, I created functions to handle font sizes and spacings, making it easier to apply consistent styles across the project. Using Sass helped me maintain a clean and organized stylesheet 🤓

```scss
@function font-size($device, $index) {
  @if $device == desktop {
    @return nth($font-sizes-desktop, $index);
  } @else if $device == tablet-mobile {
    @return nth($font-sizes-tablet-mobile, $index);
  }
}

@function spacing($index) {
  @return nth($spacings, $index);
}
```

### Useful resources

- [coolLabs Fonts](https://fonts.coollabs.io/) - This is a wonderful privacy-friendly alternative for Google Fonts. It's really easy to use, give it a try! 👀

## Author

- Frontend Mentor - [@ValeriaMontoya](https://www.frontendmentor.io/profile/ValeriaMontoya)
- Twitter - [@val_smf](https://twitter.com/val_smf)