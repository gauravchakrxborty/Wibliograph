Queries:
JavaScript atribute list
JavaScript methods list
onclick event 
Turnary Operator
====================================================================================================
====================================================================================================
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS TUTORIAL|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
====================================================================================================
0#JS Home                                                                                          |
====================================================================================================

JavaScript is a lightweight interpreted programming language. 
The web browser receives the JavaScript code in its original text form and runs the script from that. 
From a technical standpoint, 
most modern JavaScript interpreters actually use a technique called just-in-time compiling. 
The JavaScript source code gets compiled into a faster, binary format while the script is being used, 
so that it can be run as quickly as possible. 
However, JavaScript is still considered an interpreted language, 
since the compilation is handled at run time, rather than ahead of time.

====================================================================================================
1#JS Introduction by gaurav chakraborty                                                                                |
====================================================================================================

$JavaScript can change HTML Content

<DOCTYPE! html>
<html>
<head></head>
<body>
     <h2><What can JavaScript do?></h2>
	 <p> id="demo">JavaScript can change HTML content</p>
	 <button type="button" onclick='document.getElementById("demo").innerHTML = "Hello World"'>
     Click me!</button>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript can change HTML attribute values

<DOCTYPE! html>
<html>
<head></head>
<body>
     <h2>What can JavaScript do?</h2>
     <p>JavaScript can change HTML attribute value</p>
     <p>JavaScript changed the value of the source attribute of an image</p>
     <button type="button" onclick="document.getElementById('myImage').src = 'pic_bulbon.gif'">
	     Turn on the light</button>
            <img id="myImage" src="pic_turnoff.gif" style="width: 100px;">
     <button type="button" onclick="document.getElementById('myImage').src = 'pic_bulboff.gif'">
           Turn off the light</button>     
</body>
</html>
____________________________________________________________________________________________________

$JavaScript can change HTML style

<DOCTYPE! html>
<html>
<head></head>
<body>
     <h2>What can JavaScript do?</h2>
     <p id="demo">JavaScript can change HTML style</p>
     <button type="button" onclick="document.getElementById('demo').style.fontSize = '35px'">
           Click me!</button>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript can hide HTML elements

<DOCTYPE! html>
<html>
<head></head>
<body>
      <h2>What can JavaScript do?</h2>
      <p>JavaScript can hide HTML element</p>
      <button type="button" onclick="document.getElementById('demo').style.display='none'">
           Click me!</button>
</body>
</html>

____________________________________________________________________________________________________

$JavaScript can show HTML elements

<DOCTYPE! html>
<html>
<head></head>
<body>
      <h2>What can JavaScript do?</h2>
      <p>JavaScript can show hidden HTML element</p>
      <p id="demo" style="display:none">Hello World</p>
      <button id="button" onclick="document.getElelmentById('demo').style.display ='block'">
           Click me!</button>
</body>
</html>

====================================================================================================
2#JS Where To                                                                                      |
====================================================================================================

$The <script> Tag

<DOCTYPE! html>
<html>
<head></head>
<body>
      <h2>JavaScript in Body</h2>
      <p id="demo"></p>
     <script>
           document.getElementById("demo").innerHTML = "My first JavaScript";
      </script>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript Functions and Events

A JavaScript / function / is a block of JavaScript code, that can be executed when "called" for.
For example, a function can be a called when an event occurs, like when the user clicks a button.
____________________________________________________________________________________________________

$JavaScript in <head> or <body>

You can place any number of scripts in an HTML document.
Scripts can be placed in the <body>, or in the <head> section of an HTML page, or in both.

Placing scripts at the bottom of the <body> element improves the display speed, 
because script interpretation slows down the display.

____________________________________________________________________________________________________

$JavaScript in <head>

In this example, a JavaScript function is placed in the <head> section of an HTML page.
The function is invoked (called) when a button is clicked:

<DOCTYPE! html>
<html>
<head>
      <script>
           function myFunction(){
               document.getElementById("demo").innerHTML = "Paragraph Changed";
             }
      </script>
</head>
<body>
      <h2>Demo JavaScript in <head> tag</h2>
      <p id="demo">A Paragraph</p>
      <button type="button" onclick="myFunction()">Try it</btton>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript in <body>

In this example, a JavaScript function is placed in the <body> section of an HTML page.
The function is invoked (called) when a button is clicked:

<DOCTYPE! html>
<html>
<head></head>
</body>
      <h2>Demo JavaScript in <body> tag</h2>
      <p id="demo">A Paragraph</p>
      <button type="button" onclick="myFunction()">Try it!</button>
      <script>
      function = myFunction(){
          document.getElementById("demo").innerHTML = "Paragraph Changed.";
          }
      </script>
</body>
</html>
____________________________________________________________________________________________________

$External JavaScript

Scripts can also be placed in external files.
External scripts are practical when the same code is used in many different web pages.
JavaScript files have the file extension .js.
To use an external script, put the name of the script file in the src (source) attribute of a <script> tag.
You can place an external script reference in <head> or <body> as you like.
The script will behave as if it was located exactly where the <script> tag is located.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <h2>Demo External JavaScript</h2>
       <p id="demo">A Paragraph</p>
       <button type="button" onclick="myFunction()">Try it!</button>
       <p>This Example linksto "myScript.js"</p>
       <p>(myFunction is stored in myScript.js)</p>
       <script src="myScript.js"></script>
</body>
<html>

IN JAVASCRIPT FILE::

function = myFunction(){
      document.getElementById("demo").innerHTML = "Paragraph Changed";
}
____________________________________________________________________________________________________

$External JavaScript Advantages

Placing scripts in external files has some advantages:

It separates HTML and code
It makes HTML and JavaScript easier to read and maintain
Cached JavaScript files can speed up page loads

To add several script files to one page  - use several script tags:
<script src="mySCript1.js"></script>
<script src="mySCript2.js"></script>
____________________________________________________________________________________________________

$External Reference

An external script can be referenced in 3 different ways:

#With a full URL: 
<script src=”http://www.w3schools.com/myScript.js”></script>

#With a file path:
<script src="/js/mySCript.js"></script>

#Without any path:
<script src="myScript.js"></script>

====================================================================================================
3#JS Output                                                                                        |
====================================================================================================

$Introduction

JavaScript can "display" data in different ways:

-Writing into an HTML element, using innerHTML.
-Writing into the HTML output using document.write().
-Writing into an alert box, using window.alert().
-Writing into the browser console, using console.log().
-Writing into the browser function, using window.print().
____________________________________________________________________________________________________

$innerHTML

Changing the innerHTML property of an HTML element is a common way to display data in HTML.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <h2>My First Webpage</h2>
       <p>My First Paragraph</p>
       <p id="demo"></p>
       <script>
             document.getElementById("demo").innerHTML = 5 + 6;
       </script>
</body>
</html>
____________________________________________________________________________________________________

$document.write()

Using document.write() after an HTML document is loaded, will delete all existing HTML.
The document.write() method should only be used for testing.

EXAMPLE 1:::
<DOCTYPE! html>
<html>
<head></head>
<body>
       <h2>My First Webpage</h2>
       <p>My First Paragraph</p>
       <p>Calling document.write will overwrite after document finished loading </p>
       <script>
             document.write(5+6);
       </script>
</body>
</html>

EXAMPLE 2:::
<DOCUMENT! html>
<html>
<head></head>
<body>
       <h2>My First WebPage</h2>
       <p>My First Paragraph</p>
       <button type="button" onclick="document.write(5+6)">Try it!</button>
</body>
</html>

____________________________________________________________________________________________________

$window.alert()

In JavaScript, the window object is the global scope object. 
This means that variables, properties, and methods by default belong to the window object. 
This also means that specifying the window keyword is optional.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <h1>My First WebPage</h1>
       <p>My First Paragraph</p>
       <script>
             alert(5+6);
       </script>
</body>
</html>
____________________________________________________________________________________________________

$console.log()

For debugging purposes, you can call the console.log() method in the browser to display data.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <h2>My First WebPage</h2>
       <p>My First Paragraph</p>
       <Script>
             console.log(5+6);
       </script>
</body>
</html>
____________________________________________________________________________________________________

$window.print()

JavaScript does not have any print object or print methods.
You cannot access output devices from JavaScript.
The only exception is that you can call the window.print(),method to print the content.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <button type="button" onclick="window.print">Print this page</button>
<body>
</html>

====================================================================================================
4#JS Statements                                                                                    |
====================================================================================================

$Introduction

<DOCTYPE! html>
<html>
<head>
       <title>JavaSscript Statements Example 1</title>
</head>
<body>
       <h2>JavaScript Statement Example 1</h2>
       <p>A <b>JavaScript program</b> is a list of <b>statements</b> to be executed by computer</p>
       <p id="demo"></p>
       <script>
             letx, y, z;  //Statement 1
             x = 5;       //Statement 2
             y = 6;       //Statement 3
             z = x + y;   //Statement 4
                   document.getElementById("demo").innerHTML = 
                         "The value of z is" + z + ".";
       </script>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript Programs

A computer program is a list of "instructions" to be "executed" by a computer.
In a programming language, these programming instructions are called statements.
A JavaScript program is a list of programming statements.
In HTML, JavaScript programs are executed by the web browser.
____________________________________________________________________________________________________

$JavaSCript Statements

JavSciprt satements are composed of -->
Values, Operators, Expressions, Keywords and Comments.
The Statements are executed by browser, one by one, in the same order as they are written.

In the below example the statements tells the wrowser to write "Hello World" inside HTML element.

<DOCTYPE! html>
<html>
<head>
       <title>JavaScript Satement Example 2</title>
</head>
<body>
       <h2>In HTML, JavaScript Statementss are executed by the browser</h2>
       <p id="demo"></p>
       <script>
             document.getElementById("demo").innerHTML = "Hello World!";
       </script> 
</body>
</html>
____________________________________________________________________________________________________

$Semicolons

Semicolons separates JavaScript Statements.
Add a semicolon at the end of each executable statement.

<DOCTYPE! html>
<html>
<head></head>
<body>
       <h2>JavaScript Statement Example 3</h2>
       <p id="demo"></p>
       <script>
             let a, b, c;
             a = 5;           //We can also write the same as a = 5; b = 3; c = a + b;
             b = 3:           //When separated by semicolons 
             c = a + b;       //Multiple statements on one line are allowed
                   document.getElementById("demo").innerHTMl = c;
       </script>
</body>
</html>
____________________________________________________________________________________________________

$JavaScript White Space

JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

The following lines are equivalent:

let person = "Hege";
let person="Hege";

A good practice is to put spaces around operators ( = + - * / ):

let x = y + z;
____________________________________________________________________________________________________

$JavaScript Line length and Line breaks

For best readability, programmers often like to avoid code lines longer than 80 characters.
The best place to break it is after an operator or comma. 

