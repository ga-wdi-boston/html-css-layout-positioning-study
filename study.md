# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
The two options are border-box or default(none).  By default, padding and border
are applied to the outside of a box element's max size, which can create some
unintentional layout mistakes.  With border-box, the max-width and height are
preserved.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning takes its movement based on page it belongs in, whereas
absolute positioning changes based on the element that it is a child of.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
The first one generally solved by clearfix: if a div is smaller than an image
floated alongside of it then it displays... unpleasantly.  Without box-sizing:
border-box it's easy to make an element take up more space than you'd intended.
Lastly, it's easy to set the width of element using width instead of max-width,
which can create some unfortunate scrolling situations.
```
