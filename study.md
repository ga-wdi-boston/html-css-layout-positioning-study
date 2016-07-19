# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different option is the box model. The box model sets padding and margins outside of the element's width, whereas box sizing sets marigins and padding within the element.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Absolute positioning is relative to the nearest positioned ancestor. If nearest ancestor isn't set, than it uses body of the document.

Relative positioning behaves as static but it has extra properties (top, bottom, left and right) that adjusts the position of the element from its normal position.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. Using floats and not clearing them.
2. Using absolute postioning and understanding where the current element belongs.
3. Not knowing that floated elements should be placed before the content they float over.
```