<DOCTYPE! html>
<html>
<head>JavaScript Statement 4</head>
<body>
       <h2>JavaScript Statement Example 4</h2>
       <p>The best place to beak a code line is after an operator or a comma<p>
       <p id="demo"></p>
       <script>
             document.getElementById("demo").innerHTML =
                   "Hello World!";
       </script>
</body>
</html>
____________________________________________________________________________________________________

$JavaSCript Code Blocks

JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.

The purpose of code blocks is to define statements to be executed together.

One place you will find statements grouped together in blocks, is in JavaScript functions:

<DOCTYPE! html>
<html>
<head>
       <title>JavaSCript Statements</title>
</head>
<body>
       <h2>JavaScript Statement Example 5</h2>
       <p>JavaScript Code blocks are written between { and }</p>
       <button type="button" onclick="myFunction">Click me!</button>
       <p id="demo1"></p>
       <p id="demo2"></p>
       <script>
            function myFunction() {
                  document.getElementByid("demo1").innerHTML = "Hello World!";
                  document.getElementById("demo2").innerHTML = "How are you";
            }
       </script>
</body>
</html>
____________________________________________________________________________________________________

$JavaSCript Keywords

JavaScript statements often start with a keyword to identify the JavaScript action to be performed.

Here is a list of some common Keywords:

Keyword                  Description
---------                -----------          
var                      Declares a variable
let                      Declares a block variable
const                    Declares a block constant
if                       Marks a block of statements to be executed on a condition
switch                   Marks a block of statements to be executed in different cases
for                      Marks a block of statements to be exwcuted in a loop
function                 Declares a function
return                   Exits a function
try                      Implements error handling to a bulding of statements

====================================================================================================
5#JS Syntax                                                                                        |
====================================================================================================

$JavaScript values

The JavaScript syntax defines two types of values:
---> Fixed values     //Fixed values are called ""Literals""
---> Variable values  //Variable values are called Variables

// How to create variables:
var x;
let y;

// How to use variables:
x = 5;
y = 6;
let z = x + y;
____________________________________________________________________________________________________

$JavaScript Leterals

The two most important syntax rules for fixed values are:

1.Numbers are written with or withour decimals: 10.50 / 1001
2.Strings are text, written within double or single quotes: "John Doe" / 'John doe'

____________________________________________________________________________________________________

$JavaScript Quotation

The double and single quotation should be used alternativly.

Example:The single quotes will be nested within the double quotation or vise versa --> "''"/'""'
____________________________________________________________________________________________________

$JavaScript Variables

In a programming language, variables are used to store data values.
JavaScript uses the keywords var, let and const to declare variables.
An equal sign is used to assign values to variables.
In this example, x is defined as a variable. Then, x is assigned (given) the value 6:

<DOCTYPE! html>
<html>
<head>
        <title>JavaScript Syntax</title>
</head>
<body>
        <h2>JavaScript Variable</h2>
        <p>In this example, x is defined as a variable.
               Then, x is assinged the value of 6</p>
        <p id="demo"></p>
        <script>
               let x;
               x = 6;
               document.getElementById("demo").innerHTML = x ;
        </script>
</body>
<html>
____________________________________________________________________________________________________

$JavaScript Operators
____________________________________________________________________________________________________

$JavaScript Expressions
____________________________________________________________________________________________________

$JavaScript Keywords
____________________________________________________________________________________________________

$JavaScript Comments
____________________________________________________________________________________________________

$JavaSCript Identifiers/Names

Identifiers are JavaScript names.
Identifiers are used to name variables and keywords, and functions.
The rules for legal names are the same in most programming languages.

A JavaScript name must begin with:

A letter (A-Z or a-z)
A dollar sign ($)
Or an underscore (_)
Subsequent characters may be letters, digits, underscores, or dollar signs.
____________________________________________________________________________________________________

$JavaScript is Case Sensitive
____________________________________________________________________________________________________

$JavaScript and Camel Case
____________________________________________________________________________________________________

$JavaScript Character Set

====================================================================================================
6#JS Comments                                                                                      |
====================================================================================================

$Introduction

JavaScript comments can be used to explain JavaScript code,  and to make it more readable.
JavaScript comments can alse be used to prevent execution, when testing alternative code.
____________________________________________________________________________________________________

$Single-Line Comments

Single-line comments start with //.
Any text between // and the end of the line will be ignored by JavaScript 

<DOCTYPE! html>
<html>
<head>
       <title>JavaScript Comments</title>
</head>
<body>
       <h2></h2>
       <p id="demo"></p>
       <script>
             function myFunction() {
                  let x = 5;
                  let y = x + 2;
             } 
       </script>
</body>
</html>
____________________________________________________________________________________________________

$Multi-Line Comments

Multi-line comments start with /* and end with */.
Any text between /* and */ will be ignored by JavaScript.
This example uses a multi-line comment (a comment block) to explain the code:

<DOCTYPE! html>
<html>
<head>
       <title>JavaScript Comments</title>
</head>
<body>
       <h1 id="myHeader"></h1>
       <p id="myParagraph"></p>
       <script>
       
       /* <--- This is multi line commment
       This code below will change
       The header with id = "myHeader"
       The paragraph with id = "myParagraph" 
       */ <--- This is multi line comment

       document.getElementById("myHeader").inerHtml = "My First Heading";
       document.getElementById("myParagraph").innerHTML = "My First Parapgraph";
       </script>
</body>
</html>

____________________________________________________________________________________________________

$Using Comments to Prevent Execution

Using comments to prevent execution of code is suitable for code testing.
Adding // in front of a code line changes the code lines from an executable line to a comment.
This example uses // to prevent execution of one of the code lines:

<DOCTYPE! html>
<html>
<head>JavaScript Comments</head>
<body>
        <h2>JavaScript Comments Example</h2>
        <h2 id="MyHeader"></h2>
        <p id="myParagraph"></p>
        <script>
               //document.getElementById(myHeader).innerHTML = "My First Page";
               //document,getElementById("myParagraph").innerHTML = "My First Paragraph";
               document.getElementById("myParagraph").innerHTML = "The comment-block is not executed";
        </script>
        <p>The line starting with // is not executed</p>
</body>
</html>

====================================================================================================
7#JS Variables                                                                                     |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Just Like Algebra
____________________________________________________________________________________________________

$JavaScript Identifiers
____________________________________________________________________________________________________

$The Assignment Operator
____________________________________________________________________________________________________

$JavaScript Data Type
____________________________________________________________________________________________________

$Declaring a JavaScript Variable
____________________________________________________________________________________________________

$One Statement, Many Variables
___________________________________________________________________________________________________

$Value = undefined
____________________________________________________________________________________________________

$Re-Declaring JavaScript Variables
____________________________________________________________________________________________________

$JavaScript Arithmetic
____________________________________________________________________________________________________

$JavaScript Dollar Sign $
____________________________________________________________________________________________________

$JavaScript Underscore (_)

====================================================================================================
8#JS Let                                                                                           |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Cannot be Redeclared
____________________________________________________________________________________________________

$Block Scope
____________________________________________________________________________________________________

$Redeclaring Variables
____________________________________________________________________________________________________

$Difference Between var, let and const
____________________________________________________________________________________________________

$Browser Support
____________________________________________________________________________________________________

$Redeclaring
____________________________________________________________________________________________________

$Let Hoisting

====================================================================================================
9#JS Const                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Cannot be Reassigned
____________________________________________________________________________________________________

$Must be Assigned
____________________________________________________________________________________________________

$Constant Objects and Arrays
____________________________________________________________________________________________________

$Constant Arrays
____________________________________________________________________________________________________

$Constant Objects
____________________________________________________________________________________________________

$Difference Betwenn var, let and const
____________________________________________________________________________________________________

$Browser Support
____________________________________________________________________________________________________

$Block Scope
____________________________________________________________________________________________________

$Redeclaring
____________________________________________________________________________________________________

$Hoisting

====================================================================================================
10#JS Operators                                                                                    |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Assignment
____________________________________________________________________________________________________

$JavaScript Addition
____________________________________________________________________________________________________

$JavaScript Multiplication
____________________________________________________________________________________________________

$Types of JavaScript Operators
____________________________________________________________________________________________________

$JavaSCript Arithmetic Operators
____________________________________________________________________________________________________

$JavaScript Assignment Operators
____________________________________________________________________________________________________

$JavaSCript Comparison Operators
____________________________________________________________________________________________________

$JavaSCript String Comparison
____________________________________________________________________________________________________

$JavaScript String Addition
____________________________________________________________________________________________________

$Adding Strings and Numbers
____________________________________________________________________________________________________

$JavaScript Logical Operators
____________________________________________________________________________________________________

$JavaScript Type Operators
____________________________________________________________________________________________________

$JavaScript Bitwise Operators

====================================================================================================
11#JS Arithmetic                                                                                   |
====================================================================================================

$JavaScript Arithmetic Operators
____________________________________________________________________________________________________

$Arithmetic Operations
____________________________________________________________________________________________________

$Operators and Operands
____________________________________________________________________________________________________

$Adding
____________________________________________________________________________________________________

$Subtracting
____________________________________________________________________________________________________

$Multiplying
____________________________________________________________________________________________________

$Dividing
____________________________________________________________________________________________________

$Remainder
____________________________________________________________________________________________________

$Incrementing
____________________________________________________________________________________________________

$Decrementing
____________________________________________________________________________________________________

$Exponentiation
____________________________________________________________________________________________________

$Operator Precedence

====================================================================================================
12#JS Assignment                                                                                   |
====================================================================================================

$JavaScript Assignment Operators
____________________________________________________________________________________________________

$Shift Assignment Operators
____________________________________________________________________________________________________

$Bitwise Assignment Operators
____________________________________________________________________________________________________

$Logical Assignment Operators
____________________________________________________________________________________________________

$The = Operator
____________________________________________________________________________________________________

$The += Operator
____________________________________________________________________________________________________

$The -= Operator
____________________________________________________________________________________________________

$The *= Operator
____________________________________________________________________________________________________

$The **= Operator
____________________________________________________________________________________________________

$The /= Operator
____________________________________________________________________________________________________

$The %= Operator
____________________________________________________________________________________________________

$The <<= Operator
____________________________________________________________________________________________________

$The >>= Operator
____________________________________________________________________________________________________

$The >>>= Operator
____________________________________________________________________________________________________

$The &= Operator
____________________________________________________________________________________________________

$The |= Operator
____________________________________________________________________________________________________

$The ^= Operator
____________________________________________________________________________________________________

$The &&= Operator
____________________________________________________________________________________________________

$The ||= Operator
____________________________________________________________________________________________________

$The ??= Operator

====================================================================================================
13#JS Data Types                                                                                   |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The Concept of DataTypes
____________________________________________________________________________________________________

$JavaScript Types are Dynamics
____________________________________________________________________________________________________

$JavaScript Strings
____________________________________________________________________________________________________

$JavaScript Numbers
____________________________________________________________________________________________________

