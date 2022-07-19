# HTML and CSS Cheatsheet

## Introduction
The HTML and CSS Cheatsheet repository is a place where you can view a cheatsheet for HTML and CSS, languages used to create and design websites or webpages. You can also find useful pieces of information here (especially for beginners) and learning resources which are related to HTML and CSS in one way or another. This repository is a mini-project for a much bigger project called the [*Learning-Hub Project*.](https://github.com/ItemHunt/Learning-Hub) 

## How to Contribute
I welcome any contributors to this mini-project. Feel free to fork the project and add/edit stuff here and send out a pull request for review. If all is good, I should approve the pull request. In case you are new to GitHub, refer to [CONTRIBUTING](CONTRIBUTING.md) for a more detailed guide.

## Contributors

<!-- Contributors section made with [contrib.rocks](https://contrib.rocks). -->

## Table of Contents
### HTML Cheatsheet
- [Text](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#text)
- [Linking](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#linking)
- [Media Display](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#media-display)
- [Webpage Structures](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#webpage-structures)
- [Form Codes](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#form-codes)
- [Useful Codes](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#useful-codes)
- [Others](https://github.com/ItemHunt/HTML-and-CSS-Cheatsheet#others)

### CSS Cheatsheet


## HTML Cheatsheet
### Text
- **``<p> text </p>`` -**  *Paragraph* tag used for the textual content of a webpage
- **``<h1> text </h1>`` -** *H1 tag* used as the main overall title of the webpage
- **``<h2> text </h2>`` -** *H2 tag*, a subtopic title to the H1 tag
- **``<h3> text </h3>`` -** *H3 tag*, a subtopic title to the H2 tag
- **``<h4> text </h4>`` -** *H4 tag*, a subtopic title to the H3 tag 
- **``<h5> text </h5>`` -** *H5 tag*, a subtopic title to the H4 tag
- **``<h6> text </h6>`` -** *H6 tag*, a subtopic title to the H5 tag
- **``<ul> <li> bullet </li> </ul>`` -** *ul tag*, used to create an unordered list. The *li tag* in this context is considered as one bullet point
- **``<ol> <li> bullet </li> </ol>`` -** *ol tag*, used to create an ordered list. The *li tag* in this context is considered as a number that is a part of an order

### Linking 
- **``<a href = "url of a website or hash (#) for dead link"> media in hyperlink form </a>`` -** Turns anything between the *a tags* into a external link
- **``<a href = "#ID or segment"> media in hyperlink form </a>`` -** Turns anything between the *a tags* into an internal link leading to a specific part of the webpage
- **``target = "_blank"`` -** Property of the *a tag*, used to make external links open up a new browser tab first before heading to target website

### Media Display 
- **``<img src = "url of image">`` -** Used to add images
- **``alt = "textual alternative to image"`` -** Used as a property of *img*, displays given text if the image being sourced is unavailble or not in use
- **``<audio controls> <source = "url of audio" type = "format of audio"> </audio>`` -** Used to add audio that can be controlled

### Webpage Structures
- **``<head> head </head>`` -** Structure that defines the head of the webpage
- **``<header> header </header>`` -** Structure that defines the introductory section of the webpage
- **``<title> title </title>`` -** Structure that defines the title of the webpage
- **``<nav> navigation </nav>`` -** Structure that defines the navigation system of the webpage
- **``<main> main </main>`` -** Structure that defines the main section of the webpage
- **``<body> body </body>`` -** Structure that defines the body of the webpage
- **``<section> dependent section </section>`` -** Structure that defines a section of content that follows a given theme in the webpage
- **``<article> independent section </article>`` -** Structure that defines an independent section of content that doesn't rely on other parts of the webpage
- **``<footer> footer </footer>`` -** Structure that defines the footer of the webpage
- **``<div> text </div>`` -** Structure that defines a division in the webpage
- **``<style> CSS </style>`` -** 
 Structure that defines a section of the website containing all CSS data, it is located at the very top of the webpage code
- **``<code> code </code>`` -** Structure that defines an area meant for code
- **``<form> form </form>`` -** Structure that defines an area meant for form or questionarrie related content
- **``<label for = "ID of radio/checbox input type"> radi/checkbox choice </label>`` -** Used as a container for input type radio and checkbox, used within the form tags, and used to create text for the radio/checkbox choice

### Form Codes
- **``action = "url to send data to"`` -** Property of the *form tag*, used to have the form send user input to a specific url after form submission
- **``<button type = "submit"> Text </button>`` -** Used to create a button that allows users to send their input to the url specified by the *action property* upon form completion
- **``<input type = "text">`` -** Used to create an input box that accepts textual input
- **``<input type = "date">`` -** Used to create an input box that gets the user to pick a date
- **``<input type = "email">`` -** Used to create an input box that gets the user to input a valid email
- **``<input type = "radio">`` -** Used to create a multiple choice style question 
- **``name = "radio/checkbox name"`` -** Used as a property of the radio and checkbox input type to connect choices to a singular question
- **``value = "value of a non-text input type"`` -** Used as a property of everything except the text input type, value means that if the user inputs a specific choice like male for example, value should equal male. 
- **``checked`` -** Used as a property of radio/checkbox input type, allows the the specific input tag to be checked by default
- **``placeholder = "text"`` -** Property of the *input tag*, used to display placeholder text
- **``required`` -** Property of the *input tag*, used to make the user provide an answer to a specific *input tag or question* in order to complete the form

### Useful Codes
- **``<!-- comment -->`` -** Used to create a *comment block*
- **``<br>`` -** *Break*, used to move on to the next line
- **``id = "ID"`` -** *ID*, a property of almost every tag in HTML, used to link things together and add identifiers to the different parts of the webpage.
- **``class = "class1 class2 ..."`` -** *class*, a property of almost every tag in HTML, used to add CSS elements from CSS class/es. Multiple classes are separated by spacing

### Others
- **``<!DOCTYPE ...>`` -** HTML5 Website Version Identifier
- **``<!DOCTYPE html>`` -** Old HTML Website Version Identifier

## CSS Cheatsheet
### Essentials
- **``HTML_Structure { CSS Properties }`` -** Allows you to add CSS properties over all of the specified HTML Structure
- **``.class_name { CSS Properties }`` -** Allows you to create classes that can be used to add CSS elements to HTML elements that have the class
- **``@import 'font-style-copypasted-information';`` -** *@import* is used to get font styles from an external source within a CSS file. Usually contains a straight up *url* and a *rel tag*
- **``<link 'font-style-copypasted-information'>`` -** *link* is used to get font styles from an external source within a HTML file *style tag* section. Usually contains an *href and rel tag*.

### CSS Properties
- **``background: url("actual url");`` -** Used to set the background to contain an image from an external source
- **``background-color: color;`` -** Used to set the background color of something, it accepts general color names, RGB, hex codes, RGBA, etc.
- **``background: color;`` -** Used to set the background color of something, it accepts general color names, RGB, hex codes, RGBA, etc.
- **``background: linear-gradient(gradient direction value, color 1, color 2, ...color N);`` -** Used to create a linear gradient color. Direction accepts values in degrees. For color, you can use any amount and it accepts values like general color names, RGB(R, G, B), hex codes, RGBA(R, G, B, A), etc.
- **``color: color;`` -** Used to set the color of something, it accepts general color names, RGB(R, G, B), hex codes, RGBA(R, G, B, A), etc.
- **``hsl(value, value, value);`` -** Used to set an element's hue, saturation and lightness. Uses percentage as values.
- **``opacity: value;`` -** Used to adjust the opacity of things
- **``font-family: font_family_name;`` -** Used to set the font family of text
- **``font-size: value;`` -** Used to change the font size. Values that can be used include px, percentage, cm, mm, in etc.
- **``font-weight: value;`` -** Used to adjust the thickness of text, the acceptable values here are just plain numbers
- **``text-align: alignment;`` -** Used to align things
- **``line-height: value;`` -** Used to adjust line spacing, acceptable values include px, percentage, cm, mm, in etc.
- **``text-transform: value;`` -** Used to transform text to any of the following: lowercase, uppercase, capitalize, initial, inherit, and none.
- **``position: static;`` -** Default position value for all elements. They appear according to the order seen in the code.
- **``position: relative;`` -** Used to make the position of specific elements relative to itself. Meaning, the movement of elements affected by this position property does not affect the position of other elements
- **``position: absolute;`` -** Used to make the position of specific elements relative to its first positioned parent element. If there is no first positioned parent element, then it will be relative to the HTML element or page itself
- **``position: fixed;`` -** Used to make the position of specific elements related to the browser window
- **``position: sticky;`` -** Used to make the position of specific elements related to the user's scroll position
- **``direction: value;`` -** Used after using either relative or absolute position CSS element. Direction should be replaced with one of the following: right, left, top, bottom. Value should be in px, percentage, cm, mm, in etc.
- **``z-index: value;`` -** Used to change the stack position of an element affected by any of the position types from relative to sticky. Accepts any form of integer
- **``float: value;`` -** Used to make something float to either the right, left, or none.
- **``width: value;`` -** Used to adjust the width of an element
- **``length: value;`` -** Used to adjust the length of an element
- **``border-color: color;`` -** Used to set the border color of an element. It accepts it accepts general color names, RGB, hex codes, RGBA, etc.
- **``border-width: value;`` -** Used to set the border width of an element. Values that can be used include px, percentage, cm, mm, in etc.
- **``border-style: value;`` -** Used to set the border style of an element. Acceptable values include none, hidden, dotted, dashed, solid, double, groove, ridge, inset, outset. Multiple values can be used, they are separated by spaces. 
- **``border-radius: value;`` -** Used to make an element's border more round. Values that can be used include px, percentage, cm, mm, in etc.
- **``margin-direction: value;`` -** Direction can be top, right, left, and bottom. Values that can be used include px, percentage, cm, mm, in etc.
- **``margin: value1 value2 value3 value4;`` -** Value1 is top direction and value4 is left direction. Direction operates in a clockwise system. Values that can be used include px, percentage, cm, mm, in etc.
- **``padding-direction: value;`` -** Direction can be top, right, left, and bottom. Values that can be used include px, percentage, cm, mm, in etc.
- **``padding: value;`` -** All directions padding. Values that can be used include px, percentage, cm, mm, in etc.
- **``box-shadow: offset-x offset-y blur-radius spread-radius color;`` -** Used to create a box shadow. Blur-radius and spread-radius are both optional. Acceptable values for everything except color are px, percentage, cm, mm, in etc. As for color its general color names, RGB, hex codes, RGBA, etc.
- **``transform: scale(value);`` -** Used to scale the size of HTML elements. Value only accepts plain numbers.
- **``transform: skewX(value);`` -** Used to skew an object horizontally. Value input involves rad, turn, and deg. 
- **``transform: skewY(value);`` -** Used to skew an object vertically. Value input involves rad, turn, and deg. 
- **``visibility: hidden;`` -** Hides an element
- **``display: none;`` -** Hides an element
- **``display: inline;`` -** Displays an element as an inline element meaning height and width properties will have no effect
- **``display: block;`` -** Displays an element as a block. It has its own new line and uses up the whole width
- **``display: contents;`` -** Displays children elements of the direct children of the parent element as if it were also direct children of the parent element
- **``display: inline-block;`` -** Displays an element as an inline element and a block container. You can still apply height and width values. 
- **``display: inline-flex;`` -** Displays the element as an inline flex container
- **``display: inline-grid;`` -** Displays the element as an inline grid container
- **``display: inline-table;`` -** Displays the element as an inline level table
- **``display: list-item;`` -** Displays the element as a list element
- **``display: run-in;`` -** Displays an element as a block or inline. Depends on the context
- **``display: table;`` -** Displays the element as a table element
- **``display: table-caption;`` -** Displays the element as a caption element
- **``display: table-column-group;`` -** Displays the element as a colgroup element
- **``display: table-header-group;`` -** Displays the element as a thead element
- **``display: table-footer-group;`` -** Displays the element as a tfoot element
- **``display: table-row-group;`` -** Displays the element as a tbody element
- **``display: table-cell;`` -** Displays the element as a td element
- **``display: table-column;`` -** Displays the element as a col element
- **``display: table-row;`` -** Displays the element as a tr element
- **``display: initial;`` -** Default display
- **``display: inherit;`` -** Inherits the property of the affected element's parent element
- **``display: flex;`` -** Displays the element as a flex container
- **``flex: direction;`` -** Acceptable Direction values include *row-reverse*, *column-reverse*, *row*, and *column*. This code defines the direction or set-up of the flex container
- **``justify-content: value;`` -** Justifies flexbox container contents. Acceptable values include *center*, *flex-start*, *flex-end*, *space-between*, *space-around*, and *space-evenly*
- **``align-items: value;`` -** Changes flexbox element postion in the cross axis. Acceptable values include *center*, *flex-start*, *flex-end*, *stretch*, *start*, *end*, and *baseline*
- **``aign-self: value;`` -** Changes a grid or flex container item's alignment. Acceptable values include *flex-start*, *flex-end*, *center*, *start*, or *end*.
- **``flex-wrap: value;`` -** *Flex-wrap* specifies whether flexbox elements should wrap together or not. Acceptable values include *nowrap*, *wrap*, or *wrap-reverse*
- **``flex-shrink: value;`` -** Shrinks flex container elements. Acceptable value includes plain numbers.
- **``flex-grow: value;`` -** Grows flex container elements. Acceptable value includes plain numbers.
- **``flex-basis: value;`` -** Sets the initial main size of a flex item. Acceptable value includes plain numbers, auto, px, percentage, cm, mm, in, etc.
- **``flex: shrink_value grow_value basis_value;`` -** A flex container item resizing code which involves shrink, grow, and basis values separated by spaces.
- **``order: value;`` -** Used to adjust the order of flex container items. Plain numbers are used for value. 
- **``display: grid;`` -** Displays the element as a grid container
- **``grid-template-columns: width1 height1 widthN heightN;`` -** Used to create grid columns. One pair of width and heigth is equivalent to one grid container item. Acceptable values for width and height includes px, percentage, cm, mm, in, etc. 
- **``grid-template-rows: width1 height1 widthN heightN;`` -** Used to create grid rows. One pair of width and heigth is equivalent to one grid container item. Acceptable values for width and height includes px, percentage, cm, mm, in, etc. 
- **``grid-column-gap: value;`` -** Used to put a gap between columns. Acceptable values for width and height includes px, percentage, cm, mm, in, etc. 
- **``grid-row-gap: value;`` -** Used to put a gap between rows. Acceptable values for width and height includes px, percentage, cm, mm, in, etc. 
- **``grid-gap: row_gap column_gap;`` -** Used to put a gap between both columns and rows. Row and column gap should be replaced with values. Acceptable values for width and height includes px, percentage, cm, mm, in, etc. 
- **``grid-column: starting_column / ending-column;`` -** Used to adjust the amount of grid boxes the column will use (or the range of spaces a specific column will use for space). Starting-column and ending column should be replaced with plain number values.
- **``grid-row: starting_row / ending-row;`` -** Used to adjust the amount of grid boxes the row will use (or the range of spaces a specific row will use for space). Starting-row and ending-row should be replaced with plain number values.
- **``justify-self: value;`` -** Used to change the horizontal alignment of a grid column or row. Acceptable values include *center*, *stretch*, *start*, and *end*.
- **``justify-items: value;`` -** Used to change the horizontal alignment of all grid items. Acceptable values include *center*, *stretch*, *start*, and *end*.
- **``align-self: value;`` -** Used to change the vertical alignment of a grid column or row. Acceptable values include *center*, *stretch*, *start*, and *end*.
- **``align-items: value;`` -** Used to change the vertical alignment of all grid items. Acceptable values include *center*, *stretch*, *start*, and *end*.
- **``grid-template-areas: "cell1 name" "cellN name";`` -** Used to name multiple areas or sections of the grid
- **``grid-area: area;`` -** Used to specify a grid item's size and location. Requires *grid-template-areas*
- **``grid-area: horizontal_starting_line/vertical_starting line/horizontal_ending_line/vertical_ending_line;`` -** Used to specify a grid item's size and location. Does not require *grid-template-areas*
- **``grid-template-rows: value1 valueN;;`` -** Used to adjust the height of each grid row. Acceptable values includes px, percentage, cm, mm, in, etc. Instead of adding the values individually per row, you can instead put *repeat(number of repeats, value of height)* right after *grid-template-rows:*. Number of repeats can be *auto-fill* or *auto-fit* instead of just plain numbers. Auto fill fills up the whole container while auto fit collapses empty items and stretches some items to fit the container.
- **``grid-template-columns: value1 valueN;`` -** Used to adjust the width of each grid column. Acceptable values includes px, percentage, cm, mm, in, etc. Instead of adding the values individually per column, you can instead put *repeat(number of repeats, value of width)* right after *grid-template-columns:*. Number of repeats can be *auto-fill* or *auto-fit* instead of just plain numbers. Auto fill fills up the whole container while auto fit collapses empty items and stretches some items to fit the container.
- **``grid-template-rows: minmax(min value, max value);`` -** Used to add a mininum height and max height to a single grid row item. You can add multiple minmax separated by spaces
- **``grid-template-columns: minmax(min value, max value);`` -** Used to add a mininum height and max height to a single grid column item. You can add multiple minmax separated by spaces
- **``animation-name: name;`` -** Used to set the name of an animation you are about to make
- **``animation-duration: time;`` -**  Used to set the duration of the animation you are making. It accepts seconds (s) and milliseconds (ms) as values for time.
- **``animation-fill-mode: forwards;`` -** Used to ensure that the changes the animation made to your element remains permanent even after the animation duration is complete
- **``animation-iteration-count: number of iterations;`` -** Used to set the amount of times the animation will play. You can set the amount of times to infinite
- **``animation-timing-function: value;`` -** Used to configure the animation's style or movement speed(acceptable values include the ff: linear, ease, ease out, and ease in)
- **``animation-timing-function: cubic-bezier(x1, y1, x2, y2);`` -** Used to gain greater control over the configuration of the animation's style or movement speed 


### Text Properties
- **``<bold> text tags </bold>`` -** Used in the HTML file, makes text tags turn into bold characters
- **``<strong> text tags </strong>`` -** Used in the HTML file, makes text tags turn into strong characters
- **``<s> text tags </s>`` -** Used in the HTML file, makes text tags turn into strikethrough characters
- **``<u> text tags </u>`` -** Used in the HTML file, makes text tags turn into underlined characters
- **``<em> text tags </em>`` -** Used in the HTML file, makes text tags turn into italic characters

### Other Size/Placement Properties for CSS Elements
- **``#vw`` -** *vw* stands for *viewport width* and the number you give it will always be seen as a percent value. Sets a CSS element to x% of the viewport width.
- **``#vh`` -** *vh* stands for *viewport height* and the number you give it will always be seen as a percent value. Sets a CSS element to x% of the viewport height.
- **``#vmin`` -** *vmin* stands for *viewport mininum* and the number you give it will always be seen as a percent value. Sets a CSS element to x% of the viewport's smaller dimension.
- **``#vmax`` -** *vmax* stands for *viewport maximum* and the number you give it will always be seen as a percent value. Sets a CSS element to x% of the viewport's bigger dimension.


### Useful Codes
- **``CSS property: value !important;`` -** *!important*, allows a property to override all other properties
- **``@keyframes animation_name { 0% { CSS Elements } 100% { CSS Elements } }`` -** Used to add the actual animation to an already existing animation name. Multiple change points are allowed (e.g. 50%, 25%, etc)
- **``CSS property: var(variable_name, value);`` -** Used to create a variable with a value
- **``--variable_name: value;`` -** Used to place the variable somewhere thats easy to find for viewing/editing purposes
- **``:root { CSS }`` -** Used to apply CSS elements into the root of the website, which is the HTML element. 
- **``html_element:hover { CSS }`` -** Used to make an HTML element have unique CSS properties whenever the mouse hovers on top of it
- **``@media (max-height: value) { Applicable CSS Properties under media quary condition }`` -** *Media quary*, used to apply certain CSS properties when the screen size of the device viewing the website matches the height condition.
- **``@media (max-width: value) { Applicable CSS Properties under media quary condition }`` -** *Media quary*, used to apply certain CSS properties when the screen size of the device viewing the website matches the width condition.

## Additional Information For HTML and CSS
- You can put some of the codes within a code, this is called *nesting*. An example is putting *a tags* between or inside of *paragraph tags*
- A Class is like a blueprint to create an object that you want to make
- The style tags are only used if you want to code in some CSS into a HTML file. You don't need style tags if you are coding CSS elements into a CSS file. You can still add CSS elements to an HTML file even if the HTML and CSS stuff are in separate files.
- Usually, CSS elements at the bottom takes priority over CSS elements above
- You can get a variety of different font styles from this website: https://fonts.google.com/

## Learning Resources List
- Legacy (old) FCC Responsive Web Design Course that gives you a certificate and a chance to have stuff you can add to your portfolio (website) https://www.freecodecamp.org/learn/responsive-web-design/
- New FCC Responsive Web Design Course that gives you a certificate and a chance to have stuff you can add to your portfolio (website) https://www.freecodecamp.org/learn/2022/responsive-web-design/
- CSS From Zero to Hero (video) https://www.youtube.com/watch?v=1Rs2ND1ryYc
- FCC HTML5 and CSS3 Full Course From Scratch (video) https://www.youtube.com/watch?v=mU6anWqZJcc&list=PL0kSdkfSUSi_75tnbq_W2YDqWoJlw5MRW&index=76&t=5s