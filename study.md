# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
When you set box-sizing: border-box on an element, the padding and border of that element no longer increase its width. Their property values are:

content-box	Default. The width and height properties (and min/max properties) includes only the content. Border, padding, or margin are not included

border-box	The width and height properties (and min/max properties) includes content, padding and border, but not the margin

initial	Sets this property to its default value.

inherit	Inherits this property from its parent element.

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Absolute positioning allows you to remove an object from the typical flow of the document and place it at a specific point on the page. When something has absolute positioning applied, it neither affects nor is affected by other elements in the normal flow of the page
The reason for absolute positioning is so we can position an item precisely where we want it. We do this with the top, bottom, left and right CSS properties.
Relative positioning works similarly to absolute positioning in that you can use top, bottom, left and right to scoot an object to a specific point on the page. The primary difference is the origin or starting point for the element.
The item is moved “relative” to its starting position. This is helpful for when you want to slightly tweak an object’s position. Relative positioning will allow you to tweak an element’s position relative to its normal starting point

Source:
https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning

```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Validate that your approach works on all browsers
2. Forgetting to use the clear property
3. Not using the clearfix hack
4. 
```
