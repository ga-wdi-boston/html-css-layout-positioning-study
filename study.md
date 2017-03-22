# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
There are a couple different box-sizing options:
  - content-box, this option styles and calculates the width and height of the
content and not the margin and padding.
  - Border-box, applies css style to the width and height it also includes the
content and padding but not the margin.

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning is relative to the first object's possition and it causes
gaps between elements.
Absolute possitioning does not leave space for the element, it posistions it at a
specified position relative to the closest ancestor. If there isn't one it uses the
body.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
  - Using ids
  - Doing inline styles
  - Not organizing the CSS file in  logical way
```
