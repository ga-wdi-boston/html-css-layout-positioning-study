# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
border-box: the padding and the border will not increase the elements height and width
with this option

content-box: this is the defualt value that adds the padding and border onto the
origianl height and width of the element

padding-box: only the padding will not increase the height and width of the element
border will. Not standardized.

used the website given as well as MDN for this one.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
relative is positioned (when moved) relative to its original position. Other elements will
not then be moved around because this element is being moved. They will stay in their original
positions and just the element with the relative position will move.

Where as with absolute it essentially is being ignored by the rest of the elements on the page
absolute is positioned relative to its parent element. the other elements around it ignore that element and move as if it werent there.

I used the website provided as well as stackoverflow with this one
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
syntatical errors: css isnt as forgiving as js is.
box model sizing: forgetting that the size of the element is increased with padding and borders
layout issues: forgetting that setting the position to absolute will effect the elements around
it.. as well as overlapping elements with using floats.
```
