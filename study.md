Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
      * Box-sizing: Border-box allows the user to adjust padding and border without increasing the size of the element itself.
    * In your own words, explain the difference between relative and absolute positioning.
      * Relative positioning perferms the same way as static unless it is given more values. In which case it moves relative to its starting position. Absolute positioning behaves like fixed positioning but relative to the nearest positioned element instead of the viewport. If there isn't another positioned element nearby then the element itself will scroll with the screen.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
      * 1) Using redundant selectors. 2)Not using shorthand properties. 3)Using 0px instead of 0.
