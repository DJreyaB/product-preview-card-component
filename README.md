# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Mobile 

![](images\Screenshot 2023-02-18 at 23-54-56 Frontend Mentor Product preview card component.png)

#### Desktop

![](images\Screenshot 2023-02-18 at 23-55-59 Frontend Mentor Product preview card component.png)

<!-- ### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com) -->

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned
- use the picture tab in cases where there are different images based on screen size or changes
- utilized css syntax to apply padding bottom to all of the children of the parent with id details.


```html
<picture>
  <source>
</picture>
```
```css

#details > * {
    padding-bottom: 15px;
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.



### Useful resources

- [Dev To](https://dev.to/drews256/ridiculously-easy-row-and-column-layouts-with-flexbox-1k01) - This helped me understand how to create columns better within flexbox.
- [W3 Schools](https://www.w3schools.com/css/css3_mediaqueries.asp) - This documentation is great for understanding the ins and outs of media query with css.
- [Image SRC StackOverflow](https://stackoverflow.com/questions/30460681/changing-image-src-depending-on-screen-size) - I used this code to understand methods of changing the image based on a media query / screen conditions.
- [Parent Child Padding CSS StackOverflow](https://stackoverflow.com/questions/6507014/how-to-space-the-children-of-a-div-with-css) - This is a great resource to get code snippets and details about adding css to children tags.

## Author

- Website - [DJreya Boyd](https://www.djreyaboyd.com)
- Frontend Mentor - [@DJreyaB](https://www.frontendmentor.io/profile/DJreyaB)
