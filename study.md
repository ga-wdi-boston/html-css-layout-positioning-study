# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
<!-- your answer here -->
border-box - content, border and padding get the width and height
content-box - only the content gets width and height, border, padding, margin isn't touched

initial - default value
inherit - will inherit value from its parent
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
<!-- your answer here -->
relative position - the element is appearing by the default at top left and if I want to move it I need to use some direction properties like top: , left: etc with px or rem or em, also I can use negative values on those

absolute position - there is important to know which is parent to this element - it starts to move from the edge of the parent element while using also top , left: ... the parent is usually set to position: relative; while it's child - this element is set to position: absolute;

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
1. Floating around - clear: right; left; both;
2. Overflowing for example an image the container - clearfix hack - overflow: auto; zoom: 1;
3. Not responsive on certain browser widths - we need to use media queries
4. Not a browser support of some properties

5. Display: inline-block; - affected by the verical-align property - needs to be set to top,
6. Plus we need to set a width for each column
gap between the columns if there is a white space between them
```
