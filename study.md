# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
It was created so all elements were sized in a more intuitive way.When you set
box-sizing: border-box; on an element, the padding and border of that element no
longer increase its width.
```

In your own words, explain the difference between relative and absolute
positioning.

```md
The relative element is not positioned in any special way unless you add some extra properties. An absolute element always stays in the same place even if the page is scrolled; but stay at a specified position relative to its closest positioned ancestor if any, or otherwise relative to the initial containing block.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Float is intended for wrapping text around images. The clear property is important for controlling the behavior of floats. the clearfix hack works when images overflow the outside of their containers.
```
