# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box: this is the defalut, where border and padding add on to the total
size of the element.
border-box: this makes it so that padding and margin sizes are included in the
total width of the element, rather than increasing its size.
initial: this resets the box-sizing to the defautl
inherit: this takes the box-sizing property from the parent element.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning CSS will alter the element away from its default settings.
Absolute positioning is when the position is set fixed relative to its nearest
parent, rather than it's default.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Not remembering specificity of a class vs ID, so the override doesn't work
Not clearing a float oject so it overlaps other elements
using a comma instead of a semi-colon (mixing it up with js object syntax)
```
