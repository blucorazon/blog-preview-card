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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

[Screenshot of Solution](./assets/images/blog-preview-solution.png)
[Screenshot of Solution (With Hover)](./assets/images/blog-preview-solution-hover.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- Create CSS sheet and link it to html file
- Created a section for the elements on the page
- the blog post image is housed in its own <div>
- the text in that container is in its own respective <div>
- updated the headings to reflect the relative importance of each line of text before styling
- placed the background avatar to the left of the text using Flexbox

Notes on process: How do I make the process more organized?
- Two things I did not do that may help in the future:
  1. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
  2. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to approach a simple web problem; how to configure certain CSS properties and keep my style sheet organized.
I gained an introduction into flexbox as well as how to import a font into my site. 

New Concepts/Topics:
- Rem (CSS)

- Properties: A CSS property is a characteristic that defines how a browser displays an HTML element's aspect. CSS properties are used to set the style or behavior of HTML elements
  - align-items
  - box-shadow
  - box-sizing
  - background-color
  - border
  - border-radius
  - color
  - cursor
  - display
  - flex-direction
  - font-family
  - font-size
  - font-style
  - font-weight
  - gap
  - height
  - justify-content
  - margin
  - max-width
  - padding
  - width


- Selectors: A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.
  - .class: Selects all elements with class="(class-name-here)"

- Pseudo-Classes: pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s).
  - ':firstchild':  CSS pseudo-class represents the first element among a group of sibling elements.
  - ':hover': Selects a link on mouse-over
  - Use of Both A selector and pseudo-class:
    ```css
    .container:hover {
        box-shadow: 15px 15px 0px black;
    }
    ```

- At-rules
  - @fontface: CSS at-rule specifies a custom font with which to display text; the font can be loaded from either a remote server or a locally-installed font on the user's own computer.
    - ```css
        @font-face {
        font-family: "Figtree";
        src: url(./assets/fonts/Figtree-VariableFont_wght.ttf);
        font-weight: 600 800;
        }
      ```
  - @media: CSS at-rule can be used to apply part of a style sheet based on the result of one or more media queries. With it, you specify a media query and a block of CSS to apply to the document if and only if the media query matches the device on which the content is being used.
    - ```css
      @media(min-width: 375px) {
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            flex-direction: column;
            padding: 0;
        }
      }
      ```

### Continued development
These topics came up during the course of this challenge, and reviewing these topics will help down the road. 
- Organization: As the complexity of a project increases how do you keep organized ones...
  - Thoughts
  - CSS properties within { }
  - Planning the structure of a project

- Mobile-first design
- Sections vs. Divs (HTML)
- Flexbox (CSS)
- How to scale? How to ensure that my product will be clean and visible on any platform
- Padding vs. Margin
- Fonts
- Media Queries

### Useful resources

- [The Markdown Guide](https://www.markdownguide.org/)


## Author

- Github - [@blucorazon](https://www.github.com/blucorazon)
- Frontend Mentor - [@blucorazon](https://www.frontendmentor.io/profile/blucorazon)

## Acknowledgments
- [Thomas Sankara's Guide](https://www.youtube.com/watch?v=3n22cowxoKU) - This tutorial helped get me going and even though our process deviated on a couple requirements, I found great tips here when it came to using flexbox and was presented with a pretty interesting way to structure the classes in the css file. 