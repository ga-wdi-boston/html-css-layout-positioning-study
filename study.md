# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The box model option is the older, unintuitive way to set box sizing.  The new way to set box sizing is to use the box-sizing: css element.  When you use this on an element,  the padding and border width are not increased.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning uses the top, right, bottom, and left properties to set position.  Absolute positioning is positioning relative to its parent. If an element has no positioned ancestors, it uses the document body, and still moves along with page scrolling.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. forgetting to use clearfix
2. box sizing issues because you forgot to add margin, padding and border into the math equation for total size
3. not using max-width



```
