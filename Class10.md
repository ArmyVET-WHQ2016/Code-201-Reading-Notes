# JS Debugging


## What went wrong 

**Types of Errors**
Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!
Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

**There are other common errors you'll come across in your code. This section highlights most of them.**

- SyntaxError: missing ; before statement
This error generally means that you have missed a semicolon at the end of one of your lines of code, but it can sometimes be more cryptic.
- SyntaxError: missing ) after argument list
The JavaScript exception "missing ) after argument list" occurs when there is an error with how a function is called.
- SyntaxError: missing ) after function body
it generally means that you've missed one of your curly braces from a function or conditional structure.
- SyntaxError: missing ) after property id
This error usually relates to an incorrectly formed JavaScript object, but in this case we managed to get it by changing
-SyntaxError: Unexpected token 
unexpected token" occur when a specific language construct was expected, but something else was provided. 
## Fixing Errors

*Go to the tab that you've got number-game-errors.html open in, and open your JavaScript console. You should see an error message along the following lines:*
- A red "x" to indicate that this is an error.
- An error message to indicate what's gone wrong: "TypeError: guessSubmit.addeventListener is not a function"
- A "Learn More" link that links through to an MDN page that explains what this error means in greater detail.
- The name of the JavaScript file, which links through to the Debugger tab of the developer tools. If you follow this link, you'll see the exact line where the error is highlighted.
- The line number where the error is, and the character number in that line where the error is first seen.


1. Name some key differences between a Syntax Error and a Logic Error.
* Syntax Errors- These are spelling errors in your code*
* Logic errors: These are errors where the syntax is actually correct but the code is not* 

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them. 
- unexpected identifer
- undefined


3. How will this topic continue to influence your long term goals?
* gives me the opportunity to be viligent in my coding and accuracy when copying coding*



The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

**Three panes in JavaScript**
- File list
The first pane on the left contains the list of files associated with the page you are debugging. Select the file you want to work with from this list.
- Source code
Set breakpoints where you want to pause execution. In the following image, the highlight on the number 18 shows that the line has a breakpoint set.
- Watch expressions and breakpoints
The right-hand pane shows a list of the watch expressions you have added and breakpoints you have set.

**JavaScript console**
The JavaScript console is an incredibly useful tool for debugging JavaScript that isn't working as expected. It allows you to run lines of JavaScript against the page currently loaded in the browser, and reports the errors encountered as the browser tries to execute your code, *click on the Debugger tab.*


1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development? *press Ctrl + Shift + S to open the JavaScript Debugger*

2. Define what a breakpoint is.
*Breakpoints, lists the breakpoints set on the page. In example.js, a breakpoint has been set on the statement listItems.push(inputNewItem.value);

3. What is the call stack?
*Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.*

## Things I want to know more about
