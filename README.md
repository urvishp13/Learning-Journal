# Learning Journal

A blog site that allows an individual to keep record of their learning journey.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

This project is meant to teach all the workings of responsive design, such as relative units, CSS grid, and mobile-first design.

### Screenshot

Here are screenshots of the main page only.

![Desktop view](assets/screenshots/desktop-view.png)
![Mobile view](assets/screenshots/mobile-view.png)

### Links

Live site: [https://pathway-to-education.netlify.app/](https://pathway-to-education.netlify.app/)

## My process

Went through this page-by-page. The main focus was the CSS and, as there were many repeated structures across the pages, decided to modularize the CSS to make for DRYer (Don't-Repeat-Yourself) code.

### Built with

HTML, CSS

### What I learned

```css
@media (min-width: 67.8125rem) {
    
    header > .container {
        font-size: 1.47em;
    }

}
```
`em` units can be utilized in responsive design when dealing with different browser sizes. Utilizing `font-size` with `em` units in media queries will scale all the elements based in responsive units at smaller browser widths without having to alter their properties one-by-one in the larger-width media queries.

```css
.article > div {
    width: 52.625rem;
}

.article > .article-img-wrapper {
    justify-self: center;
    width: 100%;
}
```
Grid children can be given different widths. In the project, `article` is a grid. The width of the grid children was set to less than the grid's full-width, but the width of the image in the grid was made wider than it siblings. By doing this, it made the illusion that the image was flowing outside the bounds of the grid.

### Useful resources

Scrimba's Frontend Developer Bootcamp content on implicit grid.

## Author

GitHub: [https://github.com/urvishp13](https://github.com/urvishp13)