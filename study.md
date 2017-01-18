# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The options for 'box-sizing are :box-sizing: border-box, which only works on firefox. box sizing with the prefixes -webkit- and -moz- allow for box-sizing on specific browsers.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
The difference between relative and absolute positioning is that relative positioning starts at the static position like rest of the content blocks and does not effect their positioning. Absolute positioning, however, starts in the top left of the page and causes other content to slide down.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
< 1. Using too ID's. While they are more specific, they limit your ability to resuse specified style in other parts of your webpage layout. Use class'.

2. Forgetting to add a clearfix. Why does my layout look so weird and overlapped?
3. Avoid having to remember clearfix by avoiding floats all together. Try inline-block.  
```
