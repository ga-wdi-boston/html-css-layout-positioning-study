# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
Using content-box, the default, padding and border increase the width of an element.

Using border-box, padding and border do not increase the width of an element.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning places elements where static position would, but allows you
to move their position relative to that location with left, right, top and bottom.

Absolute positiong places elements similarly to fixed positioning, but it's location
is fixed to its nearest position ancestor. So an an absolute positioned div within
a relative positioned div is positioned similarly to fixed, but moves with the
relative positioned div it is within.

```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1) Using width instead of max-width when horizontally centering content.
2) Whether to use absolute or fixed positioning for "sticky" elements.
3) Not clearing floats.
```
