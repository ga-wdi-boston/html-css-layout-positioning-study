Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What are the different options for `box-sizing`? Explain the differences between them.
    - box-sizing: border-box effects an element by making sure the padding and border of that
    element no longer increase its width.
    * In your own words, explain the difference between relative and absolute positioning.
    - Elements that are positioned relatively behave the same as 'static' positioning unless
      it has additional properities (top/right/bottom/left) that cause it to adjust away from its
      normal position. An element that has absolute position behaves like fixed position,
      except relative to the nearest position ancestor rather than the viewport.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
    - position properties are difficult to remember.
    - issues with floats misbehaving (if an image is taller than the element containing it) --> clearfix hack
    - flexbox layout mode (implemented differently in different browsers)
