# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
content-box - default, the width does not include padding, border or margin, so
the element will take up more space.
padding-box - available on FF only...the width includes the content and padding,
but not border or margin.
border-box will not increase the width beyond what is specified in width, and
not impacted by padding and borders, which is included in the width. Margin is
not included.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning refers to a fixed element which will always stay in the same
place even when the page is scrolled. While Absolute positioning will position it's
self to the nearest ancestors if there is one. Else it uses the document body.
Both will be scrolled out of view on a large page. Fixed will always stay in view
even with scrolling.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Not testing your layout on other browsers, good chance it does not display as
expected.
2. Not planning on various screen sizes when viewing you page...desktop vs mobile.
3. Not using a framework that has tried and true layouts that work across many
browsers out of the box.
```
