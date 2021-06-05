# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#Frontend-Mentor---Stats-preview-card-component-solution)
  - [Table of contents](#Table-of-contents)
  - [Overview](#Overview)
    - [The challenge](#The-challenge)
    - [Screenshots](#Screenshots)
    - [Links](#Links)
  - [My process](#My-process)
    - [Built with](#Built-with)
    - [What I learned](#What-I-learned)
    - [Continued development](#Continued-development)
  - [Author](#Author)
  - [Acknowledgments](#Acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

![](./images/screenshot-1.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [BEM](http://getbem.com/) methodology
- [FIGMA](https://www.figma.com/file/fP6FiaFM33O5A5XJvOq5MR/stats-preview-card-component-main?node-id=0%3A1) 

### What I learned

- Setting an image as a background and adding filter effect to it. 
  
```css
.card__img-container {
    background-color: var(--purpleish);
    background-image: url(/images/image-header-mobile.jpg);
    background-blend-mode: multiply;
    background-size: cover;
}
```
  
  The result would be similar to this :

![](images/screenshot-2.png)

- BEM naming convention : 
  
```html
<div class="card">
  
  <div class="card__img-container">...</div>

    <div class="card__main-content">
      <header class="card__header">...</header>
      <p class="card__description">...</p>
      <section class="card__stat">...</section>
    </div>

</div>
```

- Create a Figma sketch from scratch (link to my draft : [https://bit.ly/2TJ6f0M](https://bit.ly/2TJ6f0M) ) 
- Working with Git and Github

### Continued development

- CSS Grid
- BEM methodology
- Working with a CSS preprocessor like SASS

## Author

- Frontend Mentor - [@yorline](https://www.frontendmentor.io/profile/yorline)


## Acknowledgments

Thanks to Frontend Mentor for such great work and to the encouraging community.


