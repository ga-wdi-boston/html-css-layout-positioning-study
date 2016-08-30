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
  neighboring elements.

  Absolute positioning moves an element based on its nearest non-static positioned
  ancestor then fixes it there.  It behaves like fixed positioning, except
  instead of being fixed in position on the html page, it is fixed to the nearest
  element.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
  1. Leaving accidental styling on a CSS page lower than the style you intend to
  use, leaving you scream, "WTF isn't this working????"
  2. Using the wrong type of positioning.
  3. Messing up your floats and clears.
```
