# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
content-box is width and height within that box's content only
padding-box is width and height within that box's content & padding
border-box is width and height within that box's content & padding & border
inherit is getting from its parents like most rich families pass their wealth

```

In your own words, explain the difference between relative and absolute
 positioning.

```md
relative position is with position of the elements normal position properties,
absolute position is with position of the elements parents postion properties.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1 mixing up relative and absolute position properties, or simply not setting them at all
2 mixing up block and inline properties or not setting them at all
3 for when text overflows into an image when using float, you can use .clearfix overflow: auto
'hack', as its put, to fix the overflowing text/ its parent element from  going into the image.

```
