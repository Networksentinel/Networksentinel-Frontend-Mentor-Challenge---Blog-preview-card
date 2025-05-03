# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).
## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./src/images/Final%20project%20screenshot.png)

### Links
- [Solution:](https://www.frontendmentor.io/solutions/blog-preview-card-using-htmlcssvite-aqTKwaes1Y)
- [Live Site:](https://networksentinel.github.io/Networksentinel-Frontend-Mentor-Challenge---Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- Modular CSS
- CSS custom properties
- Flexbox
- [Vite](https://vite.dev/) - Frontend built tool

### What I learned

I already knew how to use clamp() for creating fluid layouts, but in this project I learned how to incorporate the fixed design values into the clamp() function. This allowed the layout to scale with the screen size while staying within the original design constraints.

Here’s an example showing how I applied it to the size of the main card component:

```css
.card {
  width: clamp(327px, 26.67vw, 384px);
  height: clamp(501px, 36.25vw, 522px);
}
```
If you want to know how to calculated those values, just ask 🙂 I’ll be happy to explain.
