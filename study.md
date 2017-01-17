# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
'box-sizing' is a new CSS property.  Prior to this, an element with padding would add the amount of padding to the width of the element, making it wider than intended.  using the 'box-sizing' property of 'border-box' locks the width of the element to the stated width.  If there is padding, the width is adjusted so that visually it looks like the intended width.  In addition to 'box-sizing', '-moz-box-sizing' and '-webkit-box-sizing' should be used to ensure it will work on all browsers.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
A static element is said to be not positioned.  A relative element is positioned, even though it looks like a static element until other properties are added.  An absolute element is positioned relative to its parent.  Instead of positioning with regard to the entire document, it will position itself inside of the preceding element.  This is the case unless the preceding element is fixed positioned, in which case the following absolute element would position relative to the entire document.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1)  Floated images can spill outside of their containing element.  This can be fixed with the 'clearfix hack'.
2) When the page is resized to be very small, the css can start to get pretty ugly.  This can be fixed by using percentages as widths instead of pixel values.
3) If an element is floated, it can sometimes appear to overlap with the following element.  This can be avoided by adding a 'clear' property to clear elements floated to the left or right.
```
