# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

Some options for box sizing include the box-sizing property itself which allows for the padding and border of the element to no longer increase its width as it would using the width, margin, and padding properties alone. The box sizing property uses three properties (-webkit-box-sizing, -moz-box-sizing, and box-sizing) which are all set to the value border-box. The other method of box-sizing takes a little more finesse and uses the width, margin, padding, and border-width properties to size boxes. The latter method can be rather finicky.

In your own words, explain the difference between relative and absolute
 positioning.

Relative positioning is a customizable static positioning. So instead of having the element fixed in one location you can further style it using CSS to move it around the web page. Absolute positioning positions an element to the nearest positioned ancestor and allows it to be further customized using CSS from there.

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

The common mistakes when working with CSS layouts are forgetting punctuation which can cause elements and classes to run together, having too much whitespace in your stylesheet which can cause increased file sizes and slower page loading times, and forgetting quotation marks when determining values for the font-family property.
used:https://speckyboy.com/perfecting-the-stylesheet-common-errors-made-by-css-beginners/
