# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The two options are border-box or default(none).  By default, padding and border
are applied to the outside of a box element's max size, which can create some
unintentional layout mistakes.  With border-box, the max-width and height are
preserved.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning takes its movement based on page it belongs in, whereas
absolute positioning changes based on the element that it is a child of.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
The first one generally solved by clearfix: if a div is smaller than an image
floated alongside of it then it displays... unpleasantly.  Without box-sizing:
border-box it's easy to make an element take up more space than you'd intended.
Lastly, it's easy to set the width of element using width instead of max-width,
which can create some unfortunate scrolling situations.
```
