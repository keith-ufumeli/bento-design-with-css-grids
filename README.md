# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Bento grid solution](#frontend-mentor---bento-grid-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-bento-ui-with-css-grids-Ni2BymAqqB)
- Live Site URL: [Add live site URL here](https://bento-design-with-css-grids.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Bootstrap 5 CSS 

### What I learned

During this project, I gained a deeper understanding of CSS Grid and how it can be effectively utilized in Bento UI design. One of the key techniques I learned was the use of the `grid-template-areas` property to create a complex grid layout.

Here's an example of how I used the `grid-template-areas` property in the CSS:

```css
article {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: auto;
  grid-auto-flow: dense;
  gap: 1em;
  grid-template-areas:
    "hero hero aside1"
    "hero hero aside1"
    "aside2 aside3 aside1"
    "aside2 aside3 aside1"
    "aside4 aside5 aside5"
    "aside4 aside5 aside5";
}
```

This allowed me to define a grid layout with specific named areas, making it easier to position and arrange the content elements within the Bento grid. 


### Continued Development

As I move forward, I plan to continue improving my CSS Grids and Flexbox skills in UI design. The Bento grid challenge has demonstrated the power and flexibility of these CSS layout tools, and I'm eager to expand my knowledge further and apply them to solve more complex design problems.

Specifically, I want to explore advanced techniques for creating responsive and dynamic grid-based layouts, as well as mastering the art of combining Grids and Flexbox to achieve intricate and visually appealing user interfaces. 

Additionally, I'd like to delve deeper into the optimization of grid-based layouts for performance, ensuring that the designs I create are not only visually stunning but also fast and efficient, providing the best possible experience for users across various devices and screen sizes.


### Useful resources

- [Bento Grids Design (FreeCodeCamp)](https://www.freecodecamp.org/news/bento-grids-in-web-design/) - This helped me for XYZ reason. I liked this pattern and will use it going forward.


## Author

- Frontend Mentor - [@keith-ufumeli](https://www.frontendmentor.io/profile/keith-ufumeli)

