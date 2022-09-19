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
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/Screenshot.jpg)

### Links

- Solution URL: [https://github.com/DamonTham/Profile-card-component](https://github.com/DamonTham/Profile-card-component)
- Live Site URL: [https://damontham.github.io/Profile-card-component/](https://damontham.github.io/Profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="data">
  <div class="followers">
    <h1 class="numbers">80K</h1>
    <p class="text">Followers</p>
  </div>
  <div class="likes">
    <h1 class="numbers">803K</h1>
    <p class="text">Likes</p>
  </div>
  <div class="photos">
    <h1 class="numbers">1.4K</h1>
    <p class="text">Photos</p>
  </div>
</div>
```

```css
body {
  font-family: "Kumbh Sans", sans-serif;
  min-height: 100vh;
  display: flex;
  align-items: center;
  background-color: hsl(185, 75%, 39%);
  padding: 50px;
  font-size: 18px;
  background-image: url("images/bg-pattern-top.svg"),
    url("images/bg-pattern-bottom.svg");
  background-repeat: no-repeat, no-repeat;
  background-position: right 50vw bottom 40vh, left 50vw top 40vh;
}
```

<!-- ```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
``` -->

## Author

- Frontend Mentor - [@DamonTham](https://www.frontendmentor.io/profile/DamonTham)
