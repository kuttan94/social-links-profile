# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

### Links

## My process
[Discovery]
(16-MAR-2025) | I'm going to try something a little different this project - by jotting down my thoughts before I start. My initial observations are:
1. All Elements Flow Vertically - this looks like another good use case of the flexbox. All the elements are stacked on top of each other.
2. The padding on the main container looks like it compresses slightly on the mobile view.
3. Going to have to reuse pseudo-classes to define the hover states of the buttons.
4. I think I'm also going to use classes for buttons as they appear to look the same with the same hover properties.

[Build]
(25-MAR-2025)
I had a bit of a break. But I'm back. Finished building this out today and added some learnings to the readme.

### Built with

- HTML5
- CSS3
- Flexbox

### What I learned

1. Cross Axis vs. Main Axis
The main axis of a flex box is determined by the direction of the flex box. If a flex box is column then the main axis is vertical. If the flex box is row, then the main axis horizontal.

1. Align Items vs. Align Contents
Align Items aligns content along the cross axis. Where as align contents is used for multi-line flexboxes. 

2. Flex Direction & Align-Items
Align items works in the cross-axis the flex container. Tying the concept of cross-axis, main-axis and flex direction together. In this project, the flex direction of the container was column. For that reason the main axis was vertical and therefor align items worked on the cross axis (i.e. horizontal)

3. Sizing
By default the items within a flex box will not flex to fill the size of the flex container in the direction of flex. So you may need to set flex grow, but in the project, I achieved this via padding.

Additionally, items within a flex box with take up the size of the content in the cross-axis direction, unless explicitly stated by using something like align-items: stretch or width: 100% (if flex direction was column);

### Continued development

### Useful resources

- [Stackoverflow](https://stackoverflow.com/questions/27539262/whats-the-difference-between-align-content-and-align-items) - This helped me with understand align content vs align items.
- [MDM-Web-Docs] (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox) - Great resource for flexboxes and helped build the understanding of flexboxes from the ground up.

## Author
- Melvin

## Acknowledgments

