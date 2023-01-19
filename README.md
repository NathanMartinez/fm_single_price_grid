# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Mobile](/images/Screen%20Shot%202023-01-18%20at%206.54.53%20PM.png)
![Desktop](/images/Screen%20Shot%202023-01-18%20at%206.55.01%20PM.png)

### Links

- Solution URL: [Github Repo](https://github.com/NathanMartinez/fm_single_price_grid)
- Live Site URL: [Github Pages Site](https://nathanmartinez.github.io/fm_single_price_grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
main {
	width: 675px;
	grid-template-columns: repeat(2, 1fr);
	grid-template-rows: auto;
	grid-template-areas:
		'join join'
		'sign-up why-us';
}
main #join {
	grid-area: join;
}

main #sign-up {
	grid-area: sign-up;
}

main #why-us {
	grid-area: why-us;
}
```

### Continued development

- CSS Grid
- React
- Svelte
- Nextjs
- Vue

### Useful resources

- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Github - [Github](https://github.com/NathanMartinez)
- Frontend Mentor - [@NathanMartinez](https://www.frontendmentor.io/profile/NathanMartinez)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**
