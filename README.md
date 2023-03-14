
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot/Screenshot%202023-03-01%20153606.png)
![](./screenshot/Screenshot%202023-03-01%20153806.png)
This is a screenshot of what i did.

### Links


- Live Site URL: [live site](https://iceberg61.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned
responsive design is kinda difficult for me but i was able to archive the layout with the knowledge i have.
@media (max-width: 375px) {
 
    .container { 
        flex-direction: column; 
    }

    .left { 
        width: 100%; 
    }

    .product-image {
        width: 100%; 
        height: 100%;
        object-fit: contain;
        border-top-right-radius: 20px;
        border-bottom-left-radius: 0px;
    }

    .right { 
        width: 100%;
        border-top-right-radius: 0px;
        border-bottom-left-radius: 20px;

    }


### Continued development

I want to improve more on flexbox and responsive design



### Useful resources

- [Example resource 1](https://stackoverflow.com/) - This helped me for responsiveness and a little flexbox

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/iceberg61)
- Twitter - [@yourusername](https://www.twitter.com/ayanakoji_kiyo)

