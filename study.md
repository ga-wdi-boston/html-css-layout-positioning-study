# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.
Box-sizing: border-box
web-kit and moz prefixes allow you to use specific features in differnet browsers.

These properties tell browser what height and width should be. It  includes
content, padding and border, but not the margin setting.
```md

```

In your own words, explain the difference between relative and absolute
 positioning.
  Absolute positioning:
    The element is positioned relative to its first positioned (not static)
    ancestor element, so it basically inherits it (?)
  Relative: The positioning is relative to its normal position
```md
Relative positioning is similar to static positioning
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Not remembering to use the .clearfix hack
Messing up absolute/relative/static positioning
Not using a proper CSS reset
```
