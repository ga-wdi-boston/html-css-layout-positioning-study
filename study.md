# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different options for box-sizing are:
content-box - The default value.  Content, padding, border and margin can all impact the size of the element.
border-box - Content, padding and border are included in the height/width, but margin isn't.
initial - It sets the property to the default value.
inherit - The property inherits it's value from the parent element.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative - By default an object that is uses relative positioning behaves like a static object.
You can move it relative to its starting location using the top, bottom, left and right properties.

Absolute - An object that uses absolute positioning is positioned relative to its nearest
positioned ancestor or the body if all ancestors are unpositioned (static).
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. Making design decisions that don't account for mobile. Using max-width and response design can help fix this.
2. Understanding the box model and accounting for an element's border, padding, etc. when assigning height/width.  Box-sizing can help with this.
3. Issues with floating.  Making use of the clear property and the "clearfix hack" can help resolve these issues.
```
