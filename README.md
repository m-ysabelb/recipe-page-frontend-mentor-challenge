# Recipe Page Documentation by @m-ysabelb

This is the documentation of my [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help to improve coding skills by building realistic projects.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot of the Solution](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Code Snippet Takeaways](#code-snippet-takeaways)
  - [Continued development](#continued-development)
  - [References](#references)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This challenge focuses on writing semantic HTML and think through the most appropriate HTML elements for each piece of content. This challenge is also a good practice for writing HTML and CSS code.


### The challenge
[Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm)

### Screenshot of the Solution
[Desktop view](./screenshots/Simple%20Omelette%20Recipe%20-%20Desktop%20view.png)

[Mobile view](./screenshots/Simple%20Omelette%20Recipe%20-%20Mobile%20view.png)

### Links
[Solution URL](https://github.com/m-ysabelb/recipe-page-frontend-mentor-challenge)

[Live Site URL](https://m-ysabelb.github.io/recipe-page-frontend-mentor-challenge/)

## My process
- ### Plan by looking at the snapshot of the expected outcome
  From the snapshot, I formulated a basic draft outline on what HTML elements will be used. This includes the text-sizes, the placement, the alignment, and any other properties considered. As for the CSS, I referred to the given style guide in formulating possible properties. Its preparation includes conversion of HSL color codes to HEX and finding the correct fonts from the Google Fonts

- ### Create and code the draft.
  I usually plan on paper so in this step, I started creating my draft through coding the plan into the Visual Studio software. I included the corresponding image and text to the structured format. As I finished doing the HTML part, I moved onto the CSS, which I find the most challenging to finish in a little amount of time. I struggled on matching the exact colors, font-weights, spacings, alignment, and what I call 'the newly-encountered' properties to me since I am not yet versatile at coding CSS. Nonetheless, I still managed to make the website look as it should be with the help of Google, coding websites, and YouTube.

- ### Test and try it for several times.
  Completing the whole code does not necessarily mean that your work is done. You need to look at it for several times, search for its flaws, and compare your output code if it already looks vastly similar to the given design. Your keen observation and attention to detail will be trained in this part. Also, your critical skills on how to solve the identified areas for improvement.

- ### Release program.
  Personally, I prefer doing all stated steps before proceeding into this last one but for this challenge, I released my code twice due to multiple iterations of the aforementioned steps. I did it to track my progress everytime I code.

  In conclusion, either finalizing everything before publishing or releasing and updating it as you make progress will work. However, in my opinion, I can say that the latter option takes more time than the first.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Mobile-first Responsive Design
- VS Code Studio Software
- Github (gh-pages) for deployment

### Code Snippet Takeaways
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <--- declared in the HTML head to display site properly based on user's device

<img class="can be included in a class" id="can also be given an id name" src="./folder-name/another-folder-name/filename.file-extension" alt="">

<div class="can be included for every element for easeness of multiple styling in CSS"> </div>

<hr id="this is a horizontal line divider">

<p> Use <span> span </span> to make a selected word or phrase in a sentence styled. </p>

<table id="syntax needed for creating a table">
  <tr id="this creates a single row">
  <th id="this creates the emphasized heading of the table">
  <td id="used for inputting data in the table">
</table>

```

```css
  /*declared at the start of CSS*/
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  /*Specifying multiple elements sharing the same property*/
  element1, element2 {
  property1: specification;
  }

  /*example*/
  h2, li, .nutritional-value {
    color: #854632;
  }

  /*can be used if you want to hide the bottom divider of the table*/
  element {
    border-bottom-width: 0;
  }

  /*syntax to insert code for mobile-first responsive design*/
  @media (max-width: 520px) /*declaration means that the following code will take effect if width is 520px and below*/
  {
      element {
        property: value;
      }
  }

  /*the following is a snippet from the actual code. it made me realized that if you want to extend the content to the sides or top and below of the mobile view, just set the property (especially the paddings and margins) into zero
  
  yet I believe it is not applicable in some cases
  */
  @media (max-width: 520px) {
    img {
        padding: 0;
        margin: 0;
    }

    .recipe-container {
        padding: 0;
        margin: 0;
        border-radius: 0;
    }

    .text-content {
        padding: 0 2rem;
    }

    .recipe-container img {
        padding: 0;
        border-radius: 0;
    }

```

### Continued development
This section is an outline areas of things I want to focus on in future projects.

- Semantic HTML5 markup
- Get used with CSS Styling and Properties
- Mobile-first responsive design
- Improve code composability and readability
- Providing documentation to a finished coding project

### References
The following are resources that helped me in completing this project.

- [HTML hr tag](https://www.w3schools.com/tags/tag_hr.asp#:~:text=The%20element%20is%20most,change)
- [HTML tables](https://www.w3schools.com/html/html_tables.asp)
- [Change the hr color](https://www.tutorialrepublic.com/faq/how-to-change-the-color-of-an-hr-element-using-css.php#:~:text=You%20can%20simply%20use%20the,value%20of%20the%20height%20property.)
- [How to Bold a word in a sentence](https://stackoverflow.com/questions/9058425/how-to-bold-words-within-a-paragraph-in-html-css)(https://smallbusiness.chron.com/bold-word-sentence-css-45432.html)
- [CSS tables](https://www.w3schools.com/css/css_table.asp)
- [CSS display property](https://www.w3schools.com/css/css_display_visibility.asp)
- [CSS font weight property](https://www.w3schools.com/cssref/pr_font_weight.php)
- [CSS font weight property](https://www.w3schools.com/cssref/pr_font_weight.php)
- [Change the bullet color/use of span](https://www.geeksforgeeks.org/how-to-change-the-color-of-bullets-using-css/)
- [Change spacing between paragraphs](https://stackoverflow.com/questions/41253908/changing-spacing-between-paragraphs-and-inside-of-paragraphs)
- [CSS margin](https://www.w3schools.com/css/css_margin.asp)
- [Mobile-first CSS](https://medium.com/@pete.davis/mobile-first-css-89d16c91e6b3)
- [Fonts](fonts.google.com)
- [HSL to HEX](https://htmlcolors.com/hsl-to-hex)
- [Recipe Page Solution tutorial 1](https://www.youtube.com/watch?v=wF2DLQGeJS0)
- [Recipe Page Solution tutorial 2](https://www.youtube.com/watch?v=JeagPId2y54)

## Author
- GitHub - [@m-ysabelb](https://github.com/m-ysabelb)
- Frontend Mentor - [@m-ysabelb](https://www.frontendmentor.io/profile/m-ysabelb)

## Acknowledgment
Special thanks to the author of the resources mentioned in the references section, specifically:
- Google
- YouTube
- Stack Overflow
- w3schools
- geeksforgeeks

Their documentation, articles, and tutorials have been beneficial for the overall completion of this simple project.
