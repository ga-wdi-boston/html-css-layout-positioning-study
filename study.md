Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    * In your own words, explain the difference between relative and absolute positioning.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.


content box: default value having the width and height measured with content only-no borders, padding or margin.
padding box: includes the padding and borders that stretches the element past its set width.
border box: includes the border and padding properties but doesn't increase the width of the element.

relative position is fixed-like similar to being static but with extra properties
absolute is fixed like as well but stays in the same place as its relative parent

1. Not making your layouts responsive-mobile friendly
2. Not using clearfix to make sure images fit its containers
3. Not using max-width to handle small windows.
