# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
Box-sizing is a CSS property that makes CSS layouts work intuitively. Using
properties like width, padding, and border can be confusing. Sometimes when you
use the width property, it doesn’t always apply in the way that you might
expect. However, with proper box-sizing, a width of 200px really means a
rendered width of 200px.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Absolute positioning allows you to remove an object from the typical flow of
the document and place it at a specific point on the page.
Relative positioning works similarly to absolute positioning in that you can use
top, bottom, left and right to scoot an object to a specific point on the page.
The primary difference is the origin or starting point for the element. The item
placed relative to the startinmg family.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
- Using floats but not clearing them.
- Not understanding how position:absolute; works in the context of other
  positioned elements.
- Omitting semi-colons for each property declaration in a series of
  delcarations.
```
