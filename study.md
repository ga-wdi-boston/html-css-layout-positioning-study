# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Box-sizing consists of width, padding and border.

The width is the actual rendered width.  The border is the spacing between other objects.
The border will subtract from these other objects rather than the width.  The passing is the
space between this border and width.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Absolute positioning removes an object from the flow of the document, allowing you to place
it at a specific point in the page.

Relative is similiar however moves at object relative to it's starting position in
comparison to absolute which is from the top left of the page.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
Misusing ids and classes.  As an id can only be used once it is usually better to use
classes unless an id is entierly neccessary.

Not using shorthand properties is also a common mistake.  This will uncomplicate your code.

Not providing fallback fonts is another common mistake.  If a browser is unable to support your chosen font,
it will revert to your "web-safe" font if specified.
```
