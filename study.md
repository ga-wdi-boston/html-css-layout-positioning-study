Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    * In your own words, explain the difference between relative and absolute positioning.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

1. Box-sizing has to do with how the width and height of block-level elements are calculated. The default value is 'content-box', in which the height and with of the content of the element is calculated before the margin and padding. 'Border-box' measures the height and width of the element after the margins and padding have been included.

2. Relative positioning positions an element relative to where it would be in the normal flow using the top, right, bottom and left properties. Aboslute positioning positions an element relative to document, and takes it out of the flow entirely.

3. Not using boz-size:border-box, or not calculating the height and width of an element's padding when deciding how tall or wide an element should be. Not using clear or the clear-fix hack when floating elements and having divs collapse. Not making room for position-fixed elements by including margins or position surrounding elements accourdingly.
