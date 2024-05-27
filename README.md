# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### Links

- [Live Site URL](https://sharangb.github.io/fmio-recipe-page/)

### What I learned

- How to better customize list item markers
  ```css

  ul > li::marker {
    content: '•   ';
  }

- How to handle list item width when the marker uses up additional width, causing the list item to get nudged to the right an exceeding the parent's bounds

  ```css
  ul > li {
    left: var(--len-xxl);
    position: relative;
    text-indent: -2rem;
    width: calc(100% - var(--len-xxl));
  }
  ```
