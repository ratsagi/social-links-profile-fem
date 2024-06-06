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

![social link profile](image.png)
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL here](https://ratsagi.github.io/social-links-profile-fem/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
### What I learned
I used to have figma file from previous challenges so It was challenging at first how to get a right size then I had a look at the design of qr code component and noticed  the similarites of the size of their container and I use it as an example after I just worked with jpg so the key point here is I could learn to use my best jugment of the size to create this project.
When I was styling the links and added background color it didn't take full width so I was a bit confused then I undestood to use this:
```css
main a{
    width: 100%;    
}
```
I learned about inheritance. I got to now that the parent properties like color  can be inherited to children by using value "inherit":
```css
main a{
    color: inherit;    
}
```
I also figured out how to place footer on the bottom:
```css
footer{
  position:fixed;
  bottom:0;
}
```
### Continued development
I will continue to explore and follow the learning path from frontend mentor to get more hands on experience. Also continue to use free plan which lets me improve my jugment skill to recognize the sizes and other stuff. I think this is the most important skill in frontend development.
## Author

- Website - [Sagi](https://github.com/ratsagi)
- Frontend Mentor - [@ratsagi](https://www.frontendmentor.io/profile/ratsagi)
- Twitter - [@Sagi31758105](https://www.twitter.com/Sagi31758105)