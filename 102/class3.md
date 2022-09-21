# CSS Notes

## Here is what I learned from reading assignment 5

* **CSS** (Cascading Style Sheets) is what allows you to create a website that looks good, allows you to change the design of the content.

* You can use CSS to change the font color, the background, how things are spaced, and just the overall layout of the webpage.

* CSS is a rule based language, which means you define the rules by specifying what should be applied to each element or section.

* An example of this would be `h1 { color: red; font-size: 5em; }` which would make your header be the color red and the size that you set it to be.

* CSS rules open with a **selector** which means that this selects the element you are targeting.

* Next would be a set of curly braces `{ }` like this.

* Next you will insert a **declaration** which will take the form of **property** and **value** pairs.

* You can put in different properties in CSS, depending on what property you select.

* Examples of properties are: **color** which changes the color of the element, while something like **font-size** will change the size of your font.

* CSS is developed by the ground called *CSS Working Group* which help creates rules and standards for CSS to ensure a consistent experience.

* There are **three** ways to insert CSS into your webpage: **External CSS**, **Internal CSS**, and **Inline CSS**

* **External CSS** can be written in any text editor, but must be saved with a `.css` extension. It can not contain any HTML.

* **Internal CSS** should only be used with only one single HTML page has a unique style, and it is defined in the `<style>` element, located in the head section.

* **Inline CSS** should be used to apply a unique style for a single element, and should be added directly to the element itself.

* If an internal style if defined after the external style sheet, whatever element affected will follow the inline style and not the external, but if it is defined before the external style sheet, the element will follow the external style.

* If there are multiple styles specified for an HTML, it will follow a **Cascading Order** by following the rules as defined, where number 1 will have the highest priority.

1. Inline Style (Inside an HTML element)

2. External and internal style sheets (in the head section)

3. Browser default

* The CSS syntax for color will be `color: *color*|initial|inherit;` where **color** specifies the text color, **initial** sets the property to its default value, and **inherit** will inherit this property from its parent element.

## Here is what I learned from reading assignment 6

* **JavaScript** is a lightweight, interpreted, or just-in-time complied programming language with first-class functions.

* Javascript follows the ECMAScript Language Specifications (ECMA-262) and the ECMAScript Internationalization API standards.

* JavaScript and Java are two different languages.

* There are three major parts of JavaScript: The language itself, the DOM API, and the server API provided by server-side systems.

* You can use any text editor to write JavaScript.

* You can either **embed** or **include** JavaScript code directly into the HTML file. You use the `<script></script>` opening and closing tags.

* `alert()` will show a pop-up in the browser with the text that you include.

* `document.write` changes what is shown.

* `console.log` is what you can use to print out debugging information

* `prompt()` will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in.

* `confirm()` allows you to ask a yes/no question.

* `var` is the container for storing data such as variables.

* `let` declares what the variable is

* `const` declares values that cannot be changed.

[Go back to Home](../README.md)