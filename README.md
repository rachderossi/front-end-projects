# Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/stats-preview-card/Screenshot.png">

### Links

- Solution URL: [stats preview card](https://rachderossi.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Web Design

### What I learned

```html
<div class="container info">
  <div class="item">
    <ul>
      <li class="heading">10k+</li>
      <li>Companies</li>
    </ul>
  </div>
</div>
```

```css
.header-intro img {
  flex: 1 1 160px;
  float: center;
  margin: 0px 0px;
  filter: grayscale(100%) brightness(40%) sepia(300%) hue-rotate(240deg)
    saturate(400%) contrast(0.9) opacity(500);
  border-radius: 5px;
}
```