$Exponential Notation
____________________________________________________________________________________________________

$JavaScript Bigint
____________________________________________________________________________________________________

$JavaScript Boolens
____________________________________________________________________________________________________

$JavaScript Arrays
____________________________________________________________________________________________________

$JavaScript Objects
____________________________________________________________________________________________________

$The typeof Operator
____________________________________________________________________________________________________

$Undefined
____________________________________________________________________________________________________

$Empty Values

====================================================================================================
14#JS Functions                                                                                    |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Function Syntax
____________________________________________________________________________________________________

$Function Invocation
____________________________________________________________________________________________________

$Function Return
____________________________________________________________________________________________________

$The () Operator
____________________________________________________________________________________________________

$Functions Used as Variable Values
____________________________________________________________________________________________________

$Local Variables

====================================================================================================
15#JS Objects                                                                                      |
====================================================================================================

$Real Life Objects, Properties and Methords
____________________________________________________________________________________________________

$JavaScript Objects
____________________________________________________________________________________________________

$Object Defination
____________________________________________________________________________________________________

$Object Properties
____________________________________________________________________________________________________

$Accessing Object Properties
____________________________________________________________________________________________________

$Object Methods
____________________________________________________________________________________________________

$What is "this" ?
____________________________________________________________________________________________________

$The "this" Keyword
____________________________________________________________________________________________________

$Accessing Object Methods
____________________________________________________________________________________________________

$Do not declare String, Number and Boolens as Objects

====================================================================================================
16#JS Events                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$HTML Events
____________________________________________________________________________________________________

$Common HTML Events
____________________________________________________________________________________________________

$JavaScript Event Handlers

====================================================================================================
17#JS Strings                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$String.length
____________________________________________________________________________________________________

$Escape Character
____________________________________________________________________________________________________

$Breaking Long Code Lines
____________________________________________________________________________________________________

$JavaScript Strings as Objects

====================================================================================================
18#JS String Methods                                                                               |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript String Length
____________________________________________________________________________________________________

$Extracting String Parts
____________________________________________________________________________________________________

$JavaSCript String slice()
____________________________________________________________________________________________________

$JavaScript String substring()
____________________________________________________________________________________________________

$JavaScript String substr()
____________________________________________________________________________________________________

$Replacing String Content
____________________________________________________________________________________________________

$JavaSCript String ReplaceAll()
____________________________________________________________________________________________________

$Converting to Upper and Lower Case
____________________________________________________________________________________________________

$JavaSCript String toUpperCase()
____________________________________________________________________________________________________

$JavaSCript String toLowerCase()
____________________________________________________________________________________________________

$JavaScript String concat()
____________________________________________________________________________________________________

$JavaScript String trim()
____________________________________________________________________________________________________

$JavaScript String trimStart()
____________________________________________________________________________________________________

$JavaSCript String trimEnd()
____________________________________________________________________________________________________

$JavaSCript String Padding
____________________________________________________________________________________________________

$JavaSCript String padStart()
____________________________________________________________________________________________________

$JavaSCript String padEnd()
____________________________________________________________________________________________________

$Extracting String Characters
____________________________________________________________________________________________________

$JavaScript String charAt()
____________________________________________________________________________________________________

$JavaScript String charCodeAt()
____________________________________________________________________________________________________

$Property Access
____________________________________________________________________________________________________

$Concerting a String to an Array
____________________________________________________________________________________________________

$JavaScript String split()

====================================================================================================
19#JS String Search                                                                                |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaSCript String indexOf()
____________________________________________________________________________________________________

$JavaScript String lastIndexOf()
____________________________________________________________________________________________________

$JavaScript String search()
____________________________________________________________________________________________________

$Did You Notice?
____________________________________________________________________________________________________

$JavaScript String match()
____________________________________________________________________________________________________

$JavaSCript String matchAll()
____________________________________________________________________________________________________

$JavaScript String includes()
____________________________________________________________________________________________________

$JavaScript String startsWith()
____________________________________________________________________________________________________

$JavaScript String endsWith()

====================================================================================================
20#JS String Templates                                                                             |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Back-Tics Syntax
____________________________________________________________________________________________________

$Quotes Inside Stings
____________________________________________________________________________________________________

$Multiline Strings
____________________________________________________________________________________________________

$Interpolation
____________________________________________________________________________________________________

$Variable Substitutions
____________________________________________________________________________________________________

$Expression Substitution
____________________________________________________________________________________________________

$HTML Templates
____________________________________________________________________________________________________

$Browser Support

====================================================================================================
21#JS Numbers                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Numbers are Always 64-bit Floaying Point
____________________________________________________________________________________________________

$Integer Precision
____________________________________________________________________________________________________

$Floating Precision
____________________________________________________________________________________________________

$Adding Numbers and Strings
____________________________________________________________________________________________________

$Numeric Strings
____________________________________________________________________________________________________

$NaN - Not a Number
____________________________________________________________________________________________________

$infinity
____________________________________________________________________________________________________

$Hexadecimal
____________________________________________________________________________________________________

$JavaScript Numbers as Objects

====================================================================================================
22#JS BigInt                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Integer Accuracy
____________________________________________________________________________________________________

$How to Create a BigInt
____________________________________________________________________________________________________

$BigInt: A new JavaSCript Datatype
____________________________________________________________________________________________________

$BigInt Operators
____________________________________________________________________________________________________

$BigInt Decimals
____________________________________________________________________________________________________

$BigInt Hex, Octal and Binary
____________________________________________________________________________________________________

$Precision Curiosity
____________________________________________________________________________________________________

$Browser Support
____________________________________________________________________________________________________

$Minimum and Mazimum Safe Integers
____________________________________________________________________________________________________

$New Number Methods
____________________________________________________________________________________________________

$The Number.isInteger() Method
____________________________________________________________________________________________________

$The Number.isSafeInteger() Method

====================================================================================================
23#JS Number Methods                                                                               |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The toString() Method
____________________________________________________________________________________________________

$The toExponential() Method
____________________________________________________________________________________________________

$The toFixed Method
____________________________________________________________________________________________________

$The toPrecision() Method
____________________________________________________________________________________________________

$The valueOf() Method
____________________________________________________________________________________________________

$Converting Variables to Numbers
____________________________________________________________________________________________________

$The Number() Method
____________________________________________________________________________________________________

$The Number() Method Used on Dates
____________________________________________________________________________________________________

$The parseInt() Method
____________________________________________________________________________________________________

$The parseFloat() Method
____________________________________________________________________________________________________

$Number Object Methods
____________________________________________________________________________________________________

$The Number.isInteger() Method
____________________________________________________________________________________________________

$The Number.isSafeInteger() Method
____________________________________________________________________________________________________

$The Number.parseFloat() Method
____________________________________________________________________________________________________

$The Number.parseInt() Method

====================================================================================================
24#JS Number Properties                                                                            |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript EPSILON
____________________________________________________________________________________________________

$JavaSCript MAX_VALUE
____________________________________________________________________________________________________

$JavaScript MAX_SAFE_INTEGER
____________________________________________________________________________________________________

$JavaSCript MIN_SAFE_INTEGER
____________________________________________________________________________________________________

$JavaSCript POSITIVE_INFINITY
____________________________________________________________________________________________________

$JavaSCript NEGETIVE_INFINITY
____________________________________________________________________________________________________

$JavaScript NaN -Not a Number

====================================================================================================
25#JS Arrays                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Why use Arrays?
____________________________________________________________________________________________________

$Creating and Array
____________________________________________________________________________________________________

$Using the JavaScript Keyword new
____________________________________________________________________________________________________

$Accssing Array Elements
____________________________________________________________________________________________________

$Changing an Array Element
____________________________________________________________________________________________________

$Converting an Array to a String
____________________________________________________________________________________________________

$Acess the Full Array
____________________________________________________________________________________________________

$Arrays are Objects
____________________________________________________________________________________________________

$Array Elements Can Be Objects
____________________________________________________________________________________________________

$Array Properties and Methods
____________________________________________________________________________________________________

$The Length Property
____________________________________________________________________________________________________

$Accessing the First Array Element
____________________________________________________________________________________________________

$Accessing th Last Array Element
____________________________________________________________________________________________________

$Looping Array Elements
____________________________________________________________________________________________________

$Adding Array Elements
____________________________________________________________________________________________________

$Associative Arrays
____________________________________________________________________________________________________

$The Difference between Arrays and Objects
____________________________________________________________________________________________________

$When to Use Arrays and When to use Objects
____________________________________________________________________________________________________

$JavaScript new Array()
____________________________________________________________________________________________________

$How to recognize an Array

====================================================================================================
26#JS Array Methods                                                                                |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Array lenght
____________________________________________________________________________________________________

$JavaScript Array toString()
____________________________________________________________________________________________________

$Popping and Pushing
____________________________________________________________________________________________________

$JavaScript Array pop()
____________________________________________________________________________________________________

$JavaScript Array push()
____________________________________________________________________________________________________

$Shifting Element
____________________________________________________________________________________________________

$JavaScript Array shift()
____________________________________________________________________________________________________

$JavaScript Array unshift()
____________________________________________________________________________________________________

$Changing Elements
____________________________________________________________________________________________________

$JavaScript Array length
____________________________________________________________________________________________________

$JavaScript Array delete()
____________________________________________________________________________________________________

$Merging (Concatenating) Arrays
____________________________________________________________________________________________________

$Flattening an Array
____________________________________________________________________________________________________

$Browser Support
____________________________________________________________________________________________________

$Splicing and Slicing Arrays
____________________________________________________________________________________________________

$JavaScript Array splice()
____________________________________________________________________________________________________

$Using splice() to Remove Elements
____________________________________________________________________________________________________

$JavaScript Array slice()
____________________________________________________________________________________________________

$Automatic toString()
____________________________________________________________________________________________________

$Finding Max and Min Values in an Array
____________________________________________________________________________________________________

$Sorting Arrays

====================================================================================================
27#JS Array Sort                                                                                   |
====================================================================================================

$Sorting an Array
____________________________________________________________________________________________________

$Reversing an Array
____________________________________________________________________________________________________

$Numeric Sort
____________________________________________________________________________________________________

$The Compare Function
____________________________________________________________________________________________________

$Sorting an Array in Random Order
____________________________________________________________________________________________________

$The Fisher Yates Method
____________________________________________________________________________________________________

$Find the Lowest (or Highest) Array Value
____________________________________________________________________________________________________

$Using Math.max() on an Array
____________________________________________________________________________________________________

$Using math.min() on an Array
____________________________________________________________________________________________________

$My Min/Max JavaSCript methods
____________________________________________________________________________________________________

$Sorting Object Arrays
____________________________________________________________________________________________________

$Stable Array sort()

====================================================================================================
28#JS Array Iteration                                                                              |
====================================================================================================

$JavaScript Array forEach()
____________________________________________________________________________________________________

