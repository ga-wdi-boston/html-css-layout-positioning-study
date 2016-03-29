Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.

    Box sizing is used to calculated the widths and heights of elements.  The default option is content-box.  In this option the element's height and width are determined before the margin and padding.  In contrast, border-box measures the element's height and width after the margin and padding are added.

    * In your own words, explain the difference between relative and absolute positioning.

    Relative positioning determines an element's position relative to other elements in a document.  Absolute positioning places at an element at an absolute value that does not fluctuate based on other elements' positions.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

    1. Ignoring compatibility across different browsers.  For example, css methods such as transparencies will display incorrectly unless coded to various browser specifications.
    2. Not using border-box and neglecting padding when sizing an element.
    3. Errors in syntax like omitting semi-colons.
