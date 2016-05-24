Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
2. Submit a pull request with responses to the following questions:
    * What are the different options for `box-sizing`? Explain the differences between them.

  border-box is one option. box-sizing is very new so you also have to show several prefixes like this:

      -webkit-box-sizing: border-box;
         -moz-box-sizing: border-box;
              box-sizing: border-box;

  aside from border-box, the other three options are: content-box, initial, and inherit.

    * In your own words, explain the difference between relative and absolute positioning.

Aside from relative and absolute, there are also static and fixed positions.

Static position is default and it has elements stay in the normal order and layout from the html.
Fixed position

Relative positioning moves an element relative to its normal location.

Fixed positioning keeps an object in the same place in the window that the user is
viewing it in, so it stays visible in the same place while they scroll.

Absolute positioning is just like fixed positioning except it is relative to an ancestor,
rather than the window. If there is no ancestor, that absolute positioning uses the window,
in which case it is the same as fixed positioning.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

I'm not sure if there was a list of three somewhere in that article, but I found a few.

1. If you aren't careful, different objects that should be the same width may not be,
due to border, padding, and margin differences.
2. Different browsers behave differently, so you have to build for (and test on) multiple browsers
3. Using `float` can be dangerous without `clear` because later elements may overlap with the floating one.