$JavaScript Array map()
____________________________________________________________________________________________________

$JavaScript flatMap()
____________________________________________________________________________________________________

$JavaScript Array filter()
____________________________________________________________________________________________________

$JavaScript Array reduce()
____________________________________________________________________________________________________

$JavaScript Array reduceRight()
____________________________________________________________________________________________________

$JavaSCript Array every()
____________________________________________________________________________________________________

$JavaSCript Array some()
____________________________________________________________________________________________________

$JavaScript Array indexOf()
____________________________________________________________________________________________________

$JavaScript Array lastIndexOf()
____________________________________________________________________________________________________

$JavaScript Array find()
____________________________________________________________________________________________________

$JavaSCript Array findIndex()
____________________________________________________________________________________________________

$JavaScript Array.from()
____________________________________________________________________________________________________

$JavaScript Array Keys()
____________________________________________________________________________________________________

$JavaSCript Array entries()
____________________________________________________________________________________________________

$JavaScript Array includes()
____________________________________________________________________________________________________

$JavaScript Array Spread (...)

====================================================================================================
29#JS Array Const                                                                                  |
====================================================================================================

$ECMAScript  2015 (ES6)
____________________________________________________________________________________________________

$Cannot be Reassigned
____________________________________________________________________________________________________

$Arrays are Not Constants
____________________________________________________________________________________________________

$Elements Can be Reassigned
____________________________________________________________________________________________________

$Assigned when Declared
____________________________________________________________________________________________________

$Const Block Scope
____________________________________________________________________________________________________

$Redeclaring Arrays

====================================================================================================
30#JS Dates                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Date Output
____________________________________________________________________________________________________

$Creating Date Objects
____________________________________________________________________________________________________

$JavaScript new Date()
____________________________________________________________________________________________________

$new Date(date string)
____________________________________________________________________________________________________

$new Date(year, month, ...)
____________________________________________________________________________________________________

$Using 6, 4, 3 or 2 Numbers
____________________________________________________________________________________________________

$Previous Century
____________________________________________________________________________________________________

$new Date(milliseconds)
____________________________________________________________________________________________________

$Date Methods
____________________________________________________________________________________________________

$Displaying Dates

====================================================================================================
31#JS Date Formats                                                                                 |
====================================================================================================

$JavaScript Date Input
____________________________________________________________________________________________________

$JavaSscript Date Date Output
____________________________________________________________________________________________________

$JavaScript ISO Dates
____________________________________________________________________________________________________

$ISO Dates (Year and Month)
____________________________________________________________________________________________________

$ISO Dates (Only Year)
____________________________________________________________________________________________________

$ISO Dates (Date-Time)
____________________________________________________________________________________________________

$Time Zones
____________________________________________________________________________________________________

$JavaScript Short Dates
____________________________________________________________________________________________________

$WARNINGS!
____________________________________________________________________________________________________

$JavaSCript Long Dates
____________________________________________________________________________________________________

$Date Input - Parsing Dates

====================================================================================================
32#JS Date Get Methods                                                                             |
====================================================================================================

$The new Date() Construstor
____________________________________________________________________________________________________

$Date Get Methods
____________________________________________________________________________________________________

$The getFullYear() Method
____________________________________________________________________________________________________

$The getMonth() Method
____________________________________________________________________________________________________

$The getDate() Method
____________________________________________________________________________________________________

$The getHours() Method
____________________________________________________________________________________________________

$The getMinutes() Method
____________________________________________________________________________________________________

$The getSeconds() Method
____________________________________________________________________________________________________

$The getMilliseconds() Method
____________________________________________________________________________________________________

$The getDay() Method
____________________________________________________________________________________________________

$The getTime() Mrthod
____________________________________________________________________________________________________

$The Date.now() Mrthod
____________________________________________________________________________________________________

$UTC Date Get Methods
____________________________________________________________________________________________________

$The getTimezoneOffset() Method

====================================================================================================
33#JS Date Set Methods                                                                             |
====================================================================================================

$Set Date Methods
____________________________________________________________________________________________________

$The setFullYear() Method
____________________________________________________________________________________________________

$The setMonth() Method
____________________________________________________________________________________________________

$The setDate() Method
____________________________________________________________________________________________________

$The setHours() Method
____________________________________________________________________________________________________

$The setMinutes() Method
____________________________________________________________________________________________________

$The setSeconds() Method
____________________________________________________________________________________________________

$Compare Dates

====================================================================================================
34#JS Math                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The Math Object
____________________________________________________________________________________________________

$Math Properties(Constants)
____________________________________________________________________________________________________

$Math Methods
____________________________________________________________________________________________________

$Number to Integer
____________________________________________________________________________________________________

$Math.round()
____________________________________________________________________________________________________

$Math.ceil()
____________________________________________________________________________________________________

$Math.floor()
____________________________________________________________________________________________________

$Math.trunc()
____________________________________________________________________________________________________

$Math.sign()
____________________________________________________________________________________________________

$Math.pow()
____________________________________________________________________________________________________

$math.abs()
____________________________________________________________________________________________________

$Math.sin()
____________________________________________________________________________________________________

$Math.cos()
____________________________________________________________________________________________________

$Math.min() and Math.max()
____________________________________________________________________________________________________

$Math.random()
____________________________________________________________________________________________________

$The Math.log() Method
____________________________________________________________________________________________________

$The Math.log2() Method
____________________________________________________________________________________________________

$The Math.log10() Mrthod
____________________________________________________________________________________________________

$JavaScript Math Methods

====================================================================================================
35#JS Random                                                                                       |`
====================================================================================================

$Math.random()
____________________________________________________________________________________________________

$JavaScript Random Integers
____________________________________________________________________________________________________

$A Proper Random Function

====================================================================================================
36#JS Booleans                                                                                     |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Boolean Values
____________________________________________________________________________________________________

$The Boolean() Function
____________________________________________________________________________________________________

$Comparisions and Conditions
____________________________________________________________________________________________________

$Everything With a "Value" is True
____________________________________________________________________________________________________

$Everything Without a "Value" is False
____________________________________________________________________________________________________

$JavaSCript Booleans as Objects

====================================================================================================
37#JS Comparisons                                                                                  |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Comparison Operators
____________________________________________________________________________________________________

$How Can it Be Used
____________________________________________________________________________________________________

$Logical Operators
____________________________________________________________________________________________________

$Conditional (Ternary) Operator
____________________________________________________________________________________________________

$Comparing Different Types
____________________________________________________________________________________________________

$The Nullish Coalescing Operator (??)
____________________________________________________________________________________________________

$The Optional Chaining Operator (?.)

====================================================================================================
38#JS If Else                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Conditional Statement
____________________________________________________________________________________________________

$The if Statement
____________________________________________________________________________________________________

$The else Statement
____________________________________________________________________________________________________

$The else if Statement
____________________________________________________________________________________________________

$More Example

====================================================================================================
39#JS Switch                                                                                       |
====================================================================================================

$The JavaScript Switch Statement
____________________________________________________________________________________________________

$The break Keyword
____________________________________________________________________________________________________

$The default Keyword
____________________________________________________________________________________________________

$Common Code Blocks
____________________________________________________________________________________________________

$Switching Details
____________________________________________________________________________________________________

$Strict Comparison

====================================================================================================
40#JS Loop For                                                                                     |
====================================================================================================

$JavaScript Loops
____________________________________________________________________________________________________

$Different Kinds of loops 
____________________________________________________________________________________________________

$The For Loop
____________________________________________________________________________________________________

$Expression 1
____________________________________________________________________________________________________

$ Expression 2
____________________________________________________________________________________________________

$Expression 3
____________________________________________________________________________________________________

$Loop Scope
____________________________________________________________________________________________________

$For/Of and For/In Loops
____________________________________________________________________________________________________

$While Loops

====================================================================================================
41#JS Loop For In                                                                                  |
====================================================================================================

$The For In Loop
____________________________________________________________________________________________________

$For In Over Arrays
____________________________________________________________________________________________________

$Array.forEach()

====================================================================================================
42#JS Loop For Of                                                                                  |
====================================================================================================

$The For Of Loop
____________________________________________________________________________________________________

$Browser Support
____________________________________________________________________________________________________

$Looping over an Array
____________________________________________________________________________________________________

$Looping over a String
____________________________________________________________________________________________________

$The While Loop

====================================================================================================
43#JS Loop While                                                                                   |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The While Loop
____________________________________________________________________________________________________

$The Do While Loop
____________________________________________________________________________________________________

$Comparing For and  While 

====================================================================================================
44#JS Break                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The Break Statement
____________________________________________________________________________________________________

$The Continue Statement
____________________________________________________________________________________________________

$JavaScript Labels

====================================================================================================
45#JS Iterables                                                                                    |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The For Of Loop
____________________________________________________________________________________________________

$Iterating
____________________________________________________________________________________________________

$Iterating Over a String
____________________________________________________________________________________________________

$Iterating Over an Array
____________________________________________________________________________________________________

$Iterating Over a Set
____________________________________________________________________________________________________

$Iterating Over a Map

====================================================================================================
46#JS Sets                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Essentail Set Methods
____________________________________________________________________________________________________

$How to Create a Set
____________________________________________________________________________________________________

$The new Set() Method
____________________________________________________________________________________________________

$The add() Method
____________________________________________________________________________________________________

$The forEach() Method
____________________________________________________________________________________________________

$The values() Method

====================================================================================================
47#JS Maps                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Essential Map Methods
____________________________________________________________________________________________________

$How to Create a Map
____________________________________________________________________________________________________

$The new Map() Method
____________________________________________________________________________________________________

$The set() Method
____________________________________________________________________________________________________

$The get() Method
____________________________________________________________________________________________________

$The size Property
____________________________________________________________________________________________________

$The delete() Method
____________________________________________________________________________________________________

$The has() Method
____________________________________________________________________________________________________

$JavaScript Objects vs Maps
____________________________________________________________________________________________________

$The forEach() Method
____________________________________________________________________________________________________

$The entries() Method
____________________________________________________________________________________________________

$Browser Support

====================================================================================================
48#JS Typeof                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The typeof Operator
____________________________________________________________________________________________________

$Primitive Data
____________________________________________________________________________________________________

$Complex Data
____________________________________________________________________________________________________

$The Data Type of typeof
____________________________________________________________________________________________________

$The constructor Property
____________________________________________________________________________________________________

$Undefined
____________________________________________________________________________________________________

$Empty Values
____________________________________________________________________________________________________

$Null
____________________________________________________________________________________________________

$Difference Betweer Undefined and Null
____________________________________________________________________________________________________

$The instance Operator
____________________________________________________________________________________________________

$The void Operator

====================================================================================================
49#JS Type Conversion                                                                              |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Type Conversion
____________________________________________________________________________________________________

$Converting Strings to Numbers
____________________________________________________________________________________________________

$Number Methods
____________________________________________________________________________________________________

