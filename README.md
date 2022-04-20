# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [View codes](https://github.com/jesuisbienbien/faq-accordion-card-main)
- Live Site URL: [View Live site](https://jesuisbienbien.github.io/faq-accordion-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla Javascript

### What I learned

```html
<h1>Some HTML code I'm proud of</h1>
```

**_smooth dropdown transition_**

```css
.answer {
  color: var(--dark-grayish-blue);
  font-size: 0.7rem;
  margin-right: 3rem;
  overflow-y: hidden;
  max-height: 0;
  transition: all 0.25s;
}
.answer.open {
  max-height: 120px;
  transition: all 0.4s;
  margin-bottom: 1rem;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

### Useful resources

- Resource #1 [StackOverFlow](https://stackoverflow.com/questions/65464157/how-to-make-smooth-opening-dropdown-with-basic-javascript-code) - How to make a smooth faq dropdown using CSS

## Author

## Acknowledgments

@MaryamSherief on FrontendMentor
