# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
there's the old way, where you had to do math to account for the margins and
padding along with the width to make sure the total width was as intended, and
then there's the new way where you don't have to do math to determine the total
width. There's also max and min widths that are self explanatory, and a new
thing called flexbox that's pretty darn spiffy.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning is not too fancy, but allows you to place elements in a
specific way relative to other elements on the page. Absolute elements are
placed are stuck in position in relation to its nearest parent element, if it
has one, and if it doesn't have one, then it is permanently positioned in the
body.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

```md
Not taking into account different feature support across multiple versions of a
browser; not taking into account different screen sizes when setting element
sizes; and allowing your image to overflow its container because you didn't
implement the clearfix hack.
```