$The Unary + Operator
____________________________________________________________________________________________________

$Converting Numbers to Strings
____________________________________________________________________________________________________

$More Methods
____________________________________________________________________________________________________

$Converting Dates to Numbers
____________________________________________________________________________________________________

$Converting Dates to Strings
____________________________________________________________________________________________________

$Converting Booleans to Numbers
____________________________________________________________________________________________________

$Converting Booleans to Strings
____________________________________________________________________________________________________

$Automatic type Conversion
____________________________________________________________________________________________________

$Automatic String Conversion
____________________________________________________________________________________________________

$JavaScript Type Conversion Table

====================================================================================================
50#JS Bitwise                                                                                      |
====================================================================================================

$JavaScript Bitwise Operators
____________________________________________________________________________________________________

$JavaScript Uses 32 bits Bitwise Operands
____________________________________________________________________________________________________

$JavaScript Bitwise AND
____________________________________________________________________________________________________

$JavaScript Bitwise OR
____________________________________________________________________________________________________

$JavaScript Bitwise XOR
____________________________________________________________________________________________________

$JavaScript Bitwise AND(&)
____________________________________________________________________________________________________

$JavaScript Bitwise OR(|)
____________________________________________________________________________________________________

$JavaSCript Bitwise XOR (^)
____________________________________________________________________________________________________

$JavaScript Bitwise NOT(~)
____________________________________________________________________________________________________

$JavaSCript (Zero Fill) Bitwise Left Shift (<<)
____________________________________________________________________________________________________

$JavaSCript (Sign Preserving) Bitwise Right Shift (>>)
____________________________________________________________________________________________________

$JavaScript (Zero Fill) Right Shift (>>)
____________________________________________________________________________________________________

$Binary Numbers
____________________________________________________________________________________________________

$Convertiing Decimal to Binary
____________________________________________________________________________________________________

$Converting Binary to Decimal

====================================================================================================
51#JS RegExp                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$What is Regular Expression
____________________________________________________________________________________________________

$Syntax
____________________________________________________________________________________________________

$Using String Methods
____________________________________________________________________________________________________

$Using String search() With a String
____________________________________________________________________________________________________

$Using String search () With a Regular Expression
____________________________________________________________________________________________________

$Using String replace() With a String
____________________________________________________________________________________________________

$Use String replace() With a Regular Expression
____________________________________________________________________________________________________

$Regular Expression Modifiers
____________________________________________________________________________________________________

$Regular Expression Patterns
____________________________________________________________________________________________________

$Using the RegExo Object
____________________________________________________________________________________________________

$Using test()
____________________________________________________________________________________________________

$Using exec()

====================================================================================================
52#JS Precedence                                                                                   |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Operator Precedence Values
____________________________________________________________________________________________________

$Increment Operators
____________________________________________________________________________________________________

$NOT Operators
____________________________________________________________________________________________________

$Unary Operators
____________________________________________________________________________________________________

$Arithmetic Operators
____________________________________________________________________________________________________

$Shift Operators
____________________________________________________________________________________________________

$Relational Operators
____________________________________________________________________________________________________

$Comparison Operators
____________________________________________________________________________________________________

$Bitwise operators
____________________________________________________________________________________________________

$Logical Operators
____________________________________________________________________________________________________

$Conditional (Ternary) Operator
____________________________________________________________________________________________________

$Assigment Operators

====================================================================================================
53#JS Errors                                                                                       |
====================================================================================================

$Throw, and Try...Catch...Finally
____________________________________________________________________________________________________

$Errors Will Happen!
____________________________________________________________________________________________________

$JavaScript try and catch
____________________________________________________________________________________________________

$JavaScript Throws Errors
____________________________________________________________________________________________________

$The throw Statement
____________________________________________________________________________________________________

$input Validation Example
____________________________________________________________________________________________________

$HTML Validation
____________________________________________________________________________________________________

$The finally Statement
____________________________________________________________________________________________________

$The Error Object
____________________________________________________________________________________________________

$Error Object Properties
____________________________________________________________________________________________________

$Error name Values
____________________________________________________________________________________________________

$Eval Error
____________________________________________________________________________________________________

$Range Error
____________________________________________________________________________________________________

$Reference Error
____________________________________________________________________________________________________

$Syntax Error
____________________________________________________________________________________________________

$Type Error
____________________________________________________________________________________________________

$URI (Uniform Resource Identifier) Error
____________________________________________________________________________________________________

$Non-Standard Error Object Properties

====================================================================================================
54#JS Scope                                                                                        |
====================================================================================================

$introduction
____________________________________________________________________________________________________

$Block Scope
____________________________________________________________________________________________________

$Local Scope
____________________________________________________________________________________________________

$Function Scope
____________________________________________________________________________________________________

$Global JavaScript Variables
____________________________________________________________________________________________________

$Global Scope
____________________________________________________________________________________________________

$JavaScript Variables
____________________________________________________________________________________________________

$Automatically Global
____________________________________________________________________________________________________

$Strict Mode
____________________________________________________________________________________________________

$Global Variables in HTML
____________________________________________________________________________________________________

$Waring
____________________________________________________________________________________________________

$The Lifetime of JavaScript Variables
____________________________________________________________________________________________________

$Function Arguments

====================================================================================================
55#JS Hoisting                                                                                     |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaSCript Declaration are Hoisted
____________________________________________________________________________________________________

$The let and const Keywords
____________________________________________________________________________________________________

$JavaSCript initialization are Not Hoisted
____________________________________________________________________________________________________

$Declare your Variables At the Top!

====================================================================================================
56#JS Strict Mode                                                                                  |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The "use strict" Directive
____________________________________________________________________________________________________

$Declaring Strict Mode
____________________________________________________________________________________________________

$The "use strict"; Syntax
____________________________________________________________________________________________________

$Why Strict Mode
____________________________________________________________________________________________________

$Not Allowed in Strict Mode
____________________________________________________________________________________________________

$Future Proof!

====================================================================================================
57#JS this Keyword                                                                                 |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$What is "this"
____________________________________________________________________________________________________

$"this" in a Method
____________________________________________________________________________________________________

$"this" Alone
____________________________________________________________________________________________________

$"this" in a Function (Default)
____________________________________________________________________________________________________

$"this" in a Function (Strict)
____________________________________________________________________________________________________

$"this" in Event Handlers
____________________________________________________________________________________________________

$Object Method Binding
____________________________________________________________________________________________________

$Explicit Function Binding
____________________________________________________________________________________________________

$Function Borrowing
____________________________________________________________________________________________________

$"This" Precedence

====================================================================================================
58#JS Arrow Function                                                                               |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$What About "this" ?
____________________________________________________________________________________________________

$Browser Support

====================================================================================================
59#JS Classes                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Class Syntax
____________________________________________________________________________________________________

$Using a Class
____________________________________________________________________________________________________

$The Constructor Method
____________________________________________________________________________________________________

$Class methods
____________________________________________________________________________________________________

$Browser Support

====================================================================================================
60#JS Modules                                                                                      |
====================================================================================================

$Modules
____________________________________________________________________________________________________

$Export
____________________________________________________________________________________________________

$Named Exports
____________________________________________________________________________________________________

$Default Exports
____________________________________________________________________________________________________

$Import

====================================================================================================
61#JS JSON                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$What is JSON
____________________________________________________________________________________________________

$JSON Example
____________________________________________________________________________________________________

$The JSON Format Evaluates to JavaScript Objects
____________________________________________________________________________________________________

$JSON Syntax Rules
____________________________________________________________________________________________________

$JSON Data - A Name and A Value
____________________________________________________________________________________________________

$JSON Objects
____________________________________________________________________________________________________

$JSON Arrays
____________________________________________________________________________________________________

$Converting a JSON Text to a JavaScript Object

====================================================================================================
62#JS Debugging                                                                                    |
====================================================================================================

$Code Debugging
____________________________________________________________________________________________________

$JavaScript Debuggers
____________________________________________________________________________________________________

$The console.log() Method
____________________________________________________________________________________________________

$Setting Breakpoints
____________________________________________________________________________________________________

$The debugger Keyword
____________________________________________________________________________________________________

$Mojor Browser's Debugging Tools

====================================================================================================
63#JS Style Guide                                                                                  |
====================================================================================================

$JavaScript Coding Conventions
____________________________________________________________________________________________________

$Variable names
____________________________________________________________________________________________________

$Space Around Operators
____________________________________________________________________________________________________

$Code Indentation
____________________________________________________________________________________________________

$Statement Rules
____________________________________________________________________________________________________

$Object Rules
____________________________________________________________________________________________________

$Line Length < 80
____________________________________________________________________________________________________

$Name Conventions
____________________________________________________________________________________________________

$Loading JavaScript in HTML
____________________________________________________________________________________________________

$Accessing HTML Elements
____________________________________________________________________________________________________

$File Extensions
____________________________________________________________________________________________________

$Use Lower Case File Names
____________________________________________________________________________________________________

$Performance

====================================================================================================
64#JS Best Practices                                                                               |
====================================================================================================

$Avoid Global Variables
____________________________________________________________________________________________________

$Always Declare Local Variables
____________________________________________________________________________________________________

$Declaration on Top
____________________________________________________________________________________________________

$Initialize Variables
____________________________________________________________________________________________________

$Declare Objects with const
____________________________________________________________________________________________________

$Declare arrays with const
____________________________________________________________________________________________________

$Don't Use new Object()
____________________________________________________________________________________________________

$Beware of Automatic Type Conversions
____________________________________________________________________________________________________

$Use === Comparision
____________________________________________________________________________________________________

$Use Parameter Defaults
____________________________________________________________________________________________________

$End Your Switches with Defaults
____________________________________________________________________________________________________

$Avoid Number, String and Boolean as Objects
____________________________________________________________________________________________________

$Avoid Using eval()

====================================================================================================
65#JS Mistakes                                                                                     |
====================================================================================================

$Accidently Using the Assignment Operator
____________________________________________________________________________________________________

$Expecting Loose Comparison
____________________________________________________________________________________________________

$Confusing Addition $ Concatenation
____________________________________________________________________________________________________

$Misunderstanding Floats
____________________________________________________________________________________________________

$Breaking a JavaScript String
____________________________________________________________________________________________________

$Misplacing Semicolon
____________________________________________________________________________________________________

$Breaking a Return Statement
____________________________________________________________________________________________________

$Explanation
____________________________________________________________________________________________________

$Accessing Array with Named Indexes
____________________________________________________________________________________________________

$Ending Definations with a Comma
____________________________________________________________________________________________________

$Undefined is Not Null

====================================================================================================
66#JS Performance                                                                                  |
====================================================================================================

$Reduce Activity in Loops
____________________________________________________________________________________________________

$Reduce DOM Access
____________________________________________________________________________________________________

$Reduce DOM Size
____________________________________________________________________________________________________

$Avoid Unnecessary Variables
____________________________________________________________________________________________________

