## Reading Notes
### Links In HTML

Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.

FOr Example :
<a href="http://www.imdb.com">IMDB </ a> 

The text between the opening <a> tag and closing </a> tag is known as link text. Where possible, your link text should explain where visitors will be
taken if they click on it (rather than just saying "click here")

### Layout 
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.

Block-level elements: start on a new line.
examples : <h1> <p> <ul> <li>
Inline elements flow in between surrounding text.
examples: <img> <b> <i>

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.


Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.