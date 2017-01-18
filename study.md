# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different options for box-sizing are border-box, content-box and padding-box.
Border-box has the width and height properties retaining the content,
padding and border. This does not include the margin. Example:

 {
 -webkit-box-sizing: border-box;
      -moz-box-sizing: border-box;
           box-sizing: border-box;
}
Content-box measures the width and height properties alongside the content but
not the padding, border or margin. This is defined as the default and initial value.

Padding-box measures everything except for the border and the margin.

```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is similar to static positioning in a sense where it isn't
positioned in a special way unless we add special properties such as setting top,
right, left, bottom into our code. It will then adjust from its original
position. It is relative to itself.

Absolute positioning is positioned to its parent as opposed to relative
positioning which is to the document body. Absolute is positioned to its nearest
ancestor but if it has no ancestor to position itself with then it will do so
in the document body and move along with page scrolling. Page elements
can be placed anywhere you desire and an element that utilizes this position will
not affect other elements nor shall it be affected by other elements. It works
with other positioned elements as opposed to relative positioning where it
works with itself. However, this position can stunt the flexibility of your website.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Not utilizing the proper position property for the document at hand (fixed,
relative or absolute).

Omitting closing tags, closing braces or semi-colons for each code or set.

Not knowing to adjust width to max-width to avoid the content or image
from stretxing out of the edges of its container. 

```
