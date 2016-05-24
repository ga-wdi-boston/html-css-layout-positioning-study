Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.

    Content is represented in rectangular boxes, and different options exist for
    manipulating the box sizes.  
    Content-box - this is the default value which measures only the width of the
    content, excluding padding, border and margin
    Padding-box - this area extends to the border and when padding is added to the
    element, the space between the padding and the content edge increases making
    it appear as if the content is being pushed further in to the box.
    Border-box - this changes the box model in such a way that it prevents extending
    the width or height of an element by adding padding or borders

    * In your own words, explain the difference between relative and absolute positioning.

    Relative positioning behaves the same way as the default value for non-positioned elements.
    It is not positioned in any unique way, unless given additional properties defined by
    top, right, bottom and left.

    Absolute positioning behaves similarly to fixed positioning insofar as it always stays
    in the same place relative to its "nearest positioned ancestor." In other words,
    an absolute positioned element looks for a parent element that has relative positioning
    and is positioned in relation to that element.  


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

    1. Floated elements can overlap and occupy the same space as other elements or
    break out of its container.
    2. Remembering the values for the display property and what belongs to which element  
    3. Forgetting to assign a relative position to the parent, or the container,
    of the absolute positioned element.
