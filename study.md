# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Adding the box-sizing: border-box attribute will cause the padding and border properties to no longer increase the width of an element's box, and prevent boxes with incorrect sizes or distance between them.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative position allows you to make adjustments to the position of a box relative to the position where it would normally appear, whereas absolute makes adjustments based on the element's nearest positioned ancestor.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
One "gotcha" would be not including the webkit and moz specifications when using newer features, which could cause your css to break on older browsers.

Another would be forgetting to accomodate the extra space created by padding or borders that could cause some boxesto have different widths.

A third might be not considering how the page would look on smaller screens/window sizes.
```
