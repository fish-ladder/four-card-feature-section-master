# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot](https://github.com/fish-ladder/four-card-feature-section-master/blob/main/four-card-feature-section-screenshot.png)

### Links

- Solution URL: [Github repo](https://github.com/fish-ladder/four-card-feature-section-master)
- Live Site URL: [Live site](https://fish-ladder.github.io/four-card-feature-section-master/)

## My process

1. First thing I did was figure out how I would use Grid to achieve the responsive layouts. I used codepen and created the layout and media queries to get a feel for how it would work. I even added a couple extra breakpoints and layouts for fun (one of which made it into my solution). [See my codepen here:](https://codepen.io/fishladder/pen/QWPRZWg)
2. Next I sketched out my html elements structure on a notepad.
3. In VS Code I built out the html file.
4. Linked my stylesheet, added some boilerplate resets and custom properties.
5. Styled the element content (fonts, sizes, colors, etc)
6. Built the simple stacked mobile layout.
7. Added final details like the box-shadow details
8. Tweaked a LOT.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned Grid a little better, especially how the positioning within columns and rows works.

I also learned that small details can be more complex than I initially figured. The fine colored accent lines on the top of each card was quite tricky for me and I really had to experiment to achieve the result I was after. This is how I did it:

```css
.team-builder {
  background: linear-gradient(var(--clr-red) 1%, #ffffff 2%);
}
```

### Continued development

I'd like to work with Grid some more to start feeling really comfortable with it. I also found the figma file didn't have the same amount of detail as some of the other projects in terms of detailed spacing information. I had to fiddle a lot to try to dial in the layout.

### Useful resources

- [Josh Comeau's Interactive Guid to Grid](https://www.joshwcomeau.com/css/interactive-guide-to-grid/) - This was fantastic for helping me get a handle on using grid. Super helpful. Thanks, Josh!

## Author

- Frontend Mentor - [@fish-ladder](https://www.frontendmentor.io/profile/fish-ladder)

## Acknowledgments

Thanks for Kevin Powell for his tutorials on grid!
