# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
You can put 'box-sizing: border-box;' on a specific element, so that the padding and border of that element won't change the width, and you don't end up with elements with the same width but look different on the page.

If you want all the elements to do this, you can put:
* {
  -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
      box-sizing: border-box;
}
Compared to the first way, this CSS code makes everything size so that the padding and border don't change the width.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
If you add relative positioning to an element, it is positioined relative to its normal position. Relative positioning is relative to the viewport.

On the other hand, absolute positioning is positioned relative to the nearest positioned ancestor element (not the viewport), unless there is no ancestor, in which case it uses the document body.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. When you float an image to have text wrap around it, but the image is taller than the element containing it, it overflows - which is easy to overlook.

2. Elements that have a set width become wider when they have padding or border-width.

3. Elements with position: fixed are placed relative to the viewport, hwereas elements with position: absolute are placed relative to their closest parent - which is counterintuitive!
```
