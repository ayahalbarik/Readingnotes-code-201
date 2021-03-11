# Debugging and Error Handling

There are two types of errors in JavaScript.
 **The first** is a programming error, where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.

At a minimum, what we need from a debugger is the ability to stop program execution and then examine variables and objects at that point. It also helps if we can continue the program by steps, drill into functions, and examine network activity and the state of the DOM at any time. However, we can usually manage debugging if we have the ability to stop a program and examine object values

**The second** type of error occurs when the web page reader answers a question incorrectly, pushes the wrong button, or tries to type in a Social Security number when we’re expecting a name. Or the error can happen when we’re mixing libraries and something goes wrong between them. We’ll look at these kinds of errors first, and then we’ll get into the various browsers and their debugging capabilities.


If a JavaScript statement generates an error, then it throws an exception.At that point, the interpreter stops and looks for exception-handl ing code.
If you are anticipating that something in your codemay cause an error, you can use a set of statementsto handle the error (you meet them on p480).This is important because if the error is not handled,
the script will just stop processing and the user willnot know why. So exception-handling code should
inform users when there is a problem.


Error objects can help you find where your mistakes areand browsers have tools to help you read them.
PROPERTY | DESCRIPTION
------------ | -------------
name | Type of execution

Syntax Error  | Syntax has not been followed

HOW TO DEAL WITH ERRORS
1 .DEBUG THE SCRIPT TO FIX ERRORS
2 . HANDLE ERRORS GRACEFULLY
