# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Accoring to the MDN documentation, the default value for box-sizing is 'content-box'.  This option simply sets the width of an object to the width property with padding, border and margin still added to the box.

The border-box option sets the box to the width pattern inclusive of padding and border.  So if width is given as 350px, the object will always appear as 350px on the screen regardless of the rest of the box model.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Setting relative positioning doesn't affect the elements position unless extra properties such as top, left, etc. are used.  Absolute positioning is always based on the position of the absolute element's parent element's positioning.  For example, if you have nested divs, and the parent div is positioned relatively, the absolutely positioning child div would be positioned relative to it.  If the absolutely positioned item does not have a relatively positioned parent, it will attach itself to the document body and move along with the page scrolling, essentially behaving like a fixed element.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I think margin: 0 auto, getting relative and absolute positions, as well as getting floats to look right are common problems.  If you don't quite get the box model, it's difficult to make your elements look right between width, margin, border and padding.
```
