# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/AatishAsh/blog-preview-card-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

i learned few concepts in HTML and CSS:
HTML:
learned about the <article> tag, which is used for self contained content like this blog card
learned about the <span>tag
CSS:
learned about the display:flex property and how it changes the layout behavior of elements
and @font-face to use the local fonts
```html
<article class="wrapper"></article>
<span class="tag">Learning</span>
```
```css
.wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    font-family: Figtree , sans-serif;
}
@font-face {
    font-family:'Figtree' ;
    src: url(/assets/fonts/Figtree-VariableFont_wght.ttf);
}

```

## Author

- Frontend Mentor - [@AatishAsh](https://www.frontendmentor.io/profile/AatishAsh)


