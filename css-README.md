SELECTORS:
*               universal
<p>             type
.               class
#               id
sel1, sel2      grouping (comma-separated)
sel1.sel2       chaining (no-separation)
sel1 sel2       descendant combinator


BACKGROUND / BACKGROUND-COLOR
background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0));
    linear-gradinet(<gradientDirection, color1, color2>);
background: linear-gradient(180deg, rgb(255, 0, 0) 0%, rgb(0, 255, 0) 50%, rgb(0, 0, 255) 100%);
background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));

background-color: red;
background-color: #ffffff;
background-color: rgb(100, 0, 127);
background-color: hsl(15, 82%, 56%);


background-image: url(domainname.domain);
backrougnd-image: url(./dir1/n.jpg);

box-sizing: border-box;
    -webkit-box-sizing: border-box;     enables experimental features in specific browsers
    -moz-box-sizing: border-box;        enables experimental features in specific browsers


COLORS (2 main color models: additive and subtractive)
    RGB (red, green, blue)
    CMYK (cyan, magenta, yellow, black)
    HSL (hue, saturation, lightness)
color: red;
color: #ffffff;                 another for of rgb (red(2)green(2)blue(2) = #rrggbb)
color: rgb(100, 0, 127);        red, green, blue combination
color: hsl(15, 82%, 56%);       values: hue=0-360, saturation=0-100%, lightness=0-100%


DISPLAY         To manipulate block-level elements to inline elements and vice versa
display: block; (stack atop each other / new line)
display: inline; (appears in line with the element beside - not good for padding and margin)
display: inline-block; (only takes up the width of content - inline but with block-sstyle padding and margin)
display: none;          (hide or show elements without deleting or recreating)
visibility: hidden;
display: list-item;
display: table;
display: flex;


font-family: "Dejavu Sans"
font-family: Verdana, "Dejavu Sans", sans-serif

font-size: 3px;

font-style: bold;
font-style: italic;
font-style: underline;

font-weight: bold;
font-weight: <700 = bold> (1-1000);

height: 100px;
height: auto;
height: 50%;

text-align: center;

visibility: hidden;         (hides the element but still takes up space)

width: 500px;
width: auto;
width: 80%;


BORDER          adds space (even if it's only a pixel or two) between the margin and the padding
border-color
background-color
height
width
border-width


MARGIN          increases the space between a box and any others that sit next to it
margin-left: auto;
margin-right: auto;
    Centering a <div> horizontally
margin: 20px auto; /* Applies 20px top and bottom margin, auto left and right margin */


PADDING         increases the space between the edge of a box and the content inside of it
padding-left: 20px;
padding-right: 20px;
padding-top: 20px;
padding-bottom: 20px;
padding: 20px; /* padding of 20px in all 4 sides */


width
    Set the width of an element either in px or %
max-width
    To set a max width and prevent from growing too wide

PSEUDO-SELECTOR
a:visited {         Changes the color of the link when visited
    color: red; }

a:hover {           Changes the color of the link when hovered
    color: yellow; }

a:active {          Changes the color of the link whe clicked
    color: green; }