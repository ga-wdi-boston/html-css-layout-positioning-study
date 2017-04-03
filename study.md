# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
<!-- In the past, CSS programmers would set a value for the width of a box
and then to manipulate it, you would have to subract out or add border and
padding to the box as well. Otherwise, it would change the width of the box to a
size that is not desired. That is no longer best practice, but can still be done.
A more convenient way to manipulate box size is by using the border-box value for
box-sizing. This specifically tells the browser not to increase the width of
the box, no matter what the border and padding are set to.

http://learnlayout.com/
and notes taken-->
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
<!-- A relative position behaves very similarly to a static position (which means no
position at all). That is, unless you add properties to the relative positioned element.
Adjusting the properties of this element causes it to be moved away from the original
position. The content will also not be adjusted.
Absolute positioning will place an element relative to it's nearest positioned
ancestor. If said ancestor do not not exist, the element will move with the browser
while a user is scrolling though the page.

http://learnlayout.com/
and notes taken-->
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!--
1. Forgetting to format a site so that it looks the same on all devices. This can be done with media queries. Also, forgetting to add -webkit- and -moz- prefixes can sometimes make certain parts of a website not show up or show up incorrectly for different browsers. You have to style so that it is compatible for as many browsers possible.
2. Neglecting to clear-fix after floating/clearing something can totally ruin how a site looks depending on the way that it is styled.
3. Another mistake could be adding an absolute element if it does not have any ancestor elements. This could cause a whole section of your site to move while a user is scrolling/posistion it relative to the body. This could be tricky if it is not what you intended to happen. -->
```
