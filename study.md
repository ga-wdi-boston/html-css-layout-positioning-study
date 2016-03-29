Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
      - box-sizing is a new css option. Possible values include "border-box" and "content-box"
      - border-box: Makes it so the width and height properties including padding, margin, and border widths, rather than requiring additional calculations.
      - content-box: Width and height only includes content; width of border, margin, and padding must also be taken into account to determine total size of element.

    * In your own words, explain the difference between relative and absolute positioning.
      - relative: Allows you to set top, right, bottom, and left properties to adjust position of element from where it would normally appear.
      - absolute: Fixes position of an element relative to its parent element.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
      - Browser compatibility issues
      - Mixing CSS into HTML documents
      - Not providing fall-back fonts
