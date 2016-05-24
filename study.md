Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    * In your own words, explain the difference between relative and absolute positioning.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

Question 1: Box sizing is a css selector that when set to border-box prevents
all affected elements from increasing in size when their border or padding is
altered. With this option removed, elements of the same width and height but
differing padding and border widths would display as different sizes.

Question 2: Relative positioning is similar in concept to relative file pathways
in terminal; Their position coordinates are always defined relative to where
their default position. Absolute positioning uses a parent element or the
document window to attain a fixed position, unless the parent has the position
of static.

Question 3: 1.) Not using @media queries to support mobile platforms.
2.) Not using a clearfix to solve overflowing elements within a constainer.
3.) Not making sure element containing a child element absolutely positioned is
large enough to hold it.
