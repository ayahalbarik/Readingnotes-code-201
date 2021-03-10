
# The <form> Element
The HTML <form> element is used to create an HTML form for user input
<form>
.
form elements
.
</form>

The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

## HTML Lists
HTML lists allow web developers to group a set of related items in lists

*Unordered HTML List*
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

The list items will be marked with bullets (small black circles) by default:

Example
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

**Ordered HTML List**
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

The list items will be marked with numbers by default:

Example
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>


### HTML Tables
HTML tables allow web developers to arrange data into rows and columns.

The <table> tag defines an HTML table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.

Example
A simple HTML table:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

## *JavaScript Events* ## 
HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

* . An HTML web page has finished loading
* .An HTML input field was changed
* .An HTML button was clicked
Often, when events happen, you may want to do something.

~JavaScript lets you execute code when events are detected.~

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:

<element event='some JavaScript'>
With double quotes:

<element event="some JavaScript">
In the following example, an onclick attribute (with code), is added to a <button> element:

Example
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
