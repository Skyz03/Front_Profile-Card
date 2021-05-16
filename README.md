# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
The card component is one of the most used content in every website, and there are certainly many different ways to implement this card component and make it  mobile responsive via the use of Bootstrap, one of its libraries but I preferred CSS as only the way so that I can learn it more and get familier with it. 

### The challenge

- Build out the project to the designs provided

### Screenshot

![image](https://user-images.githubusercontent.com/42742924/118390054-cf806500-b64c-11eb-8cca-0ab46b5da92e.png)

This is only desktop compatible solution via the use of plain CSS.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

The process I implemented to complete this desktop compatible challenge, was I completed the card component first then added the background by applying absolute positioning.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

The main knowledge I got from this challenge was about CSS Grid display property which works similar as a table but much simpler & easier to implement.


```css
.stats {
  grid-area: stats;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 35px;
  row-gap: 0px;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
}
```

### Continued development

For future developments, this challenge can be implemented with being mobile responsive via the use of some CSS or Bootstrap techniques plus the grid system can be refined for much readbility.

### Useful resources

- [resource 1](https://redstapler.co/rpg-style-card-design-with-hover-effect-html-css-tutorial/) - This helped me understand the GRID system of CSS. I really liked this.
- 
## Author

- Website - [Sky'z](https://www.your-site.com)
