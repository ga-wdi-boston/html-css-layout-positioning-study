# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```
When you use border-box: box-sizing, the width of an element *includes* 
the padding and border widths of that element. A box with a width of 100px, 
a padding of 10px, and a border of 10px will have an inner content width of 
60px and a total width of 100px.

The default is border-box: content-box, whether the width of an element is 
exclusive of the padding and border. A box with a width of 100px, a padding 
of 10px, and a border of 10px will have an inner content width of 100px and 
a total width of 140px.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
An element that is relatively positioned is positioned relative to its normal 
place in the page layout. An element that is absolutely positioned is positioned
relative to its nearest positioned ancestor (parent, grandparent, etc.). If all
of its ancestors have the default position (static), then the element is positioned
relative to the document body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->
```
