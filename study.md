# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box: The width and height of the box is determined by it's content but not it's border, padding or margin.

border-box: The width and height of the box is determined by it's content, border and padding but not it's margin. This prevents the size of the box from spilling out past it's specified width/height when border and padding are applied.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative position behaves "normally" except that it can accept additional properties to change it's position (left, right, top, bottom). Absolutely positioned elements are anchored to the nearest positioned element.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. When using inline-block there will be a gap in content if there is whitespace in the HTML.
2. When floating an element, it's containing element can collapse if it doesn't have enough content of it's own and it will need to be cleared.
3. Adding padding and border to an element when using the default box-sizing value of content-box will increase the elements total size; this happens even if you set a specific value for it's width or height.
```
