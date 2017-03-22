# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
The options for 'box-sizing are :box-sizing: border-box, which only works on firefox. box sizing with the prefixes -webkit- and -moz- allow for box-sizing on specific browsers.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
The difference between relative and absolute positioning is that relative positioning starts at the static position like rest of the content blocks and does not effect their positioning. Absolute positioning, however, starts in the top left of the page and causes other content to slide down.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
< 1. Using too ID's. While they are more specific, they limit your ability to resuse specified style in other parts of your webpage layout. Use class'.

2. Forgetting to add a clearfix. Why does my layout look so weird and overlapped?
3. Avoid having to remember clearfix by avoiding floats all together. Try inline-block.  
```
