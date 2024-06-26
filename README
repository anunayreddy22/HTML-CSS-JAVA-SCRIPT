#HTML-CSS-JAVA-SCRIPT


java script resource --> https://javascript.info/


HTML is not Case Sensitive.

<!DOCTYPE html> -->  Declaration defines that this document is an HTML5 document
<html>   --> Tag open   this is the root element of an HTML page
<head>   ->  contains meta information about the HTML page
<title>Page Title</title>    --> specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
</head>
<body>     ->  a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

<h1>This is a Heading</h1>  ->  <h1> defines the most important heading. <h6> defines the least important heading: 
<p>This is a paragraph.</p> -> Words inside These Tage will be in normal words.

</body>  The visible part of the HTML document is between <body> and </body>
</html>  -> closing tag


HTML LINKS

HTML links are defined with the <a> tag

<a href="https://www.abcd.com">This is a link</a>  


HTML IMAGES

HTML images are defined with the <img> tag. The source file (src), alternative text (alt), width, and height are provided as attributes:

<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">


HTML ELEMENTS

An HTML element is defined by a start tag, some content, and an end tag.


The <br> tag defines a line break, and is an empty element without a closing tag:

Example
<p>This is a <br> paragraph with a line break.</p>

output:

This is a
paragraph with a line break.


HTML ATTRIBUTES

Style Attribute

<p style="color:red;">This is a red paragraph.</p> --> Colour Changes.
<body style="background-color:powderblue;"> --> background of web page changes to blue.
<h1 style="font-family:verdana;">This is a heading</h1> -> to change font style
<h1 style="font-size:300%;">This is a heading</h1>   -> Chnages font size.

title Attribute

<p title="I'm a tooltip">This is a paragraph.</p> --> if we mouse over paragraph it shows iM a tooltip
<hr> tag defines a break in an HTML page, and is most often displayed as a horizontal rule    -> no end tag
Use <br> if you want a line break (a new line) without starting a new paragraph -> no end tag
The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

FORMATTING

<b>This text is bold</b> -->bold text.
<strong>This text is important!</strong> --> same bold..
<i>This text is italic</i>  --> this txt is italic
<em>This text is emphasized</em>  --> same italic
<small>This is some smaller text.</small>
<p>Do not forget to buy <mark>milk</mark> today.</p>  --> text between mark tag is higlighted.
<p>My favorite color is <del>blue</del> red.</p>   --> a line cuts blue.
<p>This is <sub>subscripted</sub> text.</p>
<p>This is <sup>superscripted</sup> text.</p>

HTML Quotations

The HTML <blockquote> element defines a section that is quoted from another source.

EXAMPLE: 

Here is a quote from WWF's website:

            For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries.
            At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.


<q>xxxx<q> --> double qoutations
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>


HTML COLORS

<h1 style="border:2px solid Tomato;">Hello World</h1>   border

RGB  

rgb(red, green, blue)-> defines the intensity of the color with a value between 0 and 255.
rgba(red, green, blue, alpha) -> The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)

HEX

A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color.
rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

HSL (hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color. Lightness is also a percentage value. 0% is black, and 100% is white.
hsla(hue, saturation, lightness, alpha) The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)

HTML CSS

CSS can be added to HTML documents in 3 ways:

Inline - by using the style attribute inside HTML elements

Ex:  <h1 style="color:blue;">A Blue Heading</h1>

Internal - by using a <style> element in the <head> section

<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>


External - by using a <link> element to link to an external CSS file  (important)

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

"styles.css":

body {
  background-color: powderblue;

}
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
}

The most common way to add CSS, is to keep the styles in external CSS files. 


CSS Padding
The CSS padding property defines a padding (space) between the text and the border

CSS Margin
The CSS margin property defines a margin (space) outside the border.


HTML HYPERLINK

<a href="url">link text</a>

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. The target attribute specifies where to open the linked document.

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window

Ex:  <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

Use mailto: inside the href attribute to create a link that opens the user's email program

To use an image as a link, just put the <img> tag inside the <a> tag:

Example

<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

Button as a Link
To use an HTML button as a link, you have to add some JavaScript code.JavaScript allows you to specify what happens at certain events, such as a click of a button:

Example

<button onclick="document.location='default.asp'">HTML Tutorial</button>


Link Bookmarks

<h2 id="C4">Chapter 4</h2>
Then, add a link to the bookmark ("Jump to Chapter 4"), from within the same page:

Example
<a href="#C4">Jump to Chapter 4</a>


HTML Tables


<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<table style="width:100%">
  <tr>                                --> row
    <th>Company</th>                    th under 1 tr data of 1st row
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

</body>
</html>


To make a cell span over multiple rows, use the rowspan attribute
To make a cell span over multiple columns, use the colspan attribute

HTML Lists

<ul>
  <li>Coffee</li>              --> un ordered
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>              --> ordered
  <li>Tea</li>
  <li>Milk</li>
</ol>


div element

<!DOCTYPE html>
<html>
<body>

<h1>Multiple DIV Elements</h1>

<div style="background-color:#FFF4A3;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>



<div style="background-color:#D9EEE1;">
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>


