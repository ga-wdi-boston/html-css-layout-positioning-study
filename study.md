# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
Because of the "box-model" in CSS, before box-sizing, developers had to use math if they wanted to make sure the width of two different elements was identical if
they wanted the first element to have a margin and/or padding, and the second
element to have none. Now, by using the `box-sizing` property on a particular
element (and setting its value to `border-box`), the padding and border of the element no longer increase the width of the element. No math needed!
its
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
`Absolute` positioning behaves like `fixed`, except its placement is relative
to the nearest-positioned ancestor, instead of relative to the viewport.
`Relative` positioning, on the other hand, allows you to move an element by setting other properties like `top`, `right`, `bottom`, and `left`. However, if you do not add extra properties to a relatively-positioned element, it will
behave the same as an element with the position `static`.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Three "gotchas" that I think could easily trip up someone who is new to CSS are...
1. When two properties have the same number of points caculated for their specificities, the CSS rules that come `later` (ie, lower down) in the file will essentially overwrite the earlier rules. This is because of the CASCADING part of CSS, meaning that browsers read style from top to bottom, so earlier CSS style rules will be overwritten by later ones with equal specificity. This could be very frustrating, and the reason why a particular style you wrote in your code is not "showing up" when you render the file in a browser.

2. Relative and static position properties are somewhat confusing, because unless you add additional properties (left, top, etc.) to relative positioning, the element it's applied to will behave the same way as if the element was positioned statically.

3. When you use a `float` on an image, if it is taller than the element containing it, it will "spill out" of its container. In order to avoid this, you have to
use the `clearfix` hack. This can be tricky to remember for new web developers.

```
