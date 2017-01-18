# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different options for `box-sizing` are `content-box` and `border-box`.
-`content-box`: the width and height are measured including the content, but not the padding, border, or margin (initial and default value set by CSS standard).
-`border-box`: the width and height include the content, the padding, and the border, but not the margin (the padding and the border will be inside the box).
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
-Relative positioning: lays out elements as though they were not positioned, then adjusts it without the layout being changed.
-Absolute positioning: it doesn't leave space for the element, so the position is specified to the initial containing block. They have margins, but don't collapse with them.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Knowing which positioning is best, figuring out the properties of the box model, and forgetting to include the `webkit` and `moz` prefixes.
```
