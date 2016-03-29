Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
2.
    * What is the different options for `box-sizing`? Explain the differences between them.

Box-sizing can be set to either content-box or border-box.  Content-box is the default.
Width and height measures will not include the border, padding or margins - only the
content inside.  Border-box includes the padding and border, but not the margins.  This
can require some finagling of measurements to get what you really want.

* In your own words, explain the difference between relative and absolute positioning.
*
* Relative positioning refers to where the element is positioned currently as opposed to
* where it would be if it was positioned statically.  For example, if I set a relatively
* positioned element as having a 10px bottom attribute, it will be positioned 10px from
* where it would be if it wasn't explicitly positioned.  Absolute positioning overrides the
* normal flow of the document.  It isn't affected by other elements and as such, can be
* positioned more precisely.
*
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
    *
    * 1) Not choosing the most appropriate selector.
    * 2) Not accounting for size of the screen and compatibility with different browsers.
    * 3) Forgetting semicolons.
