# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What are the different options for `box-sizing`? Explain the differences between
 them.

```md
You can alter width, margin, padding, and border along with box-sizing in the 'fancy' version of this property.

The box-sizing property itself allows us to include the padding and border in an element's total width and height.
Width changes the width of the box relative to the webpage.
Margin generate space around elements, and set the size of the white space outside the border.
Padding changes the amount space around the content of the box, and clears an area around the content (inside the border).
Border changes the style, width, and color of an element's border.

```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative position adjusts an element away from its default static position, while absolute position positions the element relative to its nearest positioned ancestor or, barring that, positions it in the body.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. not adding CSS that accounts for the technological "lag" of older/different browsers
2. not using different, more abstract parameters to account for mobile usability
3. forgetting to close tags immediately
```
