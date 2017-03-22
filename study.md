# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
The different options for `box-sizing` are `content-box` and `border-box`.
-`content-box`: the width and height are measured including the content, but not the padding, border, or margin (initial and default value set by CSS standard).
-`border-box`: the width and height include the content, the padding, and the border, but not the margin (the padding and the border will be inside the box).
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
-Relative positioning: lays out elements as though they were not positioned, then adjusts it without the layout being changed.
-Absolute positioning: it doesn't leave space for the element, so the position is specified to the initial containing block. They have margins, but don't collapse with them.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
Knowing which positioning is best, figuring out the properties of the box model, and forgetting to include the `webkit` and `moz` prefixes.
```
