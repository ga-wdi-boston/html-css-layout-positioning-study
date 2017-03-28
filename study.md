# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
There seems to be two different options for box-sizing. One option was for the developer to
to explicitly set border and padding size. This posed a problem in that two elements
with the same width values could look like they were different sizes because of the different
border and padding values. It took some complicated math to make sure the two
elements looked like the same width when the developer wanted them to.

The second newer option is to use the box-sizing property. CSS will now automatically
display the border and padding with the desired effect as it is constrained by the width property.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
When position=relative, the element will be positioned +/- the value set by the top/left/right/etc. properties from its normal position. It is not dependent on any elements like it that preceded it.

position=absolute is dependent upon an element like it that is its parent. An element with this property set will be positioned relative to its parent.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. You may end up setting your element width to be wider than your browser.
2. Explicitly set border and padding values can make elements look bigger than you wanted.
3. Floats can cause inline elements to overflow its container.
```
