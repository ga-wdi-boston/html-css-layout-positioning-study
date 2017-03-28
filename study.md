# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
width:  how wide the box is including the border and padding
padding:  space between the content and border
border:  space between padding and margin

http://blog.teamtreehouse.com/box-sizing-secret-simple-css-layouts
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
With relative positioning, you have to assign it properties - otherwise, it really has no defined positioning.  The positioning you assign will move the element from it's normal position accordingly.  It may leave gaps or overlap other elements.

Fixed positioning puts the element in the same place on the page regardless of browser window size.  It can also lay over other elemwents.

http://learnlayout.com/position.html
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
Not providing fallback fonts.  For example, don't just specifiy font-family Arial, but list backup as well such as Helvetica, sans-serif (generic in case it needs to display something other than Arial or Helvetica).

Using color names instead of hex values.  What you intend and what the browser things is red could be different.  Be specific with #000000 for the color you choose.

Syntax errors like omitting ; after each property or closing braces after each rule.

https://www.quora.com/What-are-some-common-errors-or-gotchas-in-CSS

http://sixrevisions.com/css/12-common-css-mistakes-web-developers-make/
```
