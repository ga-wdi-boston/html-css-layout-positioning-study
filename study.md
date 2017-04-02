# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
<!-- your answer here -->
```By using the box-sizing:border-box property the padding and border will not increase the width of the element. Though less-inutive, you can also subtract the padding and border amounts when setting the width value.

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
<!-- your answer here -->
``` Assigning the direction settings of a relatively postion element will change its normal position, but the other content will not be adjusted to the new, relative postion. Values assinged to an absolute element only apply in relation to its closest parent element. If there is no parent element, an element with an absolute postion will still move as the page scrolls.

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
```
1. Using too many (or any) Ids instead of class names
2. Neglecting style that will optimize the mobile UX
3. Make sure the CSS class names are an exact match of the html class names
