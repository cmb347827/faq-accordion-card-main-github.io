# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

[screenshot.png](https://postimg.cc/grmcfvXy)


### Links

- Solution URL: [Github](https://github.com/cmb347827/faq-accordion-card-main-github.io)
- Live Site URL: [Live Github](https://cmb347827.github.io/faq-accordion-card-main-github.io/)

## My process

### Built with

- Semantic HTML5 markup
- Bootstrap
- Sass/SCSS
- Mobile-first workflow


### What I learned

- I had some trouble aligning the box icon in desktop view. It was easy enough to hide the box in mobile view as I do something similar with images , which I did before in an earlier projects

- More difficult was getting the background purple gradient correctly for both desktop and mobile, as well as the background url placement for both mobile and desktop.

- I needed to set the gradient background for different screen sizes, as desktop was full coverage and mobile, just mobile sized (otherwise the purple from the image blends with the background).

- This was  harder than, for instance, the "Order summary component" which did at least have the same background coverage size for both mobile/desktop.

- I first tried to apply the gradient for both desktop and mobile to the `<html>` element, but that did not work for mobile.

- Then, just to the `<container>` element, which works for mobile, but not desktop. 

- Finally, applied to `<html>` as well for desktop only, which worked. For some reason this was new to me.

- I first tried setting the background url for both mobile and desktop in `<html>`, but that did not work.

- Realized it needed to be almost centered anyway and it made sense to add the background url to the `.image` class in desktop and to the `.under` class in mobile.

- Adding the accordion was realtively straighforward as I've done something similar with a dropdown menu in an earlier project (see my codepen).

- Harder was trying to change the arrow button color and to remove the default blue border, tried to figure this out myself first but that did not work as Bootstrap accordion is new to me.


### Continued development

- Daily tutorials and projects in HTML5, CSS3, Javascrip, Bootstrap, Sass/SCSS. For now, in time I will go re-learn React ect.

- I need to add more comments to my code, I will add to this project and try to continue doing so in future projects

### Useful resources

- [Bootstrap accordion](https://getbootstrap.com/docs/5.3/components/accordion/) - Bootstrap accordion explanation

- [Remove border from Bootstrap accordion](https://stackoverflow.com/questions/28866553/remove-border-from-bootstrap-accordion) - Helped in figuring out how to remove the default blue border

- [Changing the color of the arrow in Bootstrap accordion](https://stackoverflow.com/questions/66335238/changing-the-color-arrow-in-bootstrap) - Helped in figuring out how to change the arrow color of the button

## Author

- Website - [One of my latest codepens](https://codepen.io/cynthiab72/pen/oNybYON)
- Frontend Mentor - [@cmb347827](https://www.frontendmentor.io/profile/cmb347827)

