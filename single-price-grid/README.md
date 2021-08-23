# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/single-price-grid-component/Screenshot_1.png">

### Links

- Solution URL: [4 card feature section](https://rachderossi.github.io/single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Web Design

### What I learned

```html
<div class="container-item left">
  <h2>Monthly Subscription</h2>
  <span> &dollar;29 <sup> per month</sup></span>
  <p>Full access for less than &dollar;1 a day</p>
  <nav>
    <a href="#">Sign Up</a>
  </nav>
</div>
```

```css
.container-item {
  flex: 1 1 260px;
  margin: 0px;
  padding: 50px;
  box-shadow: 0 8px 30px -10px hsl(229, 6%, 66%);
}

.container .container-item:nth-child(3) {
  order: -1;
}
.container .container-item:nth-child(2) {
  order: -3;
}
```
