# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between
them.

```md
content-box: This is the default value. Padding, border, and margin will not be
added onto the set height and width, and will instead be set outside the box.
border-box: Padding and border will be added onto the set height
and width.
initial: Reverts to default, content-box value.
inherit: Inherit box-sizing of parent element.
Resource: https://www.w3schools.com/cssref/css3_pr_box-sizing.asp
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning: Element will be positioned relative to its normal position. Element will not be removed from the normal flow of the page, and will retain its original space. Element can be offset by top and left values.
Absolute positioning: Element is removed out of the page flow, so element's original space will be occupied by other elements. Element will be positioned relative to nearest positioned ancestor element, but if there are no positioned ancestors, element will be positioned relative to the document body. Element can be offset by top and left values.
Resource: http://learnlayout.com/position.html
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

```md
Clearing floats: If an element is floated to either left or right, the surrounding elements will wrap the floated elements. To avoid that, you must set the clear value left, right, or both (depending on the situation) to make the 2nd element appear after the floated element.

Clearfix: If you have floated elements inside a parent box, then the parent box may not extend down to cover the entire content inside. In such a case, you must use one of the three methods of clearfix. My favorite clearfix method is the

Absolute positioning: When absolutely positioning an element relative to any parent/anecestor element, you must be sure to position the parent/ancestor element (anything other than static). Otherwise, the absolutely positioned element will be positioned relative to the document body. 
```
