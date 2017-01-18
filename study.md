# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
I had to use mdn for a better response to this question.

content-box: width and height properties are measured including only the content, but not the padding, border or margin.

border-box: The width and height properties include the content, the padding and border, but not the margin.


```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is just a "normally" positioned element.
Absolute position is when a position has a value, but needs to be a "child" of another position. It's context and position are defined by its parent.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Some of the most common CSS errors that I know I will need to watch out for are:
1. Making sure I always understand the proper context of position:absolute
2. Properly clearing floats
3. Making sure box-model sizes do not overflow
```
