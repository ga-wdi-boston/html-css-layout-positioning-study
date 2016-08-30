# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box - This is the default value for box-sizing. Properties like width
correspond to the width of the content rather than the entire box. This means
the entire box will end up larger than the width once border and padding are
included.

border-box - When this value is used, properties like width correspond to the
width of the entire box, rather than just the content. This makes it easier to
know the exact amount of space that an element will take up.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
A relatively positioned element is positioned relative to what its position
would be if it were static. In fact, if no additional properties are set besides
position, a relatively positioned element will behave just like a static
element.

An absolutely positioned element is positioned relative to its parent element.
If the parent element is not relatively positioned, the absolutely positioned
element will position itself relative to the document body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
- float/clear: It is easy for elements to end up in an undesired location if
clear is not used properly.
- non-responsive design: There are plenty of ways for a layout to behave in
unexpected ways depending on the size of the browser. min-width, max-width, and
media queries are very important for these situations.
- accidental overwrite: It is easy to write properties for several classes and
element selectors and have unexpected formatting once the page renders. Because
the CSS uses the properties of the last defined class/element selector (and
keeping specificity in mind), an element may not render as expected.
```