$Delay JavaScript Loading
____________________________________________________________________________________________________

$Avoid Using with 

====================================================================================================
67#JS Reserved Words                                                                               |
====================================================================================================

$ Reserved Words
____________________________________________________________________________________________________

$Removed Reserved Words
____________________________________________________________________________________________________

$JavaScript Objects, Properties and Methods
____________________________________________________________________________________________________

$Java Reserved Words
____________________________________________________________________________________________________

$Other Reserved Words
____________________________________________________________________________________________________

$HTML Event Handlers





/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS OBJECTS|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

===================================================================================================
Object Definitions                                                                                |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Primitives
____________________________________________________________________________________________________

$Objects are Variables
____________________________________________________________________________________________________

$Object Properties
____________________________________________________________________________________________________

$Object Methods
____________________________________________________________________________________________________

$Creating a javaScript Object
____________________________________________________________________________________________________

$Using an Object Literal
____________________________________________________________________________________________________

$Using the JavaScript Keyword new
____________________________________________________________________________________________________

$JavaScript Object are Mutable

===================================================================================================
Object Properties                                                                                 |
===================================================================================================

$JavaScript Properties
____________________________________________________________________________________________________

$Accessing JavaScript Properties
____________________________________________________________________________________________________

$JavaScript for..in Loop
____________________________________________________________________________________________________

$Adding New Properties
____________________________________________________________________________________________________

$Deleting Properties
____________________________________________________________________________________________________

$Nested Objects
____________________________________________________________________________________________________

$Nested Arrays and Objects
____________________________________________________________________________________________________

$Property Attributes
____________________________________________________________________________________________________

$Prototype Properties

===================================================================================================
Object Methods                                                                                    |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$What is "this"?
____________________________________________________________________________________________________

$JavaScript Methods
____________________________________________________________________________________________________

$Accessing Object Methods
____________________________________________________________________________________________________

$Adding a Method to an Object
____________________________________________________________________________________________________

$Using Built-in Methods

===================================================================================================
Object Display                                                                                    |
===================================================================================================

$How to Display JavaScript Objects
____________________________________________________________________________________________________

$Display Object Properties
____________________________________________________________________________________________________

$Display the Object is a Loop
____________________________________________________________________________________________________

$Using Object.values()
____________________________________________________________________________________________________

$Using JSON.stringify()
____________________________________________________________________________________________________

$Stringify Dates
____________________________________________________________________________________________________

$Stingify Functions
____________________________________________________________________________________________________

$Stringify Arrays

===================================================================================================
Object Accessors                                                                                  |
===================================================================================================

$JavaScript Accessors(Getters and Setters)
____________________________________________________________________________________________________

$JavaScript Getter(The get Keyword)
____________________________________________________________________________________________________

$JavaScript Setter(The set Keyword)
____________________________________________________________________________________________________

$JavaScript Function or Getter?
____________________________________________________________________________________________________

$Data Quality
____________________________________________________________________________________________________

$Why Using Getters and Setters
____________________________________________________________________________________________________

$Object.defineProperty()

===================================================================================================
Object Constructors                                                                               |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$Object Types(Blueprints)(Classes)
____________________________________________________________________________________________________

$What is "this"?
____________________________________________________________________________________________________

$Adding a property to an Object
____________________________________________________________________________________________________

$Adding a Method to an Object
____________________________________________________________________________________________________

$Adding a Property to a Constructor
____________________________________________________________________________________________________

$Adding a Method to a Constructor
____________________________________________________________________________________________________

$Built-in JavaScript Constructors
____________________________________________________________________________________________________

$String Objects
____________________________________________________________________________________________________

$Number Objects
____________________________________________________________________________________________________

$Boolean Objects

===================================================================================================
Object Prototypes                                                                                 |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$Protptype Inheritance
____________________________________________________________________________________________________

$Adding Properties and Methods to Objects
____________________________________________________________________________________________________

$Using the prototype Property

===================================================================================================
Object Iterables                                                                                  |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$Iterating Over a String
____________________________________________________________________________________________________

$Iterating Over an Array
____________________________________________________________________________________________________

$JavaScript Iterators
____________________________________________________________________________________________________

$Home Made Iterable

===================================================================================================
Object Sets                                                                                       |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$Set Methods
____________________________________________________________________________________________________

$How to Create a Set
____________________________________________________________________________________________________

$The new Set() Method
____________________________________________________________________________________________________

$The add() Method
____________________________________________________________________________________________________

$The forEach() Method
____________________________________________________________________________________________________

$The values() Method
____________________________________________________________________________________________________

$The keys() Method
____________________________________________________________________________________________________

$The entries() Method
____________________________________________________________________________________________________

$Sets are Objects

===================================================================================================
Object Maps                                                                                       |
===================================================================================================

$Introduction
____________________________________________________________________________________________________

$Map Methods
____________________________________________________________________________________________________

$How to Create a Map
____________________________________________________________________________________________________

$new Map()
____________________________________________________________________________________________________

$Map.set()
____________________________________________________________________________________________________

$Map.get()
____________________________________________________________________________________________________

$Map.size
____________________________________________________________________________________________________

$Map.delete()
____________________________________________________________________________________________________

$Map.clear()
____________________________________________________________________________________________________

$Map.has()
____________________________________________________________________________________________________

$Maps are Objects
____________________________________________________________________________________________________

$JavaScript Objects vs Maps
____________________________________________________________________________________________________

$Map.forEach()
____________________________________________________________________________________________________

$Map.entries()
____________________________________________________________________________________________________

$Map.keys()
____________________________________________________________________________________________________

$Map.values()
____________________________________________________________________________________________________

$Objects as Keys

===================================================================================================
Object Reference                                                                                  |
===================================================================================================

$Managing Objects
____________________________________________________________________________________________________

$Protecting Objects
____________________________________________________________________________________________________

$Changing a Property Value
____________________________________________________________________________________________________

$Changing Meta Data
____________________________________________________________________________________________________

$Listing All Properties
____________________________________________________________________________________________________

$Listing Enmerable Properties
____________________________________________________________________________________________________

$Adding a Property
____________________________________________________________________________________________________

$Adding Getters and Setters
____________________________________________________________________________________________________

$A Counter Example





/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS FUNCTIONS||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
Function Definitions                                                                               |
====================================================================================================

$INTRODUCTION

____________________________________________________________________________________________________

$FUNCTION DECLARATIONS

____________________________________________________________________________________________________

$FUNCTION EXPRESSIONS

____________________________________________________________________________________________________

$FUNCTION() CONSTRUCTOR

____________________________________________________________________________________________________

$FUNCTION HOISTING

____________________________________________________________________________________________________

$SELF-INVOKING FUNCTIONS

____________________________________________________________________________________________________

$FUNCTIONS CAN BE USED AS VALUES

____________________________________________________________________________________________________

$FUNCTIONS ARE OBJECTS

____________________________________________________________________________________________________

$ARROW FUNCTIONS

====================================================================================================
Function Parameters                                                                                |
====================================================================================================

$INTRODUCTION

____________________________________________________________________________________________________

$FUNCTION PARAMETERS AND ARGUMENTS

____________________________________________________________________________________________________

$PARAMETER RULES

____________________________________________________________________________________________________

$DEFAULT PARAMETERS

____________________________________________________________________________________________________

$DEFAULT PARAMETR VALUES

____________________________________________________________________________________________________

$FUNCTION REST PARAMETER

____________________________________________________________________________________________________

$THE ARGUMENTS OBJECT

____________________________________________________________________________________________________

$ARGUMENTS ARE PASED BY VALUE

____________________________________________________________________________________________________

$OBJECTS ARE PASSED BY REFERENCE

====================================================================================================
Function Invocation                                                                                |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Invoking a javaScript Function
____________________________________________________________________________________________________

$Invoking a Function as a Function
____________________________________________________________________________________________________

$What is "this"?
____________________________________________________________________________________________________

$The Global Object
____________________________________________________________________________________________________

$Invoking a Function as a Method
____________________________________________________________________________________________________

$Invoking a Function with a Function Constructor

====================================================================================================
Function Call                                                                                      |
====================================================================================================

$Method Resue
____________________________________________________________________________________________________

$All Function are Methods
____________________________________________________________________________________________________

$What is "this"?
____________________________________________________________________________________________________

$The JavaScript call() Method
____________________________________________________________________________________________________

$The call() Method with Arguments

====================================================================================================
Function Apply                                                                                     |
====================================================================================================

$Method Resue
____________________________________________________________________________________________________

$The JavaScript apply() Method
____________________________________________________________________________________________________

$The Difference Between call() and apply()
____________________________________________________________________________________________________

$The apply() Method with Arguments
____________________________________________________________________________________________________

$Simulate a Max Method on Arrays
____________________________________________________________________________________________________

$JavaScript Strict Mode

====================================================================================================
Function Blind                                                                                     |
====================================================================================================

$Function Borrowing
____________________________________________________________________________________________________

$Preserving "this"
____________________________________________________________________________________________________

$What is "this"?

====================================================================================================
Function Closures                                                                                  |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Global Variables
____________________________________________________________________________________________________

$Variable Lifetime
____________________________________________________________________________________________________

$A Counter Dilemma
____________________________________________________________________________________________________

$JavaSCript Nested Functions
____________________________________________________________________________________________________

$JavaScript Closures
____________________________________________________________________________________________________

$Example Explained



/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS CLASSES||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
Class Intro                                                                                        |
====================================================================================================

$INTRODUCTION

____________________________________________________________________________________________________

$JAVASCRIPT CLASS SYNTAX

____________________________________________________________________________________________________

$USING A CLASS

____________________________________________________________________________________________________

$THE CONSTRUCTOR METHOD

____________________________________________________________________________________________________

$CLASS METHODS

____________________________________________________________________________________________________

$BETTER SUPPORT

____________________________________________________________________________________________________

$USE STRICT

====================================================================================================
Class Inhertitane                                                                                  |
====================================================================================================

$Class Inheritance
____________________________________________________________________________________________________

$Getters and Setters
____________________________________________________________________________________________________

$Hoisting

====================================================================================================
Class Static                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Methods




/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS ASYNC||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
JS Callbacks                                                                                       |
====================================================================================================

$Function Sequence
____________________________________________________________________________________________________

$Sequence Control
____________________________________________________________________________________________________

$JavaScript Callbacks
____________________________________________________________________________________________________

$When to Use a Callback

====================================================================================================
JS Asynchronous                                                                                    |
====================================================================================================

$Asynchronous JavaScript
____________________________________________________________________________________________________

$Waiting for a Timeout
____________________________________________________________________________________________________

$Waiting for intervals
____________________________________________________________________________________________________

$Callback Alternatives

====================================================================================================
JS Promises                                                                                        |
====================================================================================================

$JavaSCript Promise Object
____________________________________________________________________________________________________

$Promise Object Properties
____________________________________________________________________________________________________

