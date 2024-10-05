# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
started with html built skeleton first and then added styles

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. discovered about <time></time> html tag which is used to show date
2. learned to make box-shadows


```html
    <time  class="date-info"  datetime="2023-12-21">Published 21 Dec 2023</time>
```
```css
.card-component {
  display: flex;
  flex-direction: column;
  gap: 20px;
  background-color: hsl(0, 0%, 100%);
  padding: 1.3rem;
  border: 1px solid hsl(0, 0%, 7%);
  border-radius: 15px;
  -webkit-box-shadow: 8px 8px 0px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 8px 8px 0px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 8px 8px 0px 0px rgba(0, 0, 0, 0.75);
}

```

## Author

- Frontend Mentor - [@sudarshanHosalli](https://www.frontendmentor.io/profile/sudarshanHosalli)


