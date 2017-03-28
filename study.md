# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Source: https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
box-sizing: content-box;
  - the initial and default value
  - width = width of content
  - height = height of content

box-sizing: border-box;
  - width = border + padding + width of content
  - height = border + padding + height of the content

box-sizing: padding-box;
  - width = padding + width of content
  - height = padding + height of content
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Source:
- https://developer.mozilla.org/en-US/docs/Web/CSS/position
- https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning

An element's position can be either "relative", "absolute"/"fixed", or "sticky". In this answer, I'll focus on the difference between "relative" and "absolute".

An element with absolute positioning is not going to be affected by other elements on the page. The element will be placed in the exact position we specify, even if that position ends up overlapping with other elements.

An element with relative positioning is going to move relative to its starting position or where it currently resides. This differs from the origin of an element with absolute positioning (top left of the browser window).
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
Sources:
- Fundamentals
- https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS

1. Using features that are not consistently supported across browsers.
2. Failing to create responsive designs for multiple, diverse devices
   (ex: making the font of a website too small to read on a mobile phone)
3. Using ids instead of classes. This will reduce your ability to generalize
   the CSS code.
```
