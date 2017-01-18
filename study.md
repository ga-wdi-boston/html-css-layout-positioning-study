# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The different options for box-sizing are: 1. for the padding, border, and margin to increase the size of the element and 2. for the padding, border, and margin to be incorporated into the maximum size designated for the element.  The first method was the way that the box model historically operated, which resulted in developers needing to do math to figure out the exact size of the elements they were placing on the screen.  The second option allows the developer to create the maximum size for the element and work within it to designate its box-model properties.  This is considered much more intuitive than the old method.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning allows the developer to move the selected element around while still maintaining its same basic place on the webpage.  Relative positioning doesn't change how the element behaves or take it out of the normal flow of the page, instead, any changes to the positioning only move the element relative to where it would have been in the original flow of the webpage.  The rest of the elements on the page don't react at all even if the new relative positioning overlaps with them on the page.

Absolute positioning positions the element relative to its parent element.  Often, the element that is getting styled will have its parent be the window that is displaying the webpage, so the element will be anchored in a fixed spot when viewed in that window.  Scrolling up or down or left or right won't change the position on the screen as long as the window stays the same size and in the same place.  If the user resizes the window the element with absolute positioning can move with the window.  But an element can also be positioned absolute to its parent, like a <li> to a <ul>.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. Using the incorrect positioning will make the webpage behave poorly.
2. Not accounting for different browser types that may be viewing the web page.
3. Trying to style elements with specific sizes that are of a fixed size when the browser will need to be resized or viewed differently.
```
