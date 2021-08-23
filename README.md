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

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/stats-preview-card/Screenshot.png">

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

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/3-column-preview-card/Screenshot_1.png">

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

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/4-card-feature-section/Screenshot_1.png">

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

# Single price grid component solution

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

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/single-price-grid/Screenshot_1.png">

### Links

- Solution URL: [Single price grid](https://rachderossi.github.io/single-price-grid/)

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
# Bikcraft

My first big project using HTML, CSS and basic JavaScript. I built the entire wireframe using Adobe XD, but the project came from my front-end classes.

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/bikcraft/Screenshot_1.png">

### Links

- Solution URL: [Bikcraft](https://rachderossi.github.io/bikcraft/)

# FlexBlog

My second project using HTML and CSS Flexbox. I built the entire wireframe using Adobe XD, but the project came from my front-end classes.

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/flexblog/Screenshot_1.png">

### Links

- Solution URL: [FlexBlog](https://rachderossi.github.io/flexblog/)

# Wildbeast

My third project using HTML and CSS Grid Layout. 

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-projects/blob/main/wildbeast/Screenshot_1.png">

### Links

- Solution URL: [Wildbeast](https://rachderossi.github.io/wildbeast/)
