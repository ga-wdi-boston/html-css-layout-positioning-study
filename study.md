# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
The different options for `box-sizing` are:
- `content-box`  (height and width include only content and not padding, border or margin)
- `padding-box` (height and width include content and padding but not border or margin)
- `border-box` (height and width include content, padding, and border but not margin)

Reference: https://css-tricks.com/box-sizing
Reference: https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
With relative positioning (position: relative), other set positioning attributes
are used to shift the position up/down/left/right of an element based on its
regular position.

With absolute positioning (position: absolute), an element's position on a web
page is placed exactly where the developer wants it on a page (i.e. "hardcoded
position").

Reference: http://learnlayout.com/position.html
Reference: https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
There are several but three "gotchas" when working with CSS layouts are:
- Not using global styles (i.e. h1, p)
- Not using unique names for ids and classes (divs)
- Not using shorthand code for declarations
    Use padding: 5px 10px 0 10px   instead of:

    padding-top: 5px
    padding-right: 10px
    padding-bottom: 0
    padding-left: 10px
    
Reference: https://webdesignledger.com/the-most-common-html-and-css-mistakes-to-avoid/

```
