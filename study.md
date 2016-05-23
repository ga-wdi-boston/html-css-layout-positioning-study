Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.

      Without 'box-sizing' the padding and border of the element will affect its specific width;
      By using 'box-sizing', all elements are always sized in a more intuitive way;


    * In your own words, explain the difference between relative and absolute positioning.

      Relative positioning: relative position is relative to element's normal position; By setting top, right, bottom, and left properties, it can be adjusted away from its normal position;
      Absolute positioning: absolute position position the element relative to the nearest element that has a set position; If there are no other elements with a position relative to the viewport, it would position relative to the document body;

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

    1.Using width: 600px; instead of max-width so that you site can be responsive;
    2.Forgetting that margin actually adds pixel to your object and that padding shrinks your object in order to add padding;
    3.Having too many classes and id's so that you get confused and don't know why something won't set it to what you want;
    4.Not having a clear idea before you start working on the css on how your design should look like in the end;
