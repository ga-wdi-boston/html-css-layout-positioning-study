# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box: When width and height properties are measured including only the content, but not the padding, border or margin. So if you add more padding or border that will add to the total size.

border-box: When the width and height properties include the content, the padding and border, but not the margin.
```

In your own words, explain the difference between relative and absolute
positioning.

```md
Relative: This position behaves the same as static unless other properties such
left right top or bottom are added to it.

Absolute: This is positioned in relation to the nearest closest ancestor, or
the way I think of it would be the enarest element based on the html. If
there is no ancestor than it will default to being postioned to the
document body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. When  you are not paying attention to specificity IE classes over divs and
styling doesn't work.
2. When styling in absolute and the element doesn't have an ancestor it will be
positioned to the document body.
3. Even when an element is above another in html. If the top element is floated
 to the left, text would be floated around the other and the div/element on
the bottom surrounds the whole thing.


```
