# Frontend Mentor - Stats preview card component solution

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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./desktop-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/yiwenxx/Fronted-Mentor-Challenge)
- Live Site URL: [Add live site URL here](https://yiwenxx.github.io/Fronted-Mentor-Challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Since one word in the heading has a specific color that is different from others, to avoid creating a seperate div or class, I learned that adding a span element with style would work perfectly, which allowed me to change the color of the word "insights" to violet.

```html
<h1>
  <b
    >Get <span style="color: hsl(277, 64%, 61%)">insights</span> that help your
    business grow.</b
  >
</h1>
```

Also, to try to mimic the side image of the design preview, instead of simply adding a layer with some opacity, using a mix-blend-mode would do a better job to achieve this goal. I tried different blend mode and find the best one.

```css
.layer2 {
  background: var(--bg-light-violet);
  height: 100%;
  mix-blend-mode: color-burn;
}
```

### Useful resources

- [Mix-Blend-Mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - This helped me learn the mix blend mode feature in the css and I found it quite helpful.

## Author

- Website - [Yiwen Xu](https://github.com/yiwenxx)
