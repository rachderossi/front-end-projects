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
# 3 column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/3-column-preview-card/Screenshot_1.png">

### Links

- Solution URL: [3 column preview card](https://rachderossi.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Web Design

### What I learned

```html
<section class="container" id="container">
  <div class="container-item sedans">
    <img src="img/icon-sedans.svg" alt="Sedans" />
    <h2>SEDANS</h2>
    <p>
      Choose a sedan for its affordability and excellent fuel economy. Ideal for
      cruising in the city or on your next road trip.
    </p>
    <nav>
      <a href="#">Learn More</a>
    </nav>
  </div>
</section>
```

```css
.container-item nav a {
  display: block;
  padding: 10px 30px 10px 30px;
  border: 2px solid hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
}
```

# Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/4-card-feature-section/Screenshot_1.png">

### Links

- Solution URL: [4 card feature section](https://rachderossi.github.io/4-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Web Design

### What I learned

```html
<section class="top-container" id="top-container">
  <div class="headings">
    <h1 class="first-line">
      <span style="color:hsl(229, 6%, 66%); font-weight: normal;">
        Reliable, efficient delivery
      </span>
    </h1>
    <h1 class="second-line"><strong> Powered by Technology </strong></h1>
    <p class="label">
      Our Artificial Intelligence powered tools use millions of project data
      points to ensure that your project is successful
    </p>
  </div>
</section>
```

```css
.cards-container {
  width: 1100px;
  height: auto;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  align-content: center;
  justify-content: center;
}
```
