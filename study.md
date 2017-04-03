# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
border-box: this means that the padding and border of an element no longer
increase its width.  Otherwise, you will need to tack padding and border on
when calculating the actual size the box will take up on the page.

```

## Relative vs Absolute Positioning


```md
Each object on the page has a "normal" position where we would expect it to appear absent
any other instructions.  Relative positioning moves the actual location up/down/right/left relative
to what would otherwise be its "normal" position.  Absolute positioning means that the
object is positioned at a fixed point relative to its nearest positioned ancestor.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Not accounting for different browsers.
2. Confusing display types (block vs. in line)
3. 3. Not using a clear fix with float so that elements overlap or look weird.
```
