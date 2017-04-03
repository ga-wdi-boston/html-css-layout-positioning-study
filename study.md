# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
You can manually set the size using width and height tags, but these can be
unintuitive since padding and margins can make boxes with the same numbers different sizes.
To fix this you can use 'border-box' to have the numbers more accurately define the size of the
boxes.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative moves a boxes "relative" to how it would have normally been placed if you hadn't
given it a property. Absolute fixes itself to an anchor of it's parent object. So if it's in a div
it will not move within the div.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

```md
I didn't see anything in the article about gotchas, but I assume floats and clearfix will always be something where it's easy to make a mistake and not accurately predict what is going to happen.
Some googling shows me that sizing elements on the page, particularly when using percent measurements
often causes unpredictable results. A third, also from the internet, says that people often confuse
how absolute positioning works.
```
