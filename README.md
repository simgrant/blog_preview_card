# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

<img width="1219" alt="Screenshot 2025-02-03 at 2 41 14 PM" src="https://github.com/user-attachments/assets/d21de7b5-39ec-4d10-b52b-5006fd485410" />

### Links

- Solution URL: [Add solution URL here](https://simgrant.github.io/blog_preview_card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

**CSS Positioning and Layout**:
   - **Positioning with `absolute`**: Used position: absolute for placing elements in specific positions relative to their container or the viewport. Example: Centering the footer at the bottom of the screen using left: 50%; transform: translateX(-50%).
   - **Offsetting Elements**: Leveraged top, left, and transform for fine-grained control over element placement.
   
**CSS Media Queries**:
   - **Mobile-first design**: Utilized min-width media queries to apply specific styles for larger screen sizes, ensuring a responsive layout from mobile to desktop. The **`min-width`** media query allows you to apply styles when the viewport is **larger than a specific width**, while **`max-width`** would apply styles for smaller screens.
   - **Order of Media Queries**: Placed media queries at the bottom of the CSS to maintain a logical flow, where base styles are defined first and overridden by specific rules for larger screens.

**CSS for Component Design**:
   - Applied styles like **border-radius** for rounded corners, **box-shadow** for card-like effects, and **border** for clean outlines.
   - Learned the importance of organizing code structure logically, ensuring that base styles come first, followed by more specific overrides for responsive design.


### Continued development

Going forward, I would like to experiment further with positioning and component designs for more interesting layouts.


### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helps a lot for referencing best practices.


