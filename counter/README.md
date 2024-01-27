# Counter
<img src="https://github.com/jhanvi2903/vanilla-javascript-projects/assets/70269514/ce1728df-498f-4e96-8c5f-d0e1f184f9e6" width="400" height="200">

### Key concepts:
* document.querySelectorAll()
* forEach()
* addEventListener()
* currentTarget property
* textContent

### Description:
#### 1. document.querySelectorAll()-
  * The querySelectorAll() method returns all elements that matches a CSS selector(s).
  * The querySelectorAll() method returns a NodeList.
  * The querySelectorAll() method throws a SYNTAX_ERR exception if the selector(s) is invalid
  * A NodeList is an array-like collection (list) of nodes.The nodes in the list can be accessed by index. The index starts 
   at 0. The length Poperty returns the number of nodes in the list.
  * Syntax - ```document.querySelectorAll(CSS selectors)  ```
  * Example(Select all elements with class="example") - ```document.querySelectorAll(".example"); ```
  * For more info - https://www.w3schools.com/jsref/met_document_queryselectorall.asp

#### 2. forEach()-
   * The forEach() method calls a function for each element in an array.
   * The forEach() method is not executed for empty elements.
   * Syntax- ```array.forEach(function(currentValue, index, arr), thisValue) ```
   * Example(Calls a function for each element in fruits:) -
     ```
     const fruits = ["apple", "orange", "cherry"];
     fruits.forEach(myFunction);
     ```
   * For more info - https://www.w3schools.com/jsref/jsref_foreach.asp

#### 3. currentTarget property-
   * The currentTarget property returns the element whose event listener triggered the event.
   * This property is read-only. This property is useful during capturing and bubbling.
   * The currenttarget property refers to the element whose event listener triggered the event, opposed to the target 
     property, which returns the element that triggered the event.
   * Syntax - ```event.currentTarget ```
   * Get the element that triggered the event: ```const element = event.currentTarget; ```
   * Get the name of the element that triggered the event: ```let text = event.currentTarget.tagName; ```
    
   
    





