# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Challenges](#challenges)
- [Author](#author)


## Overview
  The brief of this challenge was to create a qr-code-component and design it to look as similar to the png provided as possible

### Screenshot

![](./images/qr-component-solution.png.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I tried to work with styling one element at a time, working from the parent element to the child. However, the problems of my process wasn't obvious until the child elements weren't responding.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

1. [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
  - Declare CSS variables with ```--```(typically in the :root selector)
  - call them with ```var()```

2. [How to link CSS file to HTML](https://www.w3schools.com/css/css_howto.asp)
  - Call them using a ```<link>``` tag in the head
  
2. [Using google fonts](https://www.w3schools.com/css/css_font_google.asp)
  - Call them using a ```<link>``` tag in the head

3. [Center a div](https://www.youtube.com/watch?v=mVYgtzDLZfY)
  - After failing many times, the trick is to set a page width for the body element, then set a parent element with a ```percentage width```, this is so the child elements can be positioned without a fixed width (more [here](https://stackoverflow.com/questions/68516071/div-elements-are-going-top-left-and-not-centered-when-getting-zoomed-html-css))
  - then its as simple as setting margins on the div elements

4. [Resizing an image](https://www.delftstack.com/howto/css/resize-image-css/)
  - I went with making the ```width: auto;``` and ```max-height: 70%;```


## Biggest Challenges
- Centering the div on the page
- understanding the fixed elements on the page and working with flex


## Author

- Frontend Mentor - [@mpgithubcode](https://www.frontendmentor.io/profile/mpgithubcode)
