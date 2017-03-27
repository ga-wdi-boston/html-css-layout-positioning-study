# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
The different options in box-sizing are different methods of defining the height and width of box objects in CSS.
Based on the box model, the dimensions of an object depends on the content, padding, border, and margin.
The box sizing options (especially border box) allow you to easily determine dimensions of objects without complex calculations.

1) content box - height and width of the box only refers to the content when it is applied.
Margin, borders,and padding must be accounted for.
2) border box - height and width applies to the total demensions of content, padding, and border.
Margin must be accounted for.
3) padding box - height and width applies to the total dimensions of content and padding.  You must account for margins and borders when positioning.  This is a legacy option in Firefox

https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Absolute position is a way to posiition a box object in an absolute place on the webpage.  It will overlap any items
on the page that occupy that same location and it is taken away from the normal flow of the document. The position is determined relative to the browser window.

Relative positioning allows you to position an item in a webpage relative to it's starting position. Usually this
corresponds to the its position in the document flow. When moved it seems to still occupies the regular position, it took up and the objects around it still act like it is there.

https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1)  Using the appropriate type of display, positioning and clearing seems to be difficult
2)  Ensuring the dimensions of your box elements (width and height) is appropriate when taking
    into account margin, padding or borders.
3)  Clearfixes - when an image overflows its containers.
```
