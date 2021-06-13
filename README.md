# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned:

- That you can make a responsive website without media queries.
  It is possible to make a website responsive solely with CSS Grid, which what I mainly did with this project.

- How to use Font Awesome and make a circle border around social media links.

- The difference between (width:100%) and (width:auto;):
  Width:100%; element(s) take up the exact width of the parent, however it excludes margins and paddings.
  Width:auto; element(s) take up the width of the parent in which the margins and paddings are included.

- To make the footer stick at the bottom. I have achieved this by using the following properties and values;
  html {
  height: 100%;
  }

  body {
  min-height: 100%
  display: flex;
  flex-direction: column;
  }

  footer {
  margin-top: auto;
  }

## Author

- Website - [kxnzx](https://github.com/kxnzx)
- Frontend Mentor - [@kxnzx](https://www.frontendmentor.io/profile/kxnzx)
