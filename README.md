# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: [https://github.com/gchristofferson/3-column-preview-card-component](https://github.com/gchristofferson/3-column-preview-card-component)
- Live Site URL: [https://3-column-preview-card-component-olive.vercel.app/](https://3-column-preview-card-component-olive.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

While working on this project I really got a chance to practice creating re-usable components.  To do this I created a block style for the 'card' component, then I added modifier classes for styling the differences between the cards.  I tried following the BEM naming convention.

Check these code snippets below. Here is the html for my card block component with a modifier class of 'card--1'.

```html
<div class="card card--1">
  <div class="card__content">
    <img src="./images/icon-sedans.svg" alt="" class="card__icon">
    <h2 class="card__title">Sedans</h2>
    <p class="card__text">Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city
      or on your next road trip.</p>
    <button class="card__btn">Learn More</button>
  </div>
</div>
```
Here is the css for my card block component:
```css
.card {
  width: 327px;
  height: 442px;
  border-radius: 8px;
  color: var(--p-font-clr);
  background: darkgray;
}
```
Here is an example of the 'card--1' modifier class.  I had one for each of the 3 cards in this project
```css
.card--1 {
  background-color: var(--primary-clr-1);
}
```

### Continued development

In future projects I want to continue focusing on creating reusable component styles and adopting the BEM naming convention as much as possible in my own projects.  I found this really organized my work and made debugging easy.  I also added a subtle animation to the button:hover and I want to continue refining this technique in other areas of future projects while not sacrificing performance.

### Useful resources

- [BEM 101](https://css-tricks.com/bem-101/) - This is an amazing article that really helped me to understand what the BEM naming convention is and why it is useful. I'd definitely recommend this article to anyone still deciding what naming convention to adopt. I really liked how easy BEM made creating new styles for my components and will use it going forward.


## Author

- Frontend Mentor - [@gchristofferson](https://www.frontendmentor.io/profile/gchristofferson)
- Twitter - [@GreggChristoff2](https://twitter.com/GreggChristoff2)

