# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot of the solution](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Code Snippet Takeaways](#code-snippet-takeaways)
  - [Continued development](#continued-development)
  - [References](#references)
- [Author](#author)
- [Acknowledgment](#acknowledgment)

## Overview
This small project enables to build out an interface of a social link-sharing profile. The designs were given to get your personalized social link look as close to it as possible.

### The challenge
Users should be able to:
- See hover and focus states for all interactive elements on the page

[Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ)

### Screenshot of the solution
[Desktop view](./screenshots/Desktop%20view%20-%20Social%20Links%20Profile.png)

[Mobile view](./screenshots/Mobile%20view%20-%20Social%20Links%20Profile.png)

### Links
[Solution URL](https://github.com/m-ysabelb/social-links-profile-frontend-mentor-challenge)

[Live site URL here](https://m-ysabelb.github.io/social-links-profile-frontend-mentor-challenge/)

## My process
- # Plan and code.
 By my first look to the designs, I presumed that this project will be tough and it will take me much time to finish it due to multiple styles. I started the project by creating its HTML structure. This part, as I can say, is the least time consumed compared to the other parts of the process.

- # Style the components.
 After the HTML, I proceeded to CSS where fonts, sizes, colors, spacings, and other properties were involved. Most of the time were spent on this part because the design involves a lot of styling in order to achieve the expected look, and this is also my struggle since only few basic elements and properties were familiar to me. One of the things I struggled is how to make my project perform effectively as a mobile-responsive website should. As a result, I solved the problem through using the spacings, margins, and paddings--the basic elements I completely have a knowledge on. Google and YouTube were also my company during this researching times.

- # Test and try it for several times.
  This part was done simultaneously together with my trial and error phases of styling the project because there were a lot of times where I was unsatisfied of the look, especially its performance on mobiles. After hundreds of trial and error tests, I finally achieved of making it look similarly as expected. In future projects, I can say that 'Mobile-first Responsive design' is a vital part I need to practice on.

- # Deploy the project.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Mobile-first Responsive Design
- VS Code Studio Software
- Github (gh-pages) for deployment

### Code Snippet Takeaways
```html
  <main div class="new-class">
    <!--I saw this tag across tutorials/websites usually placed at the beginning in the body, so I try implementing it in this code.
    Moreover, content included in this tag demonstrates the main content of a document that is not a descendant of any element-->
  </main>
```

```css
/**padding shorthand**/
  element {
    padding: top right bottom left; /**measures either in px, rem, or em**/
  }

/**min-height has vh value that means viewport height**/
/*snippet from the code*/
body {
    background-color: #141414;
    font-family: "Inter", sans-serif;
    font-optical-sizing: auto;
    font-size: 14px;
    display: grid;
    place-content: center;
    min-height: 100vh;
}
/**100vh = 100% of the viewport height**/

/**setting the image into a clean circle format (esp for social profiles) should set its border-radius into 50%**/
  img {
    border-radius: 50%;
  }

/**add :hover if you want to change the button state as hovered**/
 button:hover {
    background-color: #c5f82a; /**set the bg color of the button to lime green**/
    color: #ffffff; /**set the text color into white**/
    cursor: pointer; /**change the cursor view into a pointer as hovered**/
 }

/**syntax for mobile-responsive**/
@media (max-width: 350px) { /**the following code will take effect if viewport width is 350 and below**/
  element {
    property: value;
  }
}
```

### Continued development
These are the things that I want to work on in future projects:

- Get used with CSS Styling and Properties
- Flexbox techniques
- Mobile-first responsive design
- CSS and display properties

### References
- [How to resize image using CSS](https://www.browserstack.com/guide/how-to-resize-image-using-css)
- [min-height in CSS](https://www.shecodes.io/athena/4773-what-is-the-meaning-of-min-height-100vh-in-css#google_vignette)
- [Fonts](fonts.google.com)
- [HSL to HEX](https://htmlcolors.com/hsl-to-hex)
- [Social Links Profile Solution tutorial 1](https://www.youtube.com/watch?v=PlUOMi23qAc)
- [Social Links Profile Solution tutorial 2](https://www.youtube.com/watch?v=JHWT_V9pYu8&t=250s)
- [Supplementary Tutorial 3](https://www.youtube.com/watch?v=9FNNkzPBFcE)

## Author
- GitHub - [@m-ysabelb](https://github.com/m-ysabelb)
- Frontend Mentor - [@m-ysabelb](https://www.frontendmentor.io/profile/m-ysabelb)

## Acknowledgment
Special thanks to the author of the resources mentioned in the references section, specifically:
- Google
- YouTube
- Browser Stack
- SheCodes

Their documentation, articles, and tutorials have been beneficial for the overall completion of this simple project.
