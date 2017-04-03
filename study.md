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
the three options that are modifiable for box-sizing are:
-the content inside the box
-the padding surrounding the content
-the border around the padding

The above mentioned are the different levels of an element. If we imagine an element as a box the content would be the innermost level, followed by the next level(padding) and then border

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning works in the same way as static(not positioned in a specific way) until you give it some CSS position properties such as left, top, bottom etc.

Absolute positioning will stay positioned relative to the document body, but if there is a parent element that is relative to it, it will orient itself based on the parent
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
```
-when floating images around text, it can sometimes be oriented so that the text and images overlap rather than around each other
-some CSS properties will not work with every browser, so there may be times where one overlooks the syntax and have the CSS property work with only one browser
-Not accounting for how some elements might actually look on the browser because elements are either inline or block elements
