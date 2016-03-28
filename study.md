// Instructions
// ------------

// 1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
// 2. Submit a pull request with responses to the following questions:

    * What is the different options for `box-sizing`? Explain the differences between them.

If two elements have the same width, but one has more padding, the elements will be different sizes. Using box sizing prevents the the padding and border from changing the width.

what do you mean different options? setting or not setting?

    * In your own words, explain the difference between relative and absolute positioning.

Relative sets the location of an element based off the location it would have without being positioned.
Absolute is essentially fixed in an exact location, but that location is determined relative to another element (10px from the top).


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

1. Clear fixing: when using a float, if the image itself it bigger than the element, clearfix won't let it overflow.
2. For non-image content, when using a float and a percent for the sizing, depending on the content it may not work as seamlessly and the content my get squished.
3. Not all browsers support all or some of newer functionality, and there are usually additional lines of code needed to support different browsers. 
