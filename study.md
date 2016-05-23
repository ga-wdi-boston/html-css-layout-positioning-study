Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`?   Explain the differences between them.
  The default is for the size of an element to include margin, border, padding + the actual element size.

  The box model hack changes adjusts so that border and padding nolonger account for extra add ons to the element size.
  Size is taken away from the inside rather than added to the outside.



    * In your own words, explain the difference between relative and absolute positioning.

relative positioning allows releases an element from its static position or its default position on the page. from there, relative to the VIEWING WINDOW or its static position, the element can be positioned, right, left,

absolute positioning releases an element from its static position and positions it relative to the nearest element that has a set position.  absolute positioning is depended on the position of other elements but if there are no other elements with a position relative to the viewport then absolute positioning will default to position relative to the viewing window.


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

-fogetting to clear following elements after you've floated previous elements
-elements inheriting styling from other rules
-default styling (especially margins and padding)
