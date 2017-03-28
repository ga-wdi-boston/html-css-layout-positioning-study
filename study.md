# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
So according to MDN, there's content boxing and border boxing. Content boxing is the width and height of your content without padding, borders, and margins.
Border boxing is the width and height of the element's content, padding, and border combined. 
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning moves the element on a webpage depending on the specific direction you tell it to by using properties.
Absolute positioning fixes and element to a spot of your choosing in relation to where you to where its parent element is.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Recognizing that different browsers may require different keywords to do the same things (-webkit- and -moz- for example.)
2. With percent-width layouts, make sure that the percentages add up to 100% or else there will be gaps in the layout.
3. If you float an element to one direction, make sure that if you need to clearfix, indicate that same direction.
```
