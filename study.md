# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

Not sure if this question means using border-box vs. not using border-box, but
that's all I can assume based on what's in the reading.

With border-box:
It takes into account specified padding, borders, margins, etc. so when the web
developer specifies dimensions for the element, these are the TOTAL dimensions,
not the dimensions plus whatever padding, borders, etc. are specified. You can
also set it up once so that each element is automatically border boxed.

Without border box:
Padding, margins, and borders add to the original specified dimensions of the element.


```md
<!-- your answer here -->
```

In your own words, explain the difference between relative and absolute
 positioning.
  Absolute is when the element is positioned in relation to its parent.
  Relatively positioned elements are "static" unless certain properties affect
  their place on the page. Then they are positioned relative to the page's body.

```md
<!-- your answer here -->
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

1. Using inline CSS in the html file instead of making a separate css file; it
violates separation of concerns.
2. Syntactical errors: for example, forgetting semi-colons at the end of each
property declaration.
3.Typos in class names, properties, etc. 
```md
<!-- your answer here -->
```
