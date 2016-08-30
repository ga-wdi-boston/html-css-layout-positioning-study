# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box: the width and height of the element do not include margin, border,
and padding

border-box: the width and height of the element DO include margin, border, and
padding. In other words, the width and height values represent the actual amount
of space the element will occupy when rendered in the browser.

padding-box: has been discontinued and is probably not worth covering

inherit, initial, and unset: these seem to be not so much styling options as
keywords that tell the browser where to look to find the option it should use.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is the same as static unless the additional properties of
left, right, top and bottom are configured. The values of these properties
tell the browser where to position the element relative to its default position.

Absolute positioning also carries with it the additional properties of left,
right, top and bottom. In this case, however, these properties specify the
element's position relative to a parent element, rather than relative to its own
default position. To find its parent element, an absolutely-positioned element
looks for the closest element that has a non-static position. If none can be
found, it is positioned relative to the document body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Gotcha 1: Floating an element without clearing the element that is intended to
come after it, resulting in overlapping elements with possible obstruction of
key content (plus just plain ugliness).

Gotcha 2: Using percentage width for a sidebar that has key content (e.g. nav
bar) without also giving it a minimum width, and/or a media query that kicks in
for small mobile screens.

Gotcha 3: Using new features or syntax without setting backup styling options in
case the user is running an older browser that doesn't support the new stuff.
```
