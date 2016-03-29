Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:


    * What is the different options for `box-sizing`? Explain the differences between them.

          One is content-box. The width and height properties only include the content. Border, padding, or margin are not included. Another is border-box; with this the width and height properties (and min/max properties) includes content, padding and border, but not the margin.

    * In your own words, explain the difference between relative and absolute positioning.

          Relative positioning will move an item (determined by its height/width properties), regardless of the position of other items on the page. A fixed item will not move at all, regardless of scrolling. It still has top/bottom/etc properties. An aboslute positioning will anchor itself to its nearest positioned ancestor.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

          If a float item is bigger than the item containing it, it can cause formatting issues.

          Another is resizing an element and expecting a boarder/padding/margin to be included, thus making the item much bigger than you wanted.

          A final one, is that if you dont adjust for resizing of the window and make it responsoive to other formats, you can easily mess up your intended design and make it ugly, especially when dealing with non-static elements.
