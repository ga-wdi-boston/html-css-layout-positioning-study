# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Every html element is a box.

The box-sizing default, content-box, defines the dimensions of an element by its content. The padding, border, and margin will be outside of those dimensions.
If set my <div> to have a height and width of 100px the content will be 100px by 100px.  It's padding, border and margin will start outside of the square increasing the size of the <div>.

box-sizing: border-box puts the padding and border of an element inside the specified dimensions. Only the margin will occur outside those dimensions.



https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
An element with position: relative will be placed in its normal position, the same way a static element would be.
If we give the relatively positioned element a value for the properties top, left, right or bottom it will be positioned away from its normal position.

An element with position: absolute will be placed in relation to its nearest positioned parent elmement. A positioned element is any element with a position other than static. top, left, right, and bottom will move the absolutely positioned element around inside of its parent element.

http://learnlayout.com
https://developer.mozilla.org/en-US/docs/Web/CSS/position
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I'm not sure what mistakes are the most common across the development community but here's what comes to mind for me.

Forgetting to close an html tag and mistaking it for a css mistake.
Forgetting that the height and width properties for an element don't take the padding and border into account by default.
Using clear and float seem like seems like a mistake in most cases. I've never had much luck with it after I've added more than a few block elements to a page.


https://medium.com/@isaaclyman/8-css-gotchas-to-start-your-morning-off-right-c5daade0731d
https://webdesignledger.com/the-most-common-html-and-css-mistakes-to-avoid/
```
