# Frontend Mentor - Order Summary Card Solution

This is a solution to the [Order Summary Card Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://github.com/NelPascual/nft-preview-card-component)
- Live Site URL: [Add live site URL here](https://nft-preview-card-nelpascual.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Among the things I was able to learn and practice in this project are:

- Regarding the image that is placed as background, I only thought of inserting it in the <body> tag, using the background-image: linear-gradient(), it is sure that there is a better way, but for this challenge I did it that way.

Here are some examples:

```html
<body></body>
```
```css
body {
  display: flex;
  flex-direction: column;
  background-color: var(--pale-blue);
  background-image: linear-gradient(to bottom, transparent 50%, transparent 50%, transparent 100%), url(../img/pattern-background-mobile.svg);
  background-position: top;
  background-repeat: no-repeat;
  background-size: 100%, 63.9rem;
  font-family: 'Red Hat Display', sans-serif;
  height: 100vh;
  margin: 0;
  padding: 0;
}
```
```css
@media only screen and (min-width: 640px) {

body {
  background-image: linear-gradient(to top, transparent 50%, transparent 50%, transparent 100%), url(../img/pattern-background-desktop.svg);
  background-position: top;
  background-repeat: no-repeat;
  background-size: 100%, 100vw;
}
}
```

### Continued development

This is my fourth project done on this platform, I will continue to apply what I have learned in the following projects, taking advantage of each of the challenges, as each of them always challenges us to learn something new and correct mistakes made in previous projects.

## Acknowledgments

I thank Frontend Mentor for providing free resources to put into practice what I have learned, and above all a place to show them.
