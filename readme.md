css shorthands

background-image set an img to an element like div
background-image: url("path")

background-repeat take no-repeat, repeat-x and repeat-y value

background-attachment takes fixed and scroll value when a background-image is added


background shorthand
background: color image repeat position;
border: borderWidth(px) borderStyle color;


border shorthand
border-style: topBottomStyle leftRightStyle;
border-style: topStyle leftRightStyle bottomStyle;
border-style: topStyle rightStyle bottomStyle leftStyle;





margin shorthand
margin: auto;      centered the element by adding equal margin at left and right.
margin: allFourSides;
margin: topBottom leftRight;
margin: top leftRight bottom;
margin: top right bottom left;
margin collapse= only incase of one elements bottom margin and next elements top margin collapse into each other. they don't adds into each other but apply the bigger margin. suppose bottom of h1 is 20px and h2 is 20px. in this case they don't adds up like 40px, they simply have 20px margin between them. this however doesn't happened incase of right and left margin.




padding shorthand
padding: allFourSides;
padding: topBottom leftRight;
padding: top leftRight bottom;
padding: top right bottom left;




height and width values
max-width: px/rem       adds width which can be minimize but can't exceed the given value.
auto = default
% = percentage of the containing box, browser calculate the size for %. 100% width means the available whole width of the browser. % works best with width.
px/rem = specified length
initial = sets to default value
inherit = inherit from parent element.



outline
outline is a line drawn outside of the border of an element. outline is similar as border.
outline-style
outline-color
outline-width
outline-offset: adds space between border and outline of an element.
shorthand outline: width style color;



text
color: apply color on text.
text-align: left center right;
text-align: justify;        make line stretched to make every line same width.
direction & unicode-bidi
direction: rtl
unicode-bidi: bidi-override;        this properties change the text direction.
vertical-align      apply to single words with span tags and take 5 values.
baseline            which is default
text-top
text-bottom
sub
super



text-decoration        take values as follows
overline        adds line above the text line
underline       adds line below the text line
line-through    adds line that crossed the text middle
text-decoration: overline line-through underline;        to add all line to the same text.


text-transform      takes 3 values
text-transform: uppercase lowercase capitalize;

text-indent: px/rem
text-spacing: px/rem
line-height: 1 is default
word-spacing: px/rem
white-space: nowrap     doesn't break text line and add horizontal scrollbar.
text-shadow: horizontal vertical;        takes negative and positive
text-shadow: horizontal vertical color;
text-shadow: horizontal vertical blur color;
text-shadow: horizontal vertical blur color, horizontal vertical blur color;



list-style-type: none circle square upper-roman lower-roman
list-style-position: outside(default) or inside
list-style-image: url('path')
list-style shorthand
list-style: type position image;


CSS table
border-collapse: collapse;      to get rid of double border of table



display: none       doesn't take up the space of the element
display: hidden     takes up the space of the element
display: block      acts like a block element
display: inline-block       acts like a block element but inside a line
display: inline     acts like an inline element
display: grid       enable grid view
display: inline-grid       enable grid view but inline
display: flex       enable flex view


position: static        default
position: relative      relative to its origin, top, bottom, left, right value will cause transform from its origin.
position: absolute      relative to the relative parent
position: fixed         fixed to the viewport
position: sticky (-webkit-sticky)       sticky to the position when scroll, top, bottom, left, right value must be used


overflow: hidden
overflow: visible
overflow: scroll
overflow: auto
overflow-x: hidden      to hide the horizontal scrollbar.



float: left right none(default) inherit;
element which need to appear below the floating element should use clear property.
clear: left right both inherit none(default)


align
margin: auto        make an element horizontally centered.
text-align: center      make the text horizontally centered.

image align center
display: block
margin: auto        margin-left & margin-right:auto;

left/right align without float
position: absolute
right: 0px;


clearfix