</body>
</html>


If you change the <div> element's display property from block to inline-block, the <div> elements will no longer add a line break before and after, and will be displayed side by side instead of on top of each other.


HTML FORMS

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

The <input> Element

An <input> element can be displayed in many ways, depending on the type attribute.

Here are some examples:

Type	                          Description
<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button


<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe">
</form>


The <select> element defines a drop-down list

<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>


  <label for="pwd">Password:</label><br>
  <input type="password" id="pwd" name="pwd"><br><br>
  <input type="submit" value="Submit">


Button

<button type="button" onclick="alert('Hello World!')">Click Me!</button>



<textarea>	Defines a multiline input control (text area)
<label>	Defines a label for an <input> element
<fieldset>	Groups related elements in a form
<legend>	Defines a caption for a <fieldset> element
<select>	Defines a drop-down list
<optgroup>	Defines a group of related options in a drop-down list
<option>	Defines an option in a drop-down list
<button>	Defines a clickable button
<datalist>	Specifies a list of pre-defined options for input controls
<output>	Defines the result of a calculation




div tags


The <div> Element
The <div> element is by default a block element, meaning that it takes all available width, and comes with line breaks before and after.

<div> as a container
The <div> element is often used to group sections of a web page together.

to use display: inline-block to align div elements side by side:

<style>
div {
  width: 30%;
  display: inline-block;
}
</style>

Flex
The CSS Flexbox Layout Module was introduced to make it easier to design flexible responsive layout structure without using float or positioning.


To make the CSS flex method work, surround the <div> elements with another <div> element and give it the status as a flex container.

<style>
.mycontainer {
  display: flex;
}
.mycontainer > div {
  width:33%;
}
</style>


--------------------------------------------------------------------------------------------------------------------------------------




JAVA SCRIPT

JavaScript is an interpreted language that executes code line by line providing more flexibility. It is a commonly used programming language to create dynamic and interactive elements in web applications.

console.log("Hello World!"); --> To print a statement

JavaScript is a lightweight, cross-platform, single-threaded, and interpreted compiled programming language. It is also known as the scripting language for webpages. It is well-known for the development of web pages, and many non-browser environments also use it. Javascript Version 6 i.e ES6 contains any features which helps in development.


Internal javascript
  
if we want to write js code in HTMl file only we can either include it in Head or Body between <script> and </script> tags

  <!DOCTYPE HTML>
  <html>
      <head>
                <title>
                      Sample Code Adding js code in head section.
                </title>
                        
                <script>
                   function myFunc() {
                        document.getElementById("demo").innerHTML = "Content Changes!"
                   }
                </script>
       </head>
  
       <body>

          <h3 id= "demo" style="color:blue">
          Anunay Reddy Kallem
          </h3>

          <button type = "button" onClick = "MyFunc">
          Click Here
          </button>
      </body>
  </html>
  

External Javascript File --> extension .js


Javascript Output

1. innerHTML property

document.getElementById("id").innerHTML;

2.  JavaScript console.log()

Console.log("Hello World")

3. JavaScript document.write()

document.write("Hello!");

4. JavaScript window.alert()

window.alert("Hello!");

5. JavaScript window.print()

The window.print() method is used to open the browser’s print dialog,  onclick="window.print()">

6.  JavaScript window.prompt()

let userInput = window.prompt("Please Enter your Input");


  creating object in js

  // Simple function
function vehicle(name, maker, engine) {
    this.name = name;
    this.maker = maker;
    this.engine = engine;
}
// New keyword to create an object
let car = new vehicle('GT', 'BMW', '1998cc');
// Property accessors
console.log(car.name);
console.log(car.maker);
console.log(car['engine']);



  JSON

  JSON (JavaScript Object Notation) is a handy way to share data. It’s easy for both people and computers to understand. In JavaScript, JSON helps organize data into simple objects. 

  const person = {
  "name": "John",
  "age": 30,
  "city": "New York"
};

The object values can be accessed by using the dot (“.”) notation.
We can also access objects by using bracket([]) notation.
Ex: person.name, person.age, person.city


1. For above json let see how we can loop


Looping of an object can be done by using a property for-in loop.
For looping an object we can even use brackets (“[]”) in the for-in loop property. 

for(a in person){
  console.log(perseon[a])
}


2. Converting a JSON Text to a JavaScript Object

JSON.parse() method

const jsonString = '{"name": "John", "age": 30}';
const jsonObject = JSON.parse(jsonString);
console.log(jsonObject.name);



  

3. Importing the local data.json file and display output.
  
 // data.json file 
{ 
	"data": [ 
		{ 
			"name": "GFG", 
			"description" : "A Computer Science portal!"
		} 
	] 
}
 
  
const sample = require('./data.json'); 
console.log(sample.data[0]);



4. JavaScript Date parse() 


let date = "February 18, 2018 12:30 PM";

let msec = Date.parse(date);
console.log(msec); --> gives 178476382 as the output.

  
5. JavaScript JSON stringify() 

The JSON.stringify() method in JavaScript is used to convert JavaScript objects into a JSON string. 
This method takes a JavaScript object as input and returns a JSON-formatted string representing that object.

