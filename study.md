# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
1)You can adjust the size of the original element, after you've created a border and padding.

2)box-sizing: border box = maintains the size of the box to its original size
even with the addition of 'padding' and/or 'border'.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Giving an element absolute positioning means that the element's placement is dependent upon something else on the page and may move if what it is relative to moves.

Giving an element a relative position means that the object will not move unless the top,right,bottom or left properties are manipulated.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1) not using clear after a float
2) having an img expand out of the element that is supposed to be containing it
3) confusing what the position properties mean
```
