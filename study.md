# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
content-box, border-box, intial, inherit

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning means that the element is positioned in a way that corresponds with its normal position.

Absolute positioning means that the element is positioned relative to the nearest positioned element. If there are not surrounding elements, it'll be positioned in relavance to the document body.

```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. If you have 3 related divs and two of them float left and one floats right, the fload of the third div will be ignored.

2. setting the width of an element to 100% will not work if the parents width is not 100%.

3. z-index is not a functioning css property. LOL !

```
