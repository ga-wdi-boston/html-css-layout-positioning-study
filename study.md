# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
-webkit-box-sizing: border-box; // works for safari and chrome
-moz-box-sizing: border-box; // works for firefox
box-sizing: border-box; // works for all others (except < IE8)
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
relative positioning allows the div to be moved away from the normal position but will move relative to the div it is in. an absolute div is put in a specific spot within its parent and will not move.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
- setting width to a specific measurement that doesn't work well when a window is too small (use max-width instead)
- floating an img that is bigger than the other div content (fix with clearfix)
- nav that is displeasing when the window is too narrow (fix with media queries)
```
