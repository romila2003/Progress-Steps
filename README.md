# Progress-Steps

This is apart of the 50 projects in 50 days challenge and is the second project.

## Table of contents

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

### The challenge

- To create progressive steps that moved onto the next step once clicked. The challenge involves HTML, CSS and Javascript.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/Progress-Steps/blob/main/Mobile%20preview.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Progress-Steps/blob/main/Desktop%20preview.PNG)


### Links

 - Source code: [https://github.com/romila2003/Progress-Steps](https://github.com/romila2003/Progress-Steps)
 - Live website: [https://romila-progressive-steps.netlify.app/](https://romila-progressive-steps.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

I improved my knowledge regarding the `if` and `else` statements. I've also briefly learned about calculations with percentages in JS.


Javascript - if and else:

```javascript

    const active = document.querySelectorAll(".active");

    progress.style.width = (active.length - 1) / (circles.length - 1) * 100 + "%";

    if(currentActive === 1) {
        prev.disabled = true;
    } else if(currentActive === circles.length) {
        next.disabled = true;
    } else {
        prev.disabled = false;
        next.disabled = false;
    }

```

### Continued development

For future developments, I should learn more concepts of javascript and implement those within new projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
