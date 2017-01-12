# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The property 'box-sizing' can be set to these values:

content-box: Only content takes up the space inside the dimensions (width, height, min, max). Rather than the border, padding or margin.

border-box: Content, padding, border all are included in the dimensions. The margin is not.

initial: The property is set to default value.

inherit: the property will inherit the relevant value from its parent element.

http://www.w3schools.com/cssref/css3_pr_box-sizing.asp
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
In Relative positioning The element will move from its normal position based on top, bottom, left, right values.  However, with absolute positioning, an element is poisitioned according to the nearest ancestor.

```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Browser compatibiliity problems.

Not accounting for smaller windows, eg mobile.

using inline CSS.
```
