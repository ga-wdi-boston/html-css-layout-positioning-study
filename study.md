Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:

    * What is the different options for `box-sizing`? Explain the differences between them.
<!--
width/height exactly what it sounds like.


padding is like a border immediately around an element or the content. The padding betweeen an element and its border

border is a styled border around an element, with padding in between it and the element and a margin on the outside of that.

margin is the outermost part of the box model. Just like the margins on the furthestmost edge of line paper in a notebook.

From inside out:
content/element=>padding=>border=>margin

box-sizing: when you set this to an element, padding and border no longer add to it's width and height. Meaning it is just content, and it's margins.
-->







    * In your own words, explain the difference between relative and absolute positioning.
<!--
relative behaves just like a static or "non positioned" object until you add extra properties to it. I'm not positive if this means how it will be placed in relation to other relative content only, or specifcally anything you tie a relationship to the relative object with.

  an absolutely positioned piece of content is anything but static. If it has no positioned ancestors it will remain in an absolute to the viewport--which is basically the screen you're looking through, or at least I i think that's a safe way to think about it-- and if it does have positioned ancestors (i think this means ancestors to the content with specific positions, anything but static) then it will be positioned in an absolute relation to that/those.
-->


    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
    <!--

    Accomodating older browsers that nobody should be using anyway, with media queries and special css.

    I'm sure you get used to it but I can see forgetting moz and webkit attributes being a problem.

    I think understanding tricky layout features like floats, clearing and relative or absolute positioning are really helpful to creating good layouts, and making dumb mistakes with them would be gotchas.



    -->
