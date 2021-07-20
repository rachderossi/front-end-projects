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
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

### Screenshot

Desktop preview
<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/stats-preview-card/screenshot1.png">

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```html
<section class="container info">
        <div class="item">
          <ul>
            <li>10k+</li>
            <li class="heading">Companies</li>
          </ul>
        </div>
</section>
  ```

```css
.header-intro img {
    flex: 1 1 160px;
    float: right;
    margin: 0 0px;
    height: 400px;
    width: 450px;
    filter: grayscale(100%) brightness(40%) sepia(300%) hue-rotate(240deg)
      saturate(400%) contrast(0.9) opacity(500);
    border-radius: 5px;
  }
```

### Continued development

Learn more about responsive web design,as you can see on my code I only made layout for screen size width 375px or 1440px.  I would like to make this work for any type of device size.
