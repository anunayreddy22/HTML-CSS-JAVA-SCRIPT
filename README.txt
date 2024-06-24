#HTML-CSS-JAVA-SCRIPT

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





















































