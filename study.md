# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
-webkit-box-sizing: border-box; // works for safari and chrome
-moz-box-sizing: border-box; // works for firefox
box-sizing: border-box; // works for all others (except < IE8)
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
relative positioning allows the div to be moved away from the normal position but will move relative to the div it is in. an absolute div is put in a specific spot within its parent and will not move.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
- setting width to a specific measurement that doesn't work well when a window is too small (use max-width instead)
- floating an img that is bigger than the other div content (fix with clearfix)
- nav that is displeasing when the window is too narrow (fix with media queries)
```
