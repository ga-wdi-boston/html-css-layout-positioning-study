# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings
// current position //
- Read [Learn CSS Layout](z).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
There are two options for box-sizing: content and border boxes.
Content box refers to the older box model which requires a developer to consider and factor in dimesinos for a box's width, padding, border, and margin. Boxes often appeared larger than their intended width designation.
Border box is the newer box-sizing option. Width designation automatically factors in padding and border dimenions and provides a developer a more intuitive way to designate a box's dimensions.

Also used: http://www.binvisions.com/articles/box-sizing-property-difference-content-border/
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning is a way for a developer to designate a box's position relative to the static/default positioning.

Absolute positioning places the box relative to its nearest ancestor. If there is no ancester, it will use the document body as an ancestor.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
1) Only sticking with the pixel units. rem and em can be just as useful: http://www.veritlabs.com/common-mistakes-found-in-css/
2) Setting line heights using units. This will cause child elements to inherit the computed values from the parent even when this is not the desired result: https://blog.mariano.io/common-css-mistakes-and-how-to-fix-them-8ee0f5e88d64
3) Using the inline element as a main container:
 https://medium.com/@Lariicsa/common-css-mistakes-developers-ignore-17cfb5ac9d2f
```
