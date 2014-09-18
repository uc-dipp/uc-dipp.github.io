---
layout: member-haha
title: Example Member
category: member
---

This is an example Hack Harris member page, to showcase things you can do in HTML, CSS, and JavaScript.


##Overview

The *structure* of a web page is built in HTML (Hypertext Markup Language. The *style* of a webpage comes from CSS (Cascading Stylesheets). 

Pro-tip: Build your webpage in HTML first, then style it in CSS. If you do both at the same time, you will trip yourself up. 


##Fun with HTML
HTML consists of **elements** that contain content inside them. An element looks like this:
`<div>`
    This stuff is inside the `div` element
`</div>`

The element is opened using `< >` angle brackets, and closed using `</ >` angle brackets with a slash after the first bracket.

Some elements:

* `<div>` Contains standard content or other elements
    
    <div>This text is inside a div</div>

* `<p>` Contains text in a paragraph format
    
    <p>This text is in a paragraph</p>

* `<br>` makes a line break.

    Some text
    <br>
    Some more text

* `<em>` Makes the text inside italic

    This text has <em>italic</em> words

* `<b>` Makes the text inside bold

    Some of this <b>text</b> is bold

* `<a href="http://harrisschool.uchicago.edu">Harris School</a>` Creates a hyperlink to the Harris School website

    <a href="http://harrisschool.uchicago.edu">Harris School</a>

* `<img src="bbq.jpg">` inserts the image located at "/bbq.jpg" (in your member folder). You don't need to close this tag

    <img src="bbq.jpg" height="50px" width="50px">
    <a href="https://drive.google.com/folderview?id=0B67xyTocshK8WFV2WlNhQnFyX1E&usp=sharing">Here</a> are some images of DiPP - just copy in the URL to one you like!

* `<h1>` - `<h6>` Makes the text into title text (bigger). You can use any number 1-6: 1 is largest

    <h2>Title 1<h2>
    <h4>Title 4</h4>


A good HTML reference can be found <a href="http://www.w3schools.com/html/">here</a>.
A great free online course in HTML and CSS can be found <a href="http://www.codecademy.com/tracks/web">here</a>.

##Fun with CSS
CSS provides your webpage with *style*. You should have your CSS in an external file in your member folder - and link it at the bottom of your index.html file as follows:

`<link rel="stylesheet" href="me.css">`

The syntax for CSS is as follows:

```
selector {
  property: value;
  property: value;
}
```

`selector` is one of your HTML elements, like `div` or `a`, **without** the `< >`. `property` is a property like `color`, which changes the font color. `value` is something like `#AC1F24`, which is red.

Here are some CSS properties you can change:

* `color: #AC1F24;` sets the text color using a <a href="http://colorrrs.com/">hexadecimal</a> value.
* `font-size: 1.2em;` changes the text size (1em is normal size)
* `background-color: #eee;` makes the element's background light gray
* `margin-left: 20px;` adds a margin, or space, of 20 pixels to the left of the element. You can also use `margin-top`, `margin-right`, and `margin-bottom`
* `cursor: pointer;` makes the mouse a pointer (hand) when it is over the element. A value of `default` is the regular arrow

A good CSS reference can be found <a href="http://www.w3schools.com/cssref/">here</a>.


<!-- this is a comment: it won't be shown -->

<!-- the following incorporates an external stylesheet 
that is located at http://ucdipp.org/members/example/me.css-->
<link rel="stylesheet" href="me.css">

<!-- the following incorporates external JavaScript code
that is located at http://ucdipp.org/members/example/me.js-->
<script src="me.js"></script>
