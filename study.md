Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    For box-sizing, you can add your own margin and padding, and then do the math to make sure the size of elements match up to one another.  Another, easier, option is to use the box-sizing property that does not increase padding or borders of elements, so that they are sized the same when their width and margin are declared.

    * In your own words, explain the difference between relative and absolute positioning.
    * Relative positioning can move an element around the page and not have an effect on other elements.  With absolute positioning, an element has a fixed position relative to the nearest parent/ancestor DOM element, and it can still be moved around the page.
    *
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
    * 1) You could confuse a fixed position with an absolute position.
    * 2) You could have an issue where your floated image is larger than your container element, and you forget to use a clearfix.
    * 3)  You could use a percentage width for an element, but it can resize strangely.  Instead you would probably want to use a media query.
