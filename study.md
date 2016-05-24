Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
      * The options are content-box and border-box, with content-box being the default. For content-box, the width and max-width properties only include the size of the content, so a box with a width of 200px, a border of 10px, and padding of 20px on all sides would actually end up much larger than 200px in total (260px I think). For border-box, the border and padding are included in the width and max-width properties, so a box with a width of 200px, a border of 10px, and padding of 20px on all sides would still only be 200px.
    * In your own words, explain the difference between relative and absolute positioning.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
