# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
The first option is to not use box-sizing which means manipulating the padding and border to compensate for the various widths. If you use 'border-box' it won't increase the width of the elment. You can also apply box-sizing to the entire css document by using a *{} tag.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Relative positioning is simlar to no positioning but it can be manipulated so elements can be pretty much anywhere on the page. If you add other properties you can shift where the relatively positioned element sits on the page. You can also set relatively positioned elements so they stay in the same place even if you scroll around in your browser.

Absolute positioning is when an element is positioned in relation to its parent element.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
You may have an image thats larger than the element it is contained within which can be resolved with a clearfix.

You may use a function that is not supported by old browsers. It is important to add webkit and moz modifiers to assist in preventing this from happening.

When using width it is easy to neglect using max width which could result in incompatibility with smaller windows and mobile users.
```
