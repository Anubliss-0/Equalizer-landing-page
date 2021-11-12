# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links

- Solution URL: (https://github.com/Anubliss-0/Equalizer-landing-page)
- Live Site URL: https://anubliss-0.github.io/Equalizer-landing-page/

## My process
  I worked on this page from the top down, building each part and testing it at different widths until happy with the results.

  I used flex box to create a responsive design that should be viewable on any device.

  Finally I checked for accessability issues and fixed any that did not interfer with the design breif. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learned a lot about positioning elements using the absolute position property alongside flex boxes to create layouts that both kept cohesion with the original design and could be resize to fit any browser window.

Something id like to do better in my next project is to create style classes in CSS which I can apply to markup, rather than creating classes around the markup.

And finally I learnt that when set as a backround SVG files are difficult to change color! (like a hover button)

Below is an example of me using the nth of type selector. Something I was unable to do previously.

```html
<div class="social">
        <a class="soclink"></a>
        <a class="soclink"></a>
        <a class="soclink"></a>
      </div>
```
```css
a.soclink:nth-of-type(1) {
    background-image: url(assets/icon-facebook.svg);
    background-size: cover;
    background-position: center;
    height: 20px;
    width: 20px;
    
}
```


### Continued development

I am still relying on flex-box a little too much, and should experiment using grids or wireframing moving forwards.

### Useful resources

- [Wave Web Accessibility](https://wave.webaim.org/) 
- used to check Accessibility.

- [CSS filter generator](https://codepen.io/sosuke/pen/Pjoqqp) 
- Using the background-image propery allows for high control over the size and position of images on a page while keeping markup tidy. However changing the color can be tricky. With this tool you can create a filter to match a HEX color target.

- [The W3C Markup Validation Service](https://validator.w3.org/)
- I use this to double check my HTML.

## Author

Anubliss_

