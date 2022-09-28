# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
Using html and css to create a product preview.

### Screenshot

![](./images/Screen%20Shot%202022-09-28%20at%2014.13.38.png)
![](./images/Screenshot%202022-09-28%20at%2014-11-20%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Using the picture element in html to make art direction for images when the screen width changes.
```html

<picture>
        <source media="(max-width: 620px )" srcset="./images/image-product-mobile.jpg">
        <source media="(min-width:620px )" srcset="./images/image-product-desktop.jpg">
        <img src="./images/image-product-desktop.jpg" alt="product-img">
      </picture>
```




### Continued development

Responsive Web designing


### Useful resources

- [https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images]() - This helped me for the art direction using picture element in html.


## Author

- Frontend Mentor - [@efosu](https://www.frontendmentor.io/profile/efosu)



## Acknowledgments

Mozilla developer web docs.