# Understanding The Problem Domain Is The Hardest Part Of Programming
What is the hardest thing about writing code?
1.Learning a new technology
2.Naming things
3.Testing your code
4.Debugging
5.Fixing bugs
6.Making software maintainable

The idea behind the Protein Tracker application is that it allows a user to set a goal for the amount of protein to consume in a day.  The user can add protein amounts which are added to a total protein count that is tracked for that user.

when you create  a familiar problem domain,you will  find that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

so Why problem domains are hard?
programmer  are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

Make the problem domain easier
Get better at understanding the problem domain


## object in JS 
JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.
**objectName.propertyName**

var myObj = new Object(),
    str = 'myString',
    rand = Math.random(),
    obj = new Object();

    ###  What is the DOM?
The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.

const paragraphs = document.querySelectorAll("p");
// paragraphs[0] is the first <p> element
// paragraphs[1] is the second <p> element, etc.
alert(paragraphs[0].nodeName);

 when you write in JavaScript, but it uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, XML documents, and their component parts (e.g. elements). Every element in a document—the document as a whole, the head, tables within the document, table headers, text within the table cells—is part of the document object model for that document, so they can all be accessed and manipulated using the DOM and a scripting language like JavaScript...
