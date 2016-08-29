# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The three options for box-sizing are:
1. Content-box: The default value rendered by CSS. Width and height properties
   are measured, but not the padding, border or margin.
2. Border-box: Height and width properties include content as well as padding
   and border properties, but not the margin property.
3. Padding-box: Height and width properties include content and padding, but
   do not include border or margin.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md

Static positioning is a default value that indicates an element is without
position unless we add some extra properties to it. Absolute positioning behaves
much like static positioning, except that it changes relative to nearest positioned
elements

```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. Using sing the float property can cause floated images to overflow
    outside of the container that we want it to be in.
2. Box model sizes can overflow when padding or borders are applied after
   declaring height and weight.
3. Failing to recognize the cascade and having it negatively affect your properties
4. BONUS!! Good ol' fashioned spelling and syntactical errors (semi colons, braces, etc)
```
