# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
When box-sizing, you have two main property options. The first is the default, invoed with content-box. This only takes the content of the box into account when calculating the width and height of the box, overlooks the border, margin and padding properties in its calculations. The second is to call box-sizing with the border-box property, which includes the content, padding and border when it calculates the size of the box.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
relative positioning is basically static positioning (which seems to be the positional equivalent of a null value) with the ability to move your property around on the board with the left, right etc. properties. Absolute positioning basically exists in relation to whatever its nearest position ancestor is (which I believe means the closest in the code, though I could be wrong here.).
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
First gotcha is related to box spacing, where if you don't properly calculate, your boxes end up being a bit out of whack. The second one is related to ID's, which is a non-issue if you don't use ID's, and the final issue is that the most recent CSS invocation will override any CSS stylesheet.
```
