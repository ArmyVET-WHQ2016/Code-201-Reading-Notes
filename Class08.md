# Read: 09 - Forms and Events

**HTML Forms- The different forms control**

<input> element, looking at the additional input types provided when HTML5 was released, and the various UI controls and data collection enhancements they provide. Additionally, we look at the <output> element.

The <output> HTML element is a container element into which a site or app can inject the results of a calculation or the outcome of a user actio

non-<input> form controls and associated tools, 
- <select>
- <textarea>
- <meter>
- <progress>

**Styling web forms**
Some elements can be styled with few if any problems across platforms. These include the following elements:

T*he Good Elements*
<form>
<fieldset> and <legend>
Single-line text <input>s (e.g. type text, url, email...), except for <input type="search">.
Multi-line <textarea>
Buttons (both <input> and <button>)
<label>
<output>

*The bad Elements*
Some elements are more difficult to style, requiring more complex CSS or some more specific tricks:

Checkboxes and radio buttons
<input type="search">

*The ugly Elements*
Some elements can't be styled thoroughly using CSS. These include:

<input type="color">
Date-related controls such as <input type="datetime-local">
<input type="range">
<input type="file">
Elements involved in creating dropdown widgets, including <select>, <option>, <optgroup> and <datalist>.
<progress> and <meter>

**Fonts and Text**
- CSS font and text features can be used easily with any widget. By default, some widgets do not inherit font-family and font-size from their parents. 
- The inherit property value causes the property value to match the computed value of the property of its parent element; inheriting the value of the parent.

**Box Sizing**
-All text fields have complete support for every property related to the CSS box model, such as width, height, padding, margin, and border.

**Legend Placement**
-The <legend> element is okay to style, but it can be a bit tricky to control placement of it. By default it is always positioned over the top border of its <fieldset> parent, near the top left corner.
-The <fieldset> needs to be positioned too, so that the <legend> is positioned relative to it (otherwise the <legend> would be positioned relative to the <body>).

The <legend> element is very important for accessibility — it will be spoken by assistive technologies as part of the label of each form element inside the fieldset — but using a technique like the one above is fine.

Labels and controls
- Ensure that the <label>s are given the right font:

**Styling the submit button**
-The <button> element is really convenient to style with CSS; you can do whatever you want, even using pseudo-elements:

**Building a form structure**
- Apply the CSS to the HTML by adding the following line inside the HTML <head>:
- create your form by adding the outer <form> element:
- Inside the <form> tags, add a heading and paragraph to inform users how required fields are marked:
- add a larger section of code into the form, below our previous entry.

1. Why are forms so important in web development?*Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature*

2. When designing a form, what are some key things to keep in mind when it comes to user experience? *the elements that you are used and to structur them*

3. List 5 form elements and explain their importance.
1. <form> HTML element represents a document section containing interactive controls for submitting information.
2. The <label> HTML element represents a caption for an item in a user interface.
3. The <input> HTML element is used to create interactive controls for web-based forms
4. The <textarea> HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.
5.The <button> HTML element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology

**Learn *JS***

JavaScript s a programming language that allows you to implement complex things on web pages.a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. 
The place where we'll be adding all our code is inside the <script> element at the bottom of the HTML:

JavaScript operators allow us to perform tests, do math, join strings together, and other such things.

1. How would you describe events to a non-technical friend?are actions or occurrences *that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs.*

2. When using the addEventListener() method, what 2 arguments will you need to provide?the name of the event and a function to handle the event. 

3. Describe the event object. Why is the target within the event object useful?
is always a reference to the element the event occurred upon.

4. What is the difference between event bubbling and event capturing?
*bubbling* the browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so. from the innermost element that was clicked.
*capturing* The browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so.