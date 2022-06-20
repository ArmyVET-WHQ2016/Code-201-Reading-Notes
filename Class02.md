Basic of HTML, CSS, JS

Why Does it Matter
As we have learned in previous chapter creating a web page, requires proper use of HTML, CSS, and of course Javascript. Adding tags known as markup to the contents of the page does just that. Tags provide allows the browser to show the users the structure for the page by providing extra meaning. (Duckett, 2011) provides the following examples

Structural Markup:

-heading
Six levels of heading

-p paragragh
sorrounds the words that makes up the paragraph with opening and closing tag

-b Bold make characters appear bold

-i Italic make characters appear italic

-sup
contains characters that should be superscript such as suffixes of dates or mathematical concept

-sub
contain characters that should be superscript

-br line break
use if you want to add a line break inside the middle of a paragraph

-hr
to create break between themes  

Sematic Markup

Adds extra information to the page

strong
indicates that its contents has strong importance

blockquotes
used for quotes that take up an entire paragraph

q
used for shorter quotes that sit within a paragraph

abbr
a title attribute on the opening tag is used to specify the full term

cite
used to indicate where the citation is from

dfn
used to indicate the defining instance of a new term

address
is use to contain details for the author of the page

ins
used to show content that has been inserted into a document

del
can show text that has been deleted from it

s indicates something that is no longe accurate or relevant (but should not be deleted)

Introducing CSS:

CSS works by associating rules with HTML elements. Which governs how the content of specified elements should be displayed.

Rules of CSS contains:

Selector Indicate which element the rule applies to.

Declaration

Indicate how the elements referred to in the selector should be styled.
Are split in two parts that sits inside of curly brackets and are separated by a colon.
A value specify the settings you want to use for the chosen properties
Using External CSS:

link tells the browser where to find the CSS file used to style the page

href specifies the path to the CSS file

type specifies the type of document being linked to

rel specifies the relationship between the HTML page and the file its is linked to

style sits inside of the element of the page.

CSS Selectors

Universal Selectors applies to all elements in the document

Type Selector matches element names

Class Selector matches an element whose class attribues has a value that matches the one specified after the period symbol

ID Selector matches an element whose id attributes has a value that matches the one specified after the pound or hash symbol

Child Selectoe matches an element that is a direct child of another\

Descendant Selector mathches an element that is a descendent of another specified element

Adjacent Sibling Selector matches an element that is the next sibling of another

General Sibling Selector matches an element that is a sibling of another, although it does not have to be the directly preceding element

Basic Javascript Instructions:

Statements A steict is a series of instructions that a computer can follow one by one. Each individual instruction or step is know as a statement which should end with a semicolon.

Comments helps make your code easier to read and understand

Variable:

Before you can use a variable, you need to anounce that you want to use it by giving it a name called an identifier. A variable is more than one word, it is usuaClly written in camelCase. Once you create a variable, you can tell it what information you would like it to store for you. You assign a value to the variable The equal sign (=) is an assignment operator- it says that you are going to assign a value to the variable

var is an example of what call a keyword used to create a variable

Using Variable:

Store numbers
Store string
Store boolean
Rules for naming a variabe:

Can not start with a number
Must not use a dash or period
Cannot use keyword or reserved words
Case sensitive
Use name that describe the kind of information
If you is made up of more than one word, use capital letter for the first letter of every word after the first word
Array: Is a special type of variable. It doesn't just store one value; it stores a list of values

Expression Evaluates into a single value. Expression rely on things called operators, they allow programmers to create a single value from one or more values

Operators:

Arithmetic Which you can use with numbers to calculate the combined values of two costs.

String

symbol used to join the strings on either side of it
Comparison The operand does not have to be a single value or variabl name. An operand can be an expression(because each expression evaluates into a single value)

Logical Allows you to compare the results of more than one comparison operator. Are evaluated left to right.

Decision & Loops:

Decision Using the results of evaluation, you can decid which path your script should go down.
An expression is evaluated, which returns a value. Your code checks the current status of the script. This is commonly done by comparing two values using a comparison operator which returns a value of true or false.
A conditional statement says what to do in a given situation. Is based on a concept of if/then/else; if a condition is met, then your code executes one or more statements, else your code does something different
Loops Where you will want to perform the same set of steps repeatedly
Comparing operators: There is usually one operator and two operands. The operands are placed on each side of the operator. They can be values or variables

If Statement: Evaluates or check a condition. If the condition evaluates to true, any statements in the subsequent code block are executed

If else Statement: Checks a condition. If it resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead.