# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
There are a couple different box-sizing options:
  - content-box, this option styles and calculates the width and height of the
content and not the margin and padding.
  - Border-box, applies css style to the width and height it also includes the
content and padding but not the margin.

```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is relative to the first object's possition and it causes
gaps between elements.
Absolute possitioning does not leave space for the element, it posistions it at a
specified position relative to the closest ancestor. If there isn't one it uses the
body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
  - Using ids
  - Doing inline styles
  - Not organizing the CSS file in  logical way
```
