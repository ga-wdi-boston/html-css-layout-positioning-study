# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
When box-sizing is set  on an element, the padding and border of that element no
longer increase its width. You can set this individually on each element, or you
can set it for the whole page with the webkit or moz pre-fixes.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positining uses top, right, bottom, and left values to set positioning.
If a gap/empty space is left by new position other content will not adjust to
fill the gap.
Absolute positioning is fixed based on the position of the nearest ancestor.
If there is no ancestor it's position will be based on the body of the html.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Using margin auto can be problematic if the browser window is smaller than the
element. It can be an issue on tablets, phone etc.
Clear can behave differently depending on where it's used in the file.
Float can cause issues if the image is taller than element. This can be fixed
clearfix hack.  
```
