# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
According to the Mozilla Development Network, the main options for the box-sizing property are: content-box, and border-box. The content-box value is the default CSS setting. This means that the height and width of the element only includes the content. This means that the padding, border, and margin can actually make the element appear wider that the width and height properties.

Constrastingly, the border-box value makes the height and width properties include the padding and border along with the content.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning means that the elements position can be altered away from its normal position by top, right, bottom, and left. It moves the object the specified amount away from its default CSS positioning.

Constrastingly, absolute positions the element relative to its nearest anscestor (or if no anscestors, then the document body itself) rather than just its normal position.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
For this, I used this website:  (https://code.tutsplus.com/articles/are-you-making-these-10-css-mistakes--net-1692/)
1) One of the 'gotcha' mistakes that you can make is not checking browser compatability. For example, certain CSS properties may not work in various browsers (or versions of browsers). This was even mentioned in this study's reading. For example, CSS columns apparently don't work through IE9 or Opera Mini. If this occurs, your layout will not appear the way you want.

2) Another common mistake is not considering various screen sizes. When you set width or other similar sizing properties, this may cause issues with smaller screens that make the layout not look as good.

3) Finally, you can run into mistakes with floating, clearing, and clearfix. For example, if you float an image that is larger than the element holding it then it will spill outside the container. You can fix this by using clearfix.

```