$Promise How To
____________________________________________________________________________________________________

$JavaScript Promise Examples
____________________________________________________________________________________________________

$Writing for a Timeout
____________________________________________________________________________________________________

$Waiting for a file

====================================================================================================
JS Async/Await                                                                                     |
====================================================================================================

$Async Syntax
____________________________________________________________________________________________________

$Await Syntax



/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS HTML DOM|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
DOM Intro                                                                                          |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The HTML DOM (Document Object Model)
____________________________________________________________________________________________________

$What You Will Learn
____________________________________________________________________________________________________

$What is the DOM?
____________________________________________________________________________________________________

$What is the HTML DOM?

====================================================================================================
DOM Methods                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The DOM Programming Interface
____________________________________________________________________________________________________

$The getElementById Method
____________________________________________________________________________________________________

$The innerHTML Property

====================================================================================================
DOM Document                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The HTML DOM Document Object
____________________________________________________________________________________________________

$Finding HTML ELements
____________________________________________________________________________________________________

$Changing HTMl Elements
____________________________________________________________________________________________________

$Adding and Deleting Elements
____________________________________________________________________________________________________

$Adding Events Handlers
____________________________________________________________________________________________________

$Finding HTML Objects

====================================================================================================
DOM Elements                                                                                       |
====================================================================================================

$Finding HTML Elements
____________________________________________________________________________________________________

$Finding HTML Element by Id
____________________________________________________________________________________________________

$Finding HTML Elements by Tag Name
____________________________________________________________________________________________________

$Finding HTML Elements by Class Name
____________________________________________________________________________________________________

$Finding HTML Elements by CSS Selectors
____________________________________________________________________________________________________

$Finding HTML Elements by HTML Object Collections

====================================================================================================
DOM HTML                                                                                           |
====================================================================================================

$Changing HTML Content
____________________________________________________________________________________________________

$Changing the Vaue of an Attribute
____________________________________________________________________________________________________

$Dynamic HTML Content
____________________________________________________________________________________________________

$Document.write()

====================================================================================================
DOM Forms                                                                                          |
====================================================================================================

$JavaScript Form Validation
____________________________________________________________________________________________________

$JavaScript Can Validate Numeric Input
____________________________________________________________________________________________________

$Automatic HTML Form Validation
____________________________________________________________________________________________________

$Data Validation
____________________________________________________________________________________________________

$HTML Constraint Validation
____________________________________________________________________________________________________

$Constraint Validation HTML Input Attributes
____________________________________________________________________________________________________

$Constraint Validation CSS Pseudo Selectors

====================================================================================================
DOM CSS                                                                                            |
====================================================================================================

$Changing HTML Style
____________________________________________________________________________________________________

$Using Events
____________________________________________________________________________________________________

$HTML DOM Style Object Reference

====================================================================================================
DOM Animations                                                                                     |
====================================================================================================

$A Basic Web Page
____________________________________________________________________________________________________

$Create Animation Container
____________________________________________________________________________________________________

$Style the Elements
____________________________________________________________________________________________________

$Animation Code
____________________________________________________________________________________________________

$Create the Full Animation Using JavaScript

====================================================================================================
DOM Events                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Reacting to Events
____________________________________________________________________________________________________

$HTML Event Attributes
____________________________________________________________________________________________________

$Assign Events Using the HTML DOM
____________________________________________________________________________________________________

$The onload and onunload Events
____________________________________________________________________________________________________

$The onchange Events
____________________________________________________________________________________________________

$The onmouseover and onmouseout Events
____________________________________________________________________________________________________

$The onmousedown, onmouseup and onclick Events
____________________________________________________________________________________________________

$More Examples
____________________________________________________________________________________________________

$HTML DOM Event Object Reference

====================================================================================================
DOM Event Listener                                                                                 |
====================================================================================================

$The addEventListener() method
____________________________________________________________________________________________________

$Syntax
____________________________________________________________________________________________________

$Add an Event Handler to an Element
____________________________________________________________________________________________________

$Add Many Event Handlers to the Same Element
____________________________________________________________________________________________________

$Add an Event Handler to the window Object
____________________________________________________________________________________________________

$Passing Parameters
____________________________________________________________________________________________________

$Event Bubbling or Event Capturing?
____________________________________________________________________________________________________

$The removeEventListner() method
____________________________________________________________________________________________________

$HTML DOM Event Object Reference

====================================================================================================
DOM Navigation                                                                                     |
====================================================================================================

$DOM Nodes
____________________________________________________________________________________________________

$Node Relationships
____________________________________________________________________________________________________

$Navigating Between Nodes
____________________________________________________________________________________________________

$Child Nodes and Node Values
____________________________________________________________________________________________________

$InnerHTML
____________________________________________________________________________________________________

$DOM Root Nodes
____________________________________________________________________________________________________

$The nodeName Property
____________________________________________________________________________________________________

$The nadeValue Property
____________________________________________________________________________________________________

$The nodeType Property

====================================================================================================
DOM Nodes                                                                                          |
====================================================================================================

$Creating New HTML Elements (Nodes)
____________________________________________________________________________________________________

$Creating new HTML Elements - insertBefore()
____________________________________________________________________________________________________

$Removing Existing HTMl Elements
____________________________________________________________________________________________________

$Removing a Child Node 
____________________________________________________________________________________________________

$Replacing HTMl Elements

====================================================================================================
DOM Collections                                                                                    |
====================================================================================================

$THE HTMLCollection Object
____________________________________________________________________________________________________

$HTML HTMLCollection Length

====================================================================================================
DOM Node Lists                                                                                     |
====================================================================================================

$The HTML DOM NodeList Object
____________________________________________________________________________________________________

$HTML DOM Node List Length
____________________________________________________________________________________________________

$The Difference Between an HTMLCollection and a NodeList
____________________________________________________________________________________________________

$Not an Array!




/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS Browser BOM||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
JS Window                                                                                          |
====================================================================================================

$The Browser Object Model (BOM)
____________________________________________________________________________________________________

$The Window Object
____________________________________________________________________________________________________

$Window Size
____________________________________________________________________________________________________

$Other Window method

====================================================================================================
JS Screen                                                                                          |
====================================================================================================

$Window Screen
____________________________________________________________________________________________________

$Window Screen Width
____________________________________________________________________________________________________

$Window Screen Height
____________________________________________________________________________________________________

$Window Screen Available Width
____________________________________________________________________________________________________

$Window Screen Available Height
____________________________________________________________________________________________________

$Window Screen Color Depth
____________________________________________________________________________________________________

$Window Screen Pixel Depth

====================================================================================================
JS Location                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Window Location
____________________________________________________________________________________________________

$Window Location Href
____________________________________________________________________________________________________

$Window Location Hostname
____________________________________________________________________________________________________

$Window Location Pathname
____________________________________________________________________________________________________

$Window Location Protocol
____________________________________________________________________________________________________

$Window Location Port
____________________________________________________________________________________________________

$Window Location Assign

====================================================================================================
JS History                                                                                         |
====================================================================================================

$Window History
____________________________________________________________________________________________________

$Window History Back
____________________________________________________________________________________________________

$Window History Forward

====================================================================================================
JS Navigator                                                                                       |
====================================================================================================

$Window Navigator
____________________________________________________________________________________________________

$Browser Cookies
____________________________________________________________________________________________________

$Browser Application Name 
____________________________________________________________________________________________________

$Browser Application Code Name
____________________________________________________________________________________________________

$The Browser Engine
____________________________________________________________________________________________________

$The Browser Version
____________________________________________________________________________________________________

$The Browser Agent
____________________________________________________________________________________________________

$The Browser Platform
____________________________________________________________________________________________________

$The Browser Language
____________________________________________________________________________________________________

$Is The Browser Online?
____________________________________________________________________________________________________

$Is Java Enabled?

====================================================================================================
JS Popup Alert                                                                                     |
====================================================================================================

$Alert Box
____________________________________________________________________________________________________

$Confirm Box
____________________________________________________________________________________________________

$Prompt Box
____________________________________________________________________________________________________

$Line Breaks

====================================================================================================
JS Timing                                                                                          |
====================================================================================================

$Timing Events
____________________________________________________________________________________________________

$The setTimeout() Method
____________________________________________________________________________________________________

$How to Stop the Execution?
____________________________________________________________________________________________________

$The setInterval() Method
____________________________________________________________________________________________________

$How to Stop the Execution?

====================================================================================================
JS Cookies                                                                                         |
====================================================================================================

$What are Cookies?
____________________________________________________________________________________________________

$Create a Cookie with JavaScript
____________________________________________________________________________________________________

$Read a Cookie with JavaScript
____________________________________________________________________________________________________

$Change a Cookie with JavaSript
____________________________________________________________________________________________________

$Delete a Cookie with JavaSript
____________________________________________________________________________________________________

$The Cookie String
____________________________________________________________________________________________________

$JavaScript Cookie Example
____________________________________________________________________________________________________

$A Function to Set a Cookie
____________________________________________________________________________________________________

$A Function to Get a Cookie
____________________________________________________________________________________________________

$A Functiuon to Check a Cookie
____________________________________________________________________________________________________

$All Together Now 





/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS WEB API||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
Web API Intro                                                                                      |
====================================================================================================

$What is Web API?
____________________________________________________________________________________________________

$Browser APIs
____________________________________________________________________________________________________

$Third Party APIs

====================================================================================================
Web Forms API                                                                                      |
====================================================================================================

$Constraint Validation DOM Methods
____________________________________________________________________________________________________

$Constraint Validation DOM Properties
____________________________________________________________________________________________________

$Validity Properties

====================================================================================================
Web History API                                                                                    |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The History back() Method
____________________________________________________________________________________________________

$The History go() Method
____________________________________________________________________________________________________

$History Object Properties
____________________________________________________________________________________________________

$History Object Methods

====================================================================================================
Web Storage API                                                                                    |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The localStorage Object
____________________________________________________________________________________________________

$The setIteam() Method
____________________________________________________________________________________________________

$The getItem() Method
____________________________________________________________________________________________________

$The sessionStroage Object
____________________________________________________________________________________________________

$The setItem() Method
____________________________________________________________________________________________________

$The getIteam() Method
____________________________________________________________________________________________________

$Storage Object Properties and Methods
____________________________________________________________________________________________________

$Related Pages for Web Storage API

====================================================================================================
Web Worker API                                                                                     |
====================================================================================================

$What is a Web Worker?
____________________________________________________________________________________________________

$Web Worker Example
____________________________________________________________________________________________________

$Check Web Worker Support
____________________________________________________________________________________________________

$Create a Web Worker File
____________________________________________________________________________________________________

$Create a Web Worker Object
____________________________________________________________________________________________________

$Terminate a Web Worker
____________________________________________________________________________________________________

$Reuse the Web Worker
____________________________________________________________________________________________________

$Full Web Worker Example Code
____________________________________________________________________________________________________

