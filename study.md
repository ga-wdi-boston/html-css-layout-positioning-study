# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
There are four options for box-sizing.  First, "initial" assigns the box-sizing property to its default value.  Next, "inherit" simply takes the property from a parent element.  Content-Box is the default value.  Here, the width and height of the box only takes into account the content of the box.  Lastly, "Border-Box" allows a developer to create a box such that padding, border, and content does not affect the width of the box.  In other words, the width and height includes everything with exception to the margin.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative position places a block of content in a location relative to another block.  Using properties of top, bottom, right, and left, the element can be positionecd based on the height and width of a page.  It is important to note that when relative positioning is used, no other content can be positioned in whitespace not included in the relative element.

Absolute positioning, on the other hand, functions in terms of the positioning of an ancestor.  While the values assigned to a relative positioned element target the entire page, the positioning of an absolute positioned element will depend on an ancestor element.  Therefore, when the properties top, right, left, and bottom are included in an absolute positioned element, it is positioned in relation to this ancestor element.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Clearfix Hack - I assumed that using clear would allow the content of a following element to be positioned after an image.  However, the overflow must be set to auto in order to make this take place.

2. Inline Blocks and Floats - I was surprised to learn that inline-blocks and floats can accomplish the same goal.  However, I now recognize the value in using inline-block to avoid having to relay on clearing the following block element.

3. Browser Type - I did not anticipate the limitations with specific css properties.  For instance, I did not know that Internet Explorer was such an obstacle for developers and there was such a need to modify CSS to ensure that a website is compatible with all browsers (e.g. inline-block and clearfix)
```
