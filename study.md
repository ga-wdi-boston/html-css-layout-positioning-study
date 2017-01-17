# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
<!-- Typically elements come under the 'box model', which adjusts width for each aspect of an element in its appropriate layer... this means that two elements with the same width can look different on a screen if one of the element has different padding, border, or margins specified... However, when you set a box-size to border-box, it stops the element from increasing in width, making everything cleaner and more consistent.-->
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
<!--Relative positioning is basically customized static positioning (therefore making it positioned instead of not-positioned). It behaves similarly to static positioning in that it will move with the page when you scroll.
Absolute positioning, on the other hand, is basically fixing an element to another element, so it travels (or doesn't travel) with the element it's fixed to... if it doesn't have something to attach itself to, it fixes itself to the browser and behaves like a fixed positioned element. -->
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!-- 1- using too many divs/classes/getting disorganized
    2- using inline style elements that override everything else
    3- forgetting to clear or clearfix after a float-->
```
