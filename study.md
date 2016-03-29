Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.

1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    * The box model (old and considered unintuitive) simple layout where you can set the width and margin.  When you add functions like a border and padding it stretches out the element beyond the specified width.  Makes contents look biger than you want.
    * Box-sizing writen as box-sizing: border-box; is a new CSS property that does not increase the width when you add padding and borders.  One thing you must do though is include the -webkit- and -moz- prefixes due to different interpretations from other browers.



    * In your own words, explain the difference between relative and absolute positioning.

Relative positioning is very simple with no real effects to the content layout.  You have to add properties to it like borders (top, bottom, left, right) etc.
Absolute acts like fixed positining, in that it moves with the page in relation to its closest ancestor.  If it does not have an ancester than the postion is fixed to the body.  It will move when you scroll through the body.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better

Picture to big for the continer and it is floated causing it to overflow.

using float incorrectly

Not using media queeries
