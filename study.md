# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different options include content-box, border-box, initial, and inherit.
The content-box is default and only includes width and height properties while
excluding border, padding, and margin. The border-box includes width, height,
content, padding, and border but excludes the margin property. The initial
property sets the default value while inherit leverages the parent element.

Source: http://www.w3schools.com/cssref/css3_pr_box-sizing.asp

```

In your own words, explain the difference between relative and absolute
 positioning.

```md

Absolute is at a fixed position on the page at an exact (or "absolute")
location and is based on the browser view port rather than other elements.
Relative position means that the element is placed relative to the position
of other elements and is determined by their box model.

Source: http://www.w3schools.com/css/css_positioning.asp

```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. In box-sizing, -webkit- and -moz- prefixes is only IE8+.
2. Using float without overflow auto can result in images overflowing their container.
3. With in-line block layouts, there will be gap between columns if there
is any white space between them in the HTML.
```
