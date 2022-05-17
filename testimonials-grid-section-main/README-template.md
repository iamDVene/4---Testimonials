# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](testimonials-devene-e.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

There were quite a few new concepts in this challenge.

Flexbox
Flexbox works well for aligning content within smaller divs/cards. For the reviewers names and images, I used flexbox.

```css
.reviewer{
  display: flex;
}
```

Setting max-width and max-height on images

Originally I only set the width on the reviewers images but noticed that the ratio would change at smaller screen widths. To maintain the size,
I fixed a max-width and max-height to the images. That helped to prevent the unneeded scaling.

```css
.reviewer img {
  border-radius: 50%;
  max-width: 30px;
  max-height: 30px;
}
```

### Continued development

nth-of-type and nth-of-child selectors

I still don't understand these concepts perfectly so in upcoming projects, I'll try to learn more about these.

### Useful resources

- [Background Image](https://www.w3schools.com/cssref/pr_background-position.asp) - I referenced the properties for background image from here. I've never had to position a Background image before so this was quite helpful in understanding how to do so.
- [CSS Selectors](https://www.w3schools.com/cssref/css_selectors.asp) - At this stage I tend to forget selectors so I reference this page quite frequently.

## Author

- Frontend Mentor - [@iamDVene](https://www.frontendmentor.io/profile/iamDVene)

## Acknowledgments

I was able to complete this challenge after completing Brad Traversy's "CSS Crash Course 2022"
