# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
<!-- You can adjust an elements box size by changing it's width, margin, border
properties. But changing the magin and border properties also changes the width.
We can use box-sizing: border-box to get rid of the unwanted width.   -->
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
<!-- Relative postion is in a normal position by default (static). When it's
top, right, bottom, and left properties are changed, it moves away from it's
normal postition. An absolute postion is like fixed postion except it is
positioned relative to the closest postitioned parent.  -->
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!--

1. Overflow - When you have an element that is larger than the it's container.
This can be fixed with the clear fix hack.

2. Positioning - Making sure your block elements are positioned the way they are
intended to be. It is easy to use the wrong positioning.

3.  IDs - ids should never be used when you have much better tools to choose
from.

   -->
```
