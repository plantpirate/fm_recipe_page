# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](/screenshot.jpeg)


### Links

- Solution URL: [https://github.com/plantpirate/fm_recipe_page]
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
My first steps were to figure out which texts were headings, a paragraphs, and which text made up section or list elements. From there, I wrapped those elements with the appropriate tags according to the design image. 

My next step was figuring out how to format the nutrition section  grid. I went with the simple repeat option to create the cells, and used 1fr to try and fill the space to match the design image. 

Next I focused on customizing the layout. I've used flexbox with success on other small projects for that goal, I thought it would also work best for this. In the future, I think I could redesign it using grid after I've learned and had more experience using it. 

Lastly, I integrated the colors from the style-guide for font sizes and colors, and the background colors

For some features like margin and padding resets, I worked them in while I was working through all the steps. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
Using grid in a project was easier than I expected. I could have gotten the same result with flexbox, but I wanted the experience of a real project vs following along from a learning module. 

Along with grid, I wanted to attempt using the nth-of-type selector since that seemed the easiest for styling the divs within the grid. 
Using this method to select multiple divs had been an issue for me on a smaller project, but i found better resources this time that allowed me to gain a better understanding of the selector.  


```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```


### Continued development

I'll need to continue practice using grid, and brush up again on the different ways to center elements.
Remember the basics, don't over complicate things.

### Useful resources

- [W3schools](https://www.w3schools.com/cssref/sel_nth-of-type.php)
  - This helped me during the times I was trying to style my grid divs. There is always another way, but this worked after taking the time to further understand how the selector is used.
- [MDN](https://developer.mozilla.org/en-US/) 
  - There were various points during the project that MDN was useful in completing it. It can at least act as a starting point to getting needed answers. 

## Author

- Frontend Mentor - [@plantpirate](https://www.frontendmentor.io/profile/plantpirate)