$Web Workers and the DOM

====================================================================================================
Web Fetch API                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$A Fetch API Example

====================================================================================================
Web Geolocation API                                                                                |
====================================================================================================

$Locate the User's Position
____________________________________________________________________________________________________

$Using the Geolocation API
____________________________________________________________________________________________________

$Handling Errors and Rejections
____________________________________________________________________________________________________

$Displaying the Result in a Map
____________________________________________________________________________________________________

$Location-specific Information
____________________________________________________________________________________________________

$The getCurrentPosition() Method - Return Data
____________________________________________________________________________________________________

$Geolocation Object - Other Intresting methods



/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS AJAX|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
AJAX Intro                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$AJAX Example Explained
____________________________________________________________________________________________________

$What is AJAX?
____________________________________________________________________________________________________

$How AJAX Works?
____________________________________________________________________________________________________

$Modern Browsers (Fetch API)

====================================================================================================
AJAX XMLHttp                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The XMLHttpRequest Object
____________________________________________________________________________________________________

$Create an XMLHttpRequest Object
____________________________________________________________________________________________________

$Define a Callback Function
____________________________________________________________________________________________________

$Send a Request
____________________________________________________________________________________________________

$Access Across Domains
____________________________________________________________________________________________________

$XMLHttpRequest Object Methods
____________________________________________________________________________________________________

$XMLHttpRequest Object Properties
____________________________________________________________________________________________________

$The onload Property
____________________________________________________________________________________________________

$Multiple Callback Functions
____________________________________________________________________________________________________

$The onreadystatechange Property

====================================================================================================
AJAX Request                                                                                       |
====================================================================================================

$Send a Request To a Server
____________________________________________________________________________________________________

$The url - A File On a Server
____________________________________________________________________________________________________

$Asynchronous - True or False?
____________________________________________________________________________________________________

$GET or POST
____________________________________________________________________________________________________

$GET Requests
____________________________________________________________________________________________________

$POST Request
____________________________________________________________________________________________________

$Synchronous Request

====================================================================================================
AJAX Response                                                                                      |
====================================================================================================

$Server Response Properties
____________________________________________________________________________________________________

$The responseText Property
____________________________________________________________________________________________________

$The responseXML Property
____________________________________________________________________________________________________

$Server Response Methods
____________________________________________________________________________________________________

$The getAllResponseHeaders() Method
____________________________________________________________________________________________________

$The getResponseHeader() Method

====================================================================================================
AJAX XML File                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$AJAX XML Example
____________________________________________________________________________________________________

$Example Explained
____________________________________________________________________________________________________

$The XML File

====================================================================================================
AJAX PHP                                                                                           |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$AJAX PHP Example
____________________________________________________________________________________________________

$Example Explained
____________________________________________________________________________________________________

$A PHP File - "gethint.php"

====================================================================================================
AJAX ASP                                                                                           |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$AJAX ASP Example
____________________________________________________________________________________________________

$Example Explained
____________________________________________________________________________________________________

$The ASP File - "gethint.asp"

====================================================================================================
AJAX Database                                                                                      |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$AJAX Database Example
____________________________________________________________________________________________________

$Example Explained - The showCustomer() Function
____________________________________________________________________________________________________

$The AJAX Server Page

====================================================================================================
AJAX Applications                                                                                  |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$The XML Document Used
____________________________________________________________________________________________________

$Display XML Data in an HTML Table
____________________________________________________________________________________________________

$Display the First CD in an HTML div Element
____________________________________________________________________________________________________

$Navigate Between the CDs
____________________________________________________________________________________________________

$Show Album Information When Clicking On a CD

====================================================================================================
AJAX Examples                                                                                      |
====================================================================================================

$Simple Examples
____________________________________________________________________________________________________

$Request Header Information
____________________________________________________________________________________________________

$Request XML Files
____________________________________________________________________________________________________

$Retrive Server Data with PHP and ASP
____________________________________________________________________________________________________

$Retrieve Database Information
____________________________________________________________________________________________________

$AJAX Applications





/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS JSON|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
JSON Intro                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JSON Example
____________________________________________________________________________________________________

$What is JSON?
____________________________________________________________________________________________________

$Why Use JSON?
____________________________________________________________________________________________________

$Storing Data

====================================================================================================
JSON Syntax                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JSON Syntax Rules
____________________________________________________________________________________________________

$JSON Data - A Name and a Value
____________________________________________________________________________________________________

$JSON - Evalutes to JavaScript Objects
____________________________________________________________________________________________________

$JSON Values
____________________________________________________________________________________________________

$JavaScript Objects
____________________________________________________________________________________________________

$JavaScript Arrays as JSON
____________________________________________________________________________________________________

$JSON FIles

====================================================================================================
JSON vs XML                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JSON is Like XML Because
____________________________________________________________________________________________________

$JSON is Unlike XML Because
____________________________________________________________________________________________________

$Why JSON is Better Than XML

====================================================================================================
JSON Data Types                                                                                    |
====================================================================================================

$Valid Data Types
____________________________________________________________________________________________________

$JSON Strings
____________________________________________________________________________________________________

$JSON Numbers
____________________________________________________________________________________________________

$JSON Objects
____________________________________________________________________________________________________

$JSON Arrays
____________________________________________________________________________________________________

$JSON Booleans
____________________________________________________________________________________________________

$JSON null

====================================================================================================
JSON Parse                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Example - Parsing JSON
____________________________________________________________________________________________________

$Array as JSON
____________________________________________________________________________________________________

$Exceptions

====================================================================================================
JSON Stringify                                                                                     |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Stringify a javaScript Object
____________________________________________________________________________________________________

$Stringify a JavaSCript Array
____________________________________________________________________________________________________

$Storing Data
____________________________________________________________________________________________________

$Exceptions

====================================================================================================
JSON Objects                                                                                       |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Objects
____________________________________________________________________________________________________

$Accessing Object Values
____________________________________________________________________________________________________

$Looping an Object

====================================================================================================
JSON Arrays                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JavaScript Arrays
____________________________________________________________________________________________________

$Accessing Array Values
____________________________________________________________________________________________________

$Arrays in Objects
____________________________________________________________________________________________________

$Looping Through an Array

====================================================================================================
JSON Server                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Sending Data
____________________________________________________________________________________________________

$Reciving Data
____________________________________________________________________________________________________

$JSON Form a Server
____________________________________________________________________________________________________

$Array as JSON

====================================================================================================
JSON PHP                                                                                           |
====================================================================================================

$Introduction 
____________________________________________________________________________________________________

$The PHP File
____________________________________________________________________________________________________

$The Client JavaScript 
____________________________________________________________________________________________________

$PHP Array 
____________________________________________________________________________________________________

$The Client JavaScript 
____________________________________________________________________________________________________

$PHP Database
____________________________________________________________________________________________________

$Use the Data
____________________________________________________________________________________________________

$PHP Method = POST

====================================================================================================
JSON HTML                                                                                          |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$HTML Table 
____________________________________________________________________________________________________

$Dynamic HTML Table
____________________________________________________________________________________________________

$HTML Drop Down List

====================================================================================================
JSON JSONP                                                                                         |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$JSONP Intro
____________________________________________________________________________________________________

$The Server File
____________________________________________________________________________________________________

$The JavaScript function
____________________________________________________________________________________________________

$Creating a Dynamic Script Tag
____________________________________________________________________________________________________

$Dunamic JSONP Result 
____________________________________________________________________________________________________

$Callback Function





/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS JQUERY|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
jQuery Selectors                                                                                   |
====================================================================================================

$JQuery vs JavaScript
____________________________________________________________________________________________________

$Finding HTML Element by Id
____________________________________________________________________________________________________

$Finding HTML Elements by Tag Name
____________________________________________________________________________________________________

$Finding HTML Elements by Class Name
____________________________________________________________________________________________________

$Finding HTMl Elements by CSS Selectors

====================================================================================================
jQuery HTML                                                                                        |
====================================================================================================

$JQuery vs JavaScript 
____________________________________________________________________________________________________

$Set Text Content
____________________________________________________________________________________________________

$Get Text Context
____________________________________________________________________________________________________

$Set HTML Content
____________________________________________________________________________________________________

$Get HTML Content

====================================================================================================
jQuery CSS                                                                                         |
====================================================================================================

$JQuery vs JavaSCript
____________________________________________________________________________________________________

$Hiding HTML Elements
____________________________________________________________________________________________________

$Showing HTML Elements
____________________________________________________________________________________________________

$Styling HTML Elements

====================================================================================================
jQuery DOM                                                                                         |
====================================================================================================

$JQuery vs JavaScript
____________________________________________________________________________________________________

$Removing HTML ELements
____________________________________________________________________________________________________

$Get Parent Element



/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/
/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\//\/\/\//\/\/\/





++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
JS GRAPHICS|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

====================================================================================================
JS Graphics                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Plotly.js
____________________________________________________________________________________________________

$Chart.js
____________________________________________________________________________________________________

$Google Chart

====================================================================================================
JS Canvas                                                                                          |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Scatter Plots
____________________________________________________________________________________________________

$Line Graphs
____________________________________________________________________________________________________

$Combined

====================================================================================================
JS Plotly                                                                                          |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$Bar Charts
____________________________________________________________________________________________________

$Horizontal Bar Charts
____________________________________________________________________________________________________

$Pie Charts
____________________________________________________________________________________________________

$Donut Charts
____________________________________________________________________________________________________

$Plotting Equations
____________________________________________________________________________________________________

$Scatter Plots
____________________________________________________________________________________________________

$Line Graphs
____________________________________________________________________________________________________

$Bubble Plots
____________________________________________________________________________________________________

$Liner Graphs
____________________________________________________________________________________________________

$Multiple Lines

====================================================================================================
JS Chart.js                                                                                        |
====================================================================================================

$Introduction
____________________________________________________________________________________________________

$How to use Chart.js?
____________________________________________________________________________________________________

$Bar Charts
____________________________________________________________________________________________________

$Doughnut Charts
____________________________________________________________________________________________________

$Scatter Plots
____________________________________________________________________________________________________

$Line Graphs
____________________________________________________________________________________________________

$Multiple Lines
____________________________________________________________________________________________________

$Linear Graphs
____________________________________________________________________________________________________

$Function Graphs

=====================================================================================================
JS Google Chart                                                                                     |
=====================================================================================================

$Introduction
____________________________________________________________________________________________________

$How to use Google Chart?
____________________________________________________________________________________________________

$Bar Charts
____________________________________________________________________________________________________

$Pie Charts
____________________________________________________________________________________________________

$3D Pie
____________________________________________________________________________________________________

$Line Graph
____________________________________________________________________________________________________

$Scatter Plots

=====================================================================================================
JS D3.js                                                                                            |
=====================================================================================================

$Introduction
____________________________________________________________________________________________________

$How to Use D3.js?
____________________________________________________________________________________________________

$Scatter Plot
