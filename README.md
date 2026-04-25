# NotesWeek1
DOM Manipulation & Event Handling Basics
This repository contains fundamental examples of interacting with the Web API via JavaScript to manipulate the Document Object Model (DOM), handle user events, and modify styles dynamically.

1. Introduction to the DOM

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

Key Concepts & Terms:

Selecting Elements: Before you can change an element, you must "catch" or select it. We use methods like document.getElementById("id_name") to target specific HTML elements.

Reading Values: Once selected, we can access the content inside an element using properties like .innerText (for the visible text) or .value (for input fields).

Overwriting Values: You can dynamically update the UI by assigning a new string to an element's .innerText.

2. Event Handling

Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them if desired.

Key Concepts & Terms:

onclick Attribute: This is an event handler attribute in HTML. It tells the browser to execute a specific JavaScript function when a user clicks the element (e.g., a button).

Alerts & Logging: * alert(): A built-in function that displays an island dialog with an optional message and an OK button.

console.log(): A method used to output messages to the web console, essential for debugging code and checking if variables hold the correct data.

3. Dynamic Styling (CSS in JS)

JavaScript allows you to access and modify the CSS of an element directly through the style object.

Key Concepts & Terms:

The .style Property: This property is used to get or set the inline style of an element.

CamelCase Naming: In CSS, properties are often hyphenated (e.g., background-color). In JavaScript, these are converted to camelCase (e.g., backgroundColor).

Property Manipulation: You can change visual aspects like color, fontSize, and backgroundColor instantly based on logic or user interaction.

4. DOM Traversal and Selection

Traversal is the act of moving through the DOM tree to find related elements.

Key Concepts & Terms:

Parent-Child Relationship: Elements nested inside other elements are children; the containing element is the parent.

Selection Methods:

getElementById(): Returns the element that has the ID attribute with the specified value.

querySelector(): A more flexible method that returns the first element that matches a specified CSS selector.

How to Use This Code

Selection: Use const element = document.getElementById("id").

Modification: Use element.innerText = "New Content" or element.style.color = "blue".

Interaction: Create functions and link them to HTML buttons using the onclick attribute.
