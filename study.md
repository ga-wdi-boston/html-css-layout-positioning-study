# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
Can set box-sizing: border-box; so the padding and border of the element no longer increase.

Can use -webkit-box-sizing, -moz-box-sizing, and box-sizing all as border-box to make sure all elements are sized the same way
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Absolute positioning is similar to fixed but with page scrolling if there are no near positioned ancestors. This position is specific and relative to the ancestor or the inital containing block.

Relative positioning holds absolutely positioned children. This lays out elements like they are not positioned and can adjust the position without changing the layout
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Using inline-block to avoid having to write extra code to 'clear' something

Can use -moz- and -webkit- to make styling in CSS a lot easier. Like for adding columns within a div.

Can set a min-width if you want a container to always be at least that size even when the browser is smaller.
```
I used these webpages to help me:
https://developer.mozilla.org/en-US/docs/Web/CSS/position
