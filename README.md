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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
[Discovery]
(16-MAR-2025) | I'm going to try something a little different this project - by jotting down my thoughts before I start. My initial observations are:
1. All Elements Flow Vertically - this looks like another good use case of the flexbox. All the elements are stacked on top of each other.
2. The padding on the main container looks like it compresses slightly on the mobile view.
3. Going to have to reuse pseudo-classes to define the hover states of the buttons.
4. I think I'm also going to use classes for buttons as they appear to look the same with the same hover properties.

[Build]
(16-MAR-2025)




### Built with

- HTML5
- CSS3
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

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

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Stackoverflow](https://stackoverflow.com/questions/27539262/whats-the-difference-between-align-content-and-align-items) - This helped me with understand align content vs align items.
- [MDM-Web-Docs] (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox) - Great resource for flexboxes and helped build the understanding of flexboxes from the ground up.

## Author
- Melvin

## Acknowledgments

