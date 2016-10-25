# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
box-sizing can be used to change the default box-model within css.  There are a few  options for it's use, including border-box (which includes the padding and border), content box, which is the default padding, border, and margin.  Not all options are recognized by all browsers.```

In your own words, explain the difference between relative and absolute
 positioning.

```md
When something had absolute applied to its positioning, it does not affect, nor is it affected by, the other elements on the page.  This is good for layout because that object can be placed wherever it needs to be placed by simply using top, bottom, left and center properties relative to the page itself.

When something is relatively position, that something depends upon the positioning of other elements within the page (it will wrap or buffer its position and will not overlap in any way)
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1: Not declaring a !DOCTYPE, this will screw everything up and is an easy fix
2: Not correcting errors in the html even when errors in the CSS are cleared, this may cause styling to work incorrectly
3: Using inline instead of CSS, gets messy fast
```
