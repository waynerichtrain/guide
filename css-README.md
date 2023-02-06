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

box-shadow: 5px 5px red;                to the right and down
    box-shadow: <offsetX offsetY color>;
box-shadow: -5px -5px red;              to the left and up
box-shadow: 5px 5px 5px green;
    box-shadow: <offsetX offsetY blurRadius color>;


box-sizing: border-box;
    -webkit-box-sizing: border-box;     enables experimental features in specific browsers
    -moz-box-sizing: border-box;        enables experimental features in specific browsers


COLORS (2 main color models: additive and subtractive)
    RGB (red, green, blue)
    CMYK (cyan, magenta, yellow, black)
    HSL (hue, saturation, lightness)
    RGBA (red, green, blu, alphaChannel(opacity))
    HEXA (red(2), green(2), blu(2), alphaChannel(opacity)(2))
    HSLA (hue, saturation, lightness, alphaChannel(opacity))
color: red;
color: #ffffff;                 another for of rgb (red(2)green(2)blue(2) = #rrggbb)
color: rgb(100, 0, 127);        red, green, blue combination
color: hsl(15, 82%, 56%);       values: hue=0-360, saturation=0-100%, lightness=0-100%
opacity: 0.5;                   opacity(0: transparent - 1.0: non-transparent)
rgba(255, 255, 255, 0.5);
#3B7E20CC;
hsla(223, 59%, 31%, 0.8);


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
height: 100vh;

opacity: 0.5;               opacity(0: transparent - 1.0: non-transparent)

text-align: center;

visibility: hidden;         (hides the element but still takes up space)


WIDTH
width: 500px;               set the width of an element in px
width: auto;                set the width of an element using keyword
width: 80%;                 set the width of an element using percentage
width: 60vw;                set the width of an element in viewport width
max-width: 500px;           To set a max width and prevent from growing too wide
min-width: 300px;


BORDER          adds space (even if it's only a pixel or two) between the margin and the padding
border-left: 10px double rgba(0, 0, 0, 75%);
    border-left-width: 10px;
    border-left-style: solid;
    border-left-color: black;

border-color: red;
border-color: rgba(0, 0, 0, 75%);

border-style: solid;
border-style: double;

border-width: 10px;
background-color
height
width


MARGIN          increases the space between a box and any others that sit next to it
margin-left: auto;
margin-right: auto;
    Centering a <div> horizontally
margin: 20px auto; /* Applies 20px top and bottom margin, auto left and right margin */
margin: 0.5rem 0;
margin: 1em auto;


PADDING         increases the space between the edge of a box and the content inside of it
padding-left: 20px;
padding-right: 20px;
padding-top: 20px;
padding-bottom: 20px;
padding: 20px; /* padding of 20px in all 4 sides */
padding: 2rem 0;


PSEUDO-SELECTOR
a:visited {                 Changes the color of the link when visited
    color: red; }

a:hover {                   Changes the color of the link when hovered
    color: yellow; }

a:active {                  Changes the color of the link whe clicked
    color: green; }

fieldset:last-of-type {     Targets the last element of a specific type
    border-bottom: none;
}