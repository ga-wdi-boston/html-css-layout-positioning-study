# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What are the different options for `box-sizing`? Explain the differences between
 them.

```md
  Box sizing is the new, hip way to mess around with the box model.  It makes
  height and width THE height and width of an element.  Unlike the box-model,
  which adds border-width, margin, and padding to the element's height and width,
  box-sizing cuts the border-width, margin and padding out of the height and
  width. This is cool because doing math over and over sucks sometimes.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
  Relative positioning is the most common type of positioning we will use and
  has the most general application.  It makes elements move relative to their
  neighboring elements.  Absolute position has a fewer number of use cases.
  Two of the best uses would be a static header/nav bar that you want to stay in
  place while you scroll down the page.  The second would be a button you want
  to stay on the screen.  The example that first comes to mind is a 'back to top'
  button.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
  1. Leaving accidental styling on a CSS page lower than the style you intend to
  use, leaving you scream, "WTF isn't this working????"
  2. Using the wrong type of positioning.
  3. Messing up your floats and clears.
```
