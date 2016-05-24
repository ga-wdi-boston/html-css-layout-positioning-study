Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
2.
    * What is the different options for `box-sizing`? Explain the differences between them.

  The two different options for box-sizing are adjusting margin and adjusting padding. Margin adds space to the top, bottom, left, and/or right outside of the element, between other elements outside of it and padding increases the space inside of the element.

    * In your own words, explain the difference between relative and absolute positioning.

Relative positioning is bascially the same as the default static positioning but can be adjusted to fit the screen differently and will change relative to the viewport. An absolutely positioned element is like a fixed element where it is positioned in relation to the document body if it has no parent, otherwise it is positioned absolutely in relation to a parent positioned element.


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

One common mistake is an image overflowing its container when used with float, which is why clearfix hack was developed. Another mistake is using outdated syntax or syntax not supported by the browser/ version you're using. Another common mistake is making inline <li> (list) elements for horiztonal menus.
