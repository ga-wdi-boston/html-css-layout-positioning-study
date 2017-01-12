# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The box-sizing property determines whether an elements border and padding
affect its overall height and width.  The two options are "border-box" and
"content-box".  If an element is given "border-box" box-sizing, its height and
width will not be affected by the amount of padding it has or the width of its
borders.  That is, its overall size will take account of the padding and border.

Assigning "content-box," conversely, will cause the browser to add the padding
and borders to the overall height.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative and absolute positioning both make it possible to adjust the position
of an element.  They differ in two key ways.  First, relatively positioned
elements remain in the document "flow" -- they take up space like static elements
and surrounding elements' positions are adjusted accordingly-- while abosultely
positioned elements are removed -- they do not occupy space and do not affect the
position of other elements on the page.

The other differnce is that the top, left, right, bottom properties offset the
element from where it would have been positioned staticly.  The top,bottom,left,
and right properties on absolutely positioned elements, on the other hand,
specify the position of the element relative to its nearest non-static
parent.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. When positioning with inline-block, any whitespace between elements in the
html page will create space between the elements on the page.  This is an
unexpected behavior whitespace does not affect page rendering in most other
scenarios.

2. When positioning something absolutely within a positioned container, the
absolutely positioned element's height and width will not affect the height of
the container and so may overflow the container.

3.Failing to pay attention to the box-sizing property of an element can
can dramatically change the effect of the other css properties assigned to the
element.
```
