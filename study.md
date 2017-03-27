# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
One option is to use just the width, margin, padding and boarder-width. This
could lead to boxes with the same width looking totally different depending on the
padding and boarder-widths values. Manual calcuations would be needed to get boxes
looking like they have the same width

Another option is to use box-sizing.  This takes all the guess work out of setting
up 2 same width boxes, but with different padding and boarder-widths.  Since this is
still relatively new, we should use:
-webkit-box-sizing: boarder-box
   -moz-box-sizing: boarder-box
        box-sizing: boarder-box
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning behaves the same as static (unless additional properties are
included).  Relative positioning without the additional properties is not positioned
in any special way.

Absolute positioning depends on the nearest positioned ancestor for its location.
If no positioned ancestors exist, it absolute will use the document body for its
location.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I didn't see these in the reading, so I searched some:
  1.  not using a fallback font
  2.  using redundant properties not DRY
  3.  using color names instead of hexadecimal format
```
