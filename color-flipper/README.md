# Color Flipper
<img src="https://github.com/jhanvi2903/vanilla-javascript-projects/assets/70269514/0334e299-b083-4eb5-803c-4fb64b8135ea" width="400" height="200">

### Key concepts:
* arrays
* document.getElementById()
* document.querySelector()
* addEventListener()
* document.body.style.backgroundColor
* Math.floor()
* Math.random()
* array.length

### Description:
#### 1. document.getElementById():-
  * The getElementById() method is one of the most common methods in the HTML DOM.
  * It is used almost every time you want to read or edit an HTML element.
  * The getElementById() method returns an element with a specified value.
  * The getElementById() method returns null if the element does not exist.
  * Syntax- ``` document.getElementById(elementID)```
 
#### 2. document.querySelector():-
   * The querySelector() method returns the first element that matches a CSS selector.
   * Syntax- ``` document.querySelector(CSS selectors)```
   * CSS selectors select HTML elements based on id, classes, types, attributes, values of attributes etc. For more details -[https://www.w3schools.com/cssref/css_selectors.php]
   * Examples -
      * Get the first p element: ```document.querySelector("p"); ```
      * Get the first element with class="example": ```document.querySelector(".example"); ```
   * To return all matches (not only the first), use the querySelectorAll() instead.
   * Both querySelector() and querySelectorAll() throw a SYNTAX_ERR exception if the selector(s) is invalid.

#### 3. addEventListener():-
  * The addEventListener() method attaches an event handler to an element.
  * Syntax- ```element.addEventListener(event, function, useCapture)```
   <img width="400" height="200" alt="image" src="https://github.com/jhanvi2903/vanilla-javascript-projects/assets/70269514/f5668e55-a26d-4824-b78e-0f2a3319e2fe">

#### 4. document.body.style.backgroundColor:-
  * The backgroundColor property sets or returns the background color of an element.
  * Return the backgroundColor property: ```object.style.backgroundColor ```
  * Set the backgroundColor property: ```object.style.backgroundColor = "color|transparent|initial|inherit" ```
  * Syntax- ```document.body.style.backgroundColor = "red";```
  * CSS color values- [https://www.w3schools.com/cssref/css_colors_legal.php]

#### 5. Math.floor():-
  * The Math.floor() method rounds a number DOWN to the nearest integer.

#### 6. Math.random():-
  * The Math.random() method returns a random number from 0 (inclusive) up to but not including 1 (exclusive).
  * Examples -
     * Return a random number between 0 and 10: ```let x = Math.random() * 10; ```
     * Return a random number between 0 and 100: ```let x = Math.random() * 100; ```
     * A random whole number between 1 and 10: ```let x = Math.floor((Math.random() * 10) + 1);  ```
     * Math.random() does not return a cryptographically secure number.
     * To return a cryptographically secure number- [https://www.w3schools.com/jsref/met_crypto_getrandomvalues.asp]
