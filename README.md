# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
## Overview
this project is good for learning box model and html structure, sementic html tag

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot1.jpg)
![](./assets/images/Screenshot2.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/alamscode-rgb/blog-preview-card-main)
- Live Site URL: [Add live site URL here](https://blog-preview-card-main-blue.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned

i learned how to used sementic element, how to structure layout using flext and width margin and padding properties.

```html
 <div class="card">
      <header>
        <img src="/assets/images/illustration-article.svg" alt="illustration-article">
      </header>
      <main>
        <span>Learning</span>
        <p>Published 21 Dec 2023</p>
        <h1>HTML & CSS foundations</h1>
        <p>These languages are
    the backbone of every website, defining structure, content, and
    presentation.</p>
      </main>
      <footer>
        <img src="./assets/images/image-avatar.webp" alt="image-avatar">
        <p>Greg Hooper</p>
      </footer>
    </div>
```
```css
@font-face {
  font-family: "figtree"; /* Choose a descriptive name for your font */
  src: url("./assets/fonts/Figtree-VariableFont_wght.ttf") format("truetype");
  font-style: normal;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: "figtree",sans-serif;
  font-style: normal;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: hsl(47, 88%, 63%);
  gap: 5em;
}
.card {
  background-color: hsl(0, 0%, 100%);
  width: 24rem;
  height: 32.6rem;
  display: flex;
  flex-direction: column;
  border: 1px solid rgb(0, 0, 0);
  border-radius: 1rem;
  color: hsl(0, 0%, 7%);
  box-shadow: 0.62rem 0.62rem 1px rgb(0, 0, 0);
}
header {
  flex: 1 1 100%;
  padding: 1.5rem 1.5rem 0 1.5rem;
}
header img {
  width: 100%;
  border-radius: 0.62rem;
}
main {
  flex: 1 1 100%;
  padding: 1.5rem 1.5rem 0 1.5rem;
}
main span {
  background-color: hsl(47, 88%, 63%);
  padding: 0.562rem 0.75rem;
  border-radius: 0.312rem;
  font-size: 0.87rem;
  font-weight: bold;
}
main p:nth-of-type(1) {
  margin-block-start: 1.5rem;
  font-size: 0.87rem;
}

main h1 {
  font-size: 1.5rem;
  margin-block-start: 1.5rem;
  width: 100%;
  margin-block-end: 1.75rem;
}
main h1:hover{
    color: hsl(47, 88%, 63%);
    cursor: pointer;
}
main p:nth-of-type(2) {
  margin-block-start: 1.5rem;
  font-size: 1rem;
  color: hsl(0, 0%, 42%);
}
footer {
  flex: 1 1 100%;
  display: flex;
  gap: 0.80rem;
  justify-content: start;
  align-items: center;
  margin: 1.5rem 0 1.5rem 1.5rem;
}
footer img {
  width: 2rem;
  height: 2rem;
}
footer>p {
  font-size: 0.87rem;
  font-weight: bold;
}

@media (max-width: 377px) {
  .card {    
    width: 20.5em;
    height: 31.3em;
    margin-inline-start: 1.5em;
    margin-inline-end: 1.5em;
  }
}


```

### Continued development

i will be extending this blog preview using grid layout and use some animation and do this using utility classes in coming days

## Author
- Frontend Mentor - [@alamscode-rgb](https://www.frontendmentor.io/profile/alamscode)
- Twitter - [@alamscode](https://www.twitter.com/alamscode)

