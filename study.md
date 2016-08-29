# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The original box model allowed you to set a width of an element, however
any border or padding adjustments would make the box element appear larger than
you intended. This method can still be used, but you have to use extra math
adjusting the width, padding, and border accordingly, to ensure that two boxes
(assuming you want them the same size) end up being the same size.

Another option for box sizing is the box-sizing property. The property Box-
sizing: border-box ensures that an element's width will not be affected by
any padding or borders, regardless of their size. Within box-sizing: border-box,
there are prefixes (-webkit- and -moz-) that can be applied to enable features
in specific browsers.

Other types of box-sizing include box-sizing: content box (the default value for
CSS), which has height and width measured by content only (no border, padding,
or margin); and box-sizing: padding-box (no longer used!!!), whose height and
width include the content and padding but not the border or margin.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is a positioned version of the static position. It takes on
similar behaviors, defaulting to a normal position, but has the option to add
extra properties. These properties (top, left, bottom, and right) can be set
and their values are relative to the original/static/normal position that you
would otherwise have.

Absolute positioning allows the element to stay in the same place even when the
page is scrolled. This positioning is relative to the nearest positioned
element on the page (so a static element would not apply here). If there are no
close by elements, then the absolute position is relative to the document
body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
```
