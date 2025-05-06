# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Ayokanmi-Adejola/Blog-Preview-Card)
- Live Site URL: [Live Site](https://ayokanmi-adejola.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts - Figtree font

### What I learned

This project helped me practice creating interactive card components with hover effects. I learned how to implement smooth transitions and shadow effects to create a more engaging user experience.

Some code snippets I'm proud of:

```html
<article class="card">
  <img src="./assets/images/illustration-article.svg" alt="Article illustration" class="card-image">
  <div class="card-content">
    <span class="tag">Learning</span>
    <p class="date">Published 21 Dec 2023</p>
    <h1 class="title">HTML & CSS foundations</h1>
    <p class="description">These languages are the backbone of every website, defining structure, content, and presentation.</p>
    <div class="author">
      <img src="./assets/images/image-avatar.webp" alt="Greg Hooper" class="author-image">
      <span class="author-name">Greg Hooper</span>
    </div>
  </div>
</article>
```

```css
.card {
  background-color: var(--white);
  border-radius: 1rem;
  overflow: hidden;
  max-width: 380px;
  border: 1px solid var(--gray-950);
  box-shadow: 8px 8px 0 var(--gray-950);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.title:hover {
  color: var(--yellow);
}
```

### Continued development

In future projects, I'd like to focus more on:
- Implementing more complex animations
- Creating responsive designs for a wider range of devices
- Exploring CSS Grid for more complex layouts

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me understand CSS transitions and transforms better.
- [CSS-Tricks](https://css-tricks.com/) - Great resource for flexbox and general CSS techniques.

## Author

- Website - [Ayokanmi Adejola](https://ayokanmi-adejola-portfolio.netlify.app/)
- Frontend Mentor - [Ayokanmi Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
