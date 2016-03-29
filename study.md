Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What are the different options for `box-sizing`? Explain the differences between them.

    There is border-box and content-box. Content-box includes the height and width properties of only the content.
    Border-Box includes the height and width properties of the content, padding and border.


    * In your own words, explain the difference between relative and absolute positioning.

    Absolute position is removed from the flow of other elements, meaning that it's position is not affected by other elements -- it literally will stay in that specific position. Also, absolute position is dependant on the relative positioning of its parent element, whereas relative position is relative to where it would normally be positioned in the flow of elements.


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

    Common Gotchas from my experience:
    1.) Positioning your elements with different layout stuctures(inline layout mixed with float layout)
    2.) Overflows.
    3.) Height and Width choices that may push elements to areas of the sheet you did not expect.
