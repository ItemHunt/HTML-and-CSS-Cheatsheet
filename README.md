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
- **``<style> text </style>`` -** 
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

### Others
- **``<!DOCTYPE ...>`` -** HTML5 Website Version Identifier
- **``<!DOCTYPE html>`` -** Old HTML Website Version Identifier

## CSS Cheatsheet
### Essentials
- **``HTML_Structure { CSS Properties }`` -** Allows you to add CSS properties over all of the specified HTML Structure
- **``.class_name { CSS Properties }`` -** Allows you to create classes that can be used to add CSS elements to HTML elements that have the class

### CSS Properties
- **``background-color: color;`` -** Used to set the background color of something, it accepts general color names, RGB, hex codes, etc.
- **``background: color;`` -** Used to set the background color of something, it accepts general color names, RGB, hex codes, etc.
- **``color: color;`` -** Used to set the color of something, it accepts general color names, RGB, hex codes, etc.
- **``font-family: font_family_name;`` -** Used to set the font family of text
- **``text-align: alignment`` -** Used to align things

### Text Properties
- **``<bold> text tags </bold>`` -** Used in the HTML file, makes text tags turn into bold characters
- **``<strong> text tags </strong>`` -** Used in the HTML file, makes text tags turn into strong characters
- **``<s> text tags </s>`` -** Used in the HTML file, makes text tags turn into strikethrough characters
- **``<u> text tags </u>`` -** Used in the HTML file, makes text tags turn into underlined characters
- **``<em> text tags </em>`` -** Used in the HTML file, makes text tags turn into italic characters

### Useful Codes
- **``property: value !important;`` -** *!important*, allows a property to override all other properties

## Additional Information For HTML and CSS
- You can put some of the codes within a code, this is called *nesting*. An example is putting *a tags* between or inside of *paragraph tags*
- A Class is like a blueprint to create an object that you want to make
- The style tags are only used if you want to code in some CSS into a HTML file. You don't need style tags if you are coding CSS elements into a CSS file. You can still add CSS elements to an HTML file even if the HTML and CSS stuff are in separate files.
- Usually, CSS elements at the bottom takes priority over CSS elements above
- 

## Learning Resources List
- Legacy (old) FCC Responsive Web Design Course that gives you a certificate and a chance to have stuff you can add to your portfolio (website) https://www.freecodecamp.org/learn/responsive-web-design/
- New FCC Responsive Web Design Course that gives you a certificate and a chance to have stuff you can add to your portfolio (website) https://www.freecodecamp.org/learn/2022/responsive-web-design/