let value = ["Logan", 21, "Peter", 24];
let result = JSON.stringify(value);


FUNCTIONS

  function myFunction(g1, g2) {
    return g1 / g2;
}
const value = myFunction(8, 2); // Calling the function
console.log(value);



ARRAYS

1. PUSH and POP
  array.push()  or array.pop()  -> add/deletes at the end of the array

2.SHIFT and UNSHIFT
  array.shift()  or array.unshift --> removes/adds first element of the array

3. INCLUDES
  array.include('xyz')  --> To check a specifed element is present in array or not
  
4. MAP
  let newArray = oldArray.map(function (element) {
    return element * 5;
});

ARROW FUNCTIONS*

Arrow Function is one of the most used and efficient methods to create a function in JavaScript because of its comparatively easy implementation

let function_name = (argument1, argument2 ,..) => expression

// Arrow function for multiplying two numbers
let value = (a, b) => a * b;
console.log(value(3, 5));

  
//Arrow Functions without parameters
const gfg = () => {
    console.log( "Hi from GeekforGeeks!" );
}

gfg();

//Arrow Functions with parameters
const gfg = ( x, y, z ) => {
    console.log( x + y + z )
}

gfg( 10, 20, 30 );


  

DOM tree

The backbone of an HTML document is tags.

According to the Document Object Model (DOM), every HTML tag is an object. Nested tags are “children” of the enclosing one. The text inside a tag is an object as well.

All these objects are accessible using JavaScript, and we can use them to modify the page.

	
document.body.style.background = 'red'; // make the background red for the time we specify below
setTimeout(() => document.body.style.background = '', 3000); // return back



Browser Events


Mouse events:
click – when the mouse clicks on an element (touchscreen devices generate it on a tap).
contextmenu – when the mouse right-clicks on an element.
mouseover / mouseout – when the mouse cursor comes over / leaves an element.
mousedown / mouseup – when the mouse button is pressed / released over an element.
mousemove – when the mouse is moved.
Keyboard events:

keydown and keyup – when a keyboard key is pressed and released.
	
Form element events:
submit – when the visitor submits a <form>.
focus – when the visitor focuses on an element, e.g. on an <input>.


Event handlers

To react on events we can assign a handler – a function that runs in case of an event.
Handlers are a way to run JavaScript code in case of user actions.

A handler can be set in HTML with an attribute named on<event>.
For instance, to assign a click handler for an input, we can use onclick, like here:
<input value = "click me" onclick = "alert('clicked!!!!')" type = "button">




Let’s say, one part of our code wants to highlight a button on click, and another one wants to show a message on the same click.
We’d like to assign two event handlers for that. But a new DOM property will overwrite the existing one:

input.onclick = function() { alert(1); }
// ...
input.onclick = function() { alert(2); } // replaces the previous handler

Alternative way of managing handlers using the special methods addEventListener and removeEventListener
which aren’t bound by such constraint.

element.addEventListener(event, handler, [options]);

event -> Event name, e.g. "click".
handler -> The handler function.
options -> An additional optional object with properties.

To remove the handler, use removeEventListener:
element.removeEventListener(event, handler, [options]);

<input id="elem" type="button" value="Click me"/>

<script>
  function handler1() {
    alert('Thanks!');
  };

  function handler2() {
    alert('Thanks again!');
  }

  elem.onclick = () => alert("Hello");
  elem.addEventListener("click", handler1); // Thanks!
  elem.addEventListener("click", handler2); // Thanks again!

</script>


Promises

The constructor syntax for a promise object is:

let promise = new Promise(function(resolve, reject) {
  // executor (the producing code)

  // after 1 second signal that the job is done with the result "done"
  setTimeout(() => resolve("done"), 1000);
  // after 1 second signal that the job is finished with an error
  setTimeout(() => reject(new Error("Whoops!")), 1000);
});
When the executor obtains the result, be it soon or late, doesn’t matter, it should call one of these callbacks:

resolve(value) — if the job is finished successfully, with result value.
reject(error) — if an error has occurred, error is the error object.
	

If we’re interested only in successful completions, then we can provide only one function argument to .then:
	
let promise = new Promise(resolve => {
  setTimeout(() => resolve("done!"), 1000);
});

promise.then(alert);


Fetch

fetch('/article/promise-chaining/user.json')
  // .then below runs when the remote server responds
  .then(function(response) {
    // response.text() returns a new promise that resolves with the full response text
    // when it loads
    return response.text();
  })
  .then(function(text) {
    // ...and here's the content of the remote file
    alert(text); // {"name": "iliakan", "isAdmin": true}
  });


More about promise Apis -- https://javascript.info/promise-api



ASYNC / AWAIT

async ensures that the function returns a promise, and wraps non-promises in it. Simple enough, right? 
But not only that. There’s another keyword, await, that works only inside async functions.

async function f() {

  let promise = new Promise((resolve, reject) => {
    setTimeout(() => resolve("done!"), 1000)
  });

  let result = await promise; // wait until the promise resolves (*)

  alert(result); // "done!"
}

f();









	


  















  

  










































