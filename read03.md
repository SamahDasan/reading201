# Html Lists

## List Types

* ## Numbered List
* ## Pulled List
* ## Definition List

# What is Orderd List  ?

<br>

> < ol>
< li>Chop potatoes into quarters< /li> <br>
< li>Simmer in salted water for 15-20
 minutes until tender< /li> <br>
< li>Heat milk, butter and nutmeg< /li> <br>
< li>Drain potatoes and mash< /li> <br>
< li>Mix in the milk mixture< /li> <br>
< /ol>

<br>


# What is UnOrdered List ? 

<br>

> < ul>
< li>1kg King Edward potatoes< /li> <br>
< li>100ml milk< /li> <br> 
< li>50g salted butter< /li> <br>
< li>Freshly grated nutmeg< /li> <br>
< li>Salt and pepper to taste< /li> <br> 
< /ul>

<br>
<br>

# What Is Definition List ?
## consists of a series of terms and their definitions.

<br>

> < dl> <br>
< dt>Sashimi< /dt> <br> 
< dd>Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce
 < /dd> <br>
< dt>Scale< /dt> <br>
< dd>A device used to accurately measure the
 weight of ingredients< /dd> <br>
< dd>A technique by which the scales are removed
 from the skin of a fish< /dd> <br>
< dt>Scamorze< /dt> <br>
< dt>Scamorzo< /dt> <br>
< dd>An Italian cheese usually made from whole
 cow's milk (although it was traditionally made
 from buffalo milk)< /dd>
< /dl>
<br>
<br>
<br>
---
---
<br>
<br>
<br>

# What is Links

## Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.

< a href="http ://www.imdb.com">IMDB< /a>
<br>
<br>

# What Are The Boxes

## Box Dimensions  (width, height)

## Limiting Width  (min-width, max-width)

## Limiting Height  (min-height, max-height)

## Overflowing Content (hidden,Scroll)

<br>
<br>
<br>
----
----

# Border, Margin & Padding

Border<br>
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge one box
from another.

<br>

Margin<br>
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two 
adjacent boxes.


<br>


Padding <br>
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.


# What is border
 border-width

<br>

> p.one {
<br>
border-width: 2px;}
<br>
p.two {
<br>
border-width: thick;}
<br>
p.three {
<br>
border-width: 1px 4px 12px 4px;}

<br>
<br>

# What Are Border Styles?

>border-styles 
<br>
p.one {border-style: solid;}
<br>
p.two {border-style: dotted;}
<br>
p.three {border-style: dashed;}
<br>
p.four {border-style: double;}
<br>
p.five {border-style: groove;}
<br>
p.six {border-style: ridge;}
<br>
p.seven {border-style: inset;}
<br>
p.eight {border-style: outset;}

# border-color

> p.one {
<br>
border-color: #0088dd;}
<br>
p.two {<br>
border-color: #bbbbaa #111111 #ee3e80 #0088dd;}


---
---

# padding

The padding property allows
you to specify how much space
should appear between the
content of an element and its
border. 

<br>

>p {
<br> width: 275px;
<br> border: 2px solid #0088dd;}
<br> p.example {
<br> padding: 10px;}


# Margin
The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems

> margin-top <br>
margin-right <br>
margin-bottom <br>
margin-left 

<br>
&nbsp;&nbsp;   Example <br>

>p {
<br> width: 200px;
<br> border: 2px solid #0088dd;
<br> padding: 10px;}

><br> p.example {
<br> margin: 20px;}

----
----
# Change Inline /Block Display

## inline
This causes a block-level
element to act like an inline
element.

## block
This causes an inline element to
act like a block-level element.

## inline-block
This causes a block-level
element to flow like an inline
element, while retaining other
features of a block-level element.

## none
This hides an element from the
page. In this case, the element
acts as though it is not on the
page at all (although a user could
still see the content of the box if
they used the view source option
in their browser).

---
---

# Hiding Boxes
## visibility
<br>
hidden
This hides the element.

visible
This shows the element.
If the visibility of an element
is set to hidden, a blank space
will appear in its place.

If you do not want a blank space
to appear, then you should use
the display property with
a value of none instead (as
covered on the previous page)

> li {
<br> display: inline;
<br> margin-right: 10px;} 
<br> li.coming-soon {
<br> visibility: hidden;}

# border-image

>p.one {<br>
-moz-border-image: url("images/dots.gif")
 11 11 11 11 stretch; <br>
-webkit-border-image: url("images/dots.gif")
 11 11 11 11 stretch; <br>
border-image: url("images/dots.gif")
 11 11 11 11 stretch;} <br>
p.two { <br> 
-moz-border-image: url("images/dots.gif")
 11 11 11 11 round; <br>
-webkit-border-image: url("images/dots.gif")
 11 11 11 11 round; <br>
border-image: url("imagges/dots.gif")
 11 11 11 11 round;} 

<br>
<br>

 # box-shadow

Horizontal offset
Negative values position the
shadow to the left of the box.

Vertical offset
Negative values position the
shadow to the top of the box.

Blur distance
If omitted, the shadow is a solid
line like a border.

Spread of shadow
If used, a positive value will
cause the shadow to expand in
all directions, and a negative
value will make it contract.


# border-radius

>p { <br>
border: 5px solid #cccccc; <br>
padding: 20px; <br>
width: 275px; <br>
text-align: center; <br>
border-radius: 10px; <br>
-moz-border-radius: 10px; <br>
-webkit-border-radius: 10px;} <br>



<br>
<br>
<br>


