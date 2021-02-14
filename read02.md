# Basics of HTML, CSS & JS

<br>

## first of all these are notes of html 
### X HTML pages are text documents.
X HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.

X Tags are often referred to as elements.

X Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.

X Opening tags can carry attributes, which tell us more
about the content of that element.

X Attributes require a name and a value.

X To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

---

## Text Styleing in html css

### Headings
<br>

* < h1>
* < h2>
* < h3>
* < h4>
* < h5>
* < h6>
<br>

HTML has six "levels" of
headings:

< h1> is used for main headings

< h2> is used for subheadings
If there are further sections
under the subheadings then the

< h3> element is used, and so
on...

---
![](cd.bmp)




# Paragraphs
##  < p >
To create a paragraph, surround
the words that make up the
paragraph with an opening < p>
tag and closing < /p> tag

# Bold & Italic
< b>
By enclosing words in the tags
< b> and < /b> we can make
characters appear bold.
The < b> element also represents
a section of text that would be
presented in a visually different
way (for example key words in a
paragraph) although the use of
the < b> element does not imply
any additional meaning.

< i>
By enclosing words in the tags
< i> and < /i> we can make
characters appear italic.
The < i> element also represents
a section of text that would be
said in a different way from
surrounding content — such as
technical terms, names of ships,
foreign words, thoughts, or other
terms that would usually be
italicized.

> p>This is how we make a word appear < b>bold.< /b>
 < /p>
< p>Inside a product description you might see some
< b>key features< /b> in bold.< /p>

> < p>This is how we make a word appear < i>italic< /i>.
 < /p>
< p>It's a potato < i>Solanum teberosum< /i>.
< /p>
< p>Captain Cook sailed to Australia on the
< i>Endeavour< /i>.< /p>

---

---
---

 # Using External CSS

## < link> chapter-10/using-external-css.html HTML
The < link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the < head> element.
It should use three attributes:
href

This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type

This attribute specifies the type
of document being linked to. The
value should be text/css.
rel

This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.
An HTML page can use more
than one CSS style sheet. To
do this it could have a < link>
element for every CSS file it
uses.
 For example, some authors
use one CSS file to control the
presentation (such as fonts and
colors) and a second to control
the layout. 

***
***
> body {
 font-family: arial;

> background-color: rgb(185,179,175);}

> h1 {
 color: rgb(255,255,255);}

 # Using Internal CSS

< !DOCTYPE html>
< html>
< head>
 < title>Using Internal CSS< /title>
 < style type="text/css">
 body {
 font-family: arial;
 background-color: rgb(185,179,175);}
 h1 {
 color: rgb(255,255,255);}
 < /style>
< /head>
< body>
 < h1>Potatoes< /h1>
 < p>There are dozens of different potato
 varieties. They are usually described as
 early, second early and maincrop.< /p>
< /body>
< /html>

***
***
# CSS SELECTORS
## Universal Selector
## Applies to all elements in the document 
## * {} Targets all elements on the page
<br>
<br>

## Class Selector
## Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol

<br>
<br>

# Child Selector
## Matches an element that is a direct child of another

