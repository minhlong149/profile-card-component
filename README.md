# Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- [Solution](https://github.com/minhlong149/profile-card-component)
- [Live Site](https://github.com/minhlong149/profile-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Overlaying an image between 2 element:

```html
<section class="container">
  <div class="upper">
    <!-- Inside this is the image you want to overlay -->
    <img class="profile-picture" src="./images/image-victor.jpg">
  </div>
  <div class="lower"></div>
</section>
```
```css
.profile-picture {
  position: absolute;
  margin-bottom: -50px; /* Change this as you please to fit the content */
}
```

However, this only work if you know the height of the elements.

## Author

- Github - [Long Nguyen](https://github.com/minhlong149)
