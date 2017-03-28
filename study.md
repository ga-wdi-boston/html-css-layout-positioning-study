# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Some options include 'content-box', 'border-box', and 'padding box'.  With content-box, the width and height properties are measured by only including the content.  Padding, border, and margin are excluded.

With border-box, the content, padding, and border are included, but the margin is not included.  It is of must use when you may not know in advance what the margin will be.

With padding-box, the width and heigh properties include the content and padding, but not the border or margin.

Sources:
https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
http://stackoverflow.com/questions/12195707/css3-box-sizing-property
https://css-tricks.com/box-sizing/


```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Since every element on a web page is a block, you can set a width and height and the element will adhere to that.  The default position for every element is static.  However, relative and absolute position are options that can be applied based on your wants and needs.

When relative positioning is used, an objects position will be impacted relative to itself, or relative to its normal position.  Adding top, right, bottom, or left properties will move the element from where it was originally placed.

With absolute positioning, page elements are removed from the flow of the document can be placed exactly where you want them to display on the page.  An element with absolute positioning is not affected by other elements, nor does it affect other elements itself.  The elements are positioned in relation to the parent element or browser window.  This means that the element will display in the location specified even if another element is already displaying in that same location.

Sources: https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/
https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning
http://cssreset.com/understanding-css-relative-and-absolute-positioning-explained/
http://learn.shayhowe.com/advanced-html-css/detailed-css-positioning/
http://www.tutorialrepublic.com/css-tutorial/css-position.php

```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
While there are likely many "gotchas", the three that I will focus on are as follows.

1.) Declaring color names instead of using rgb or hexadecimal.  For example, declaing the color "red" instead of applying a red rgb or hexadecimal value.  The color "red" may be rendered differently from one browser to another, but rgb and hexadecimal values will apply more consistency across browsers.

2.) Not accounting for browser compatibility.  Different browsers support CSS differently.  Something that is supported by Chrome and Firefox may not be supported by an older version of IE.  A developer should check his or her CSS across the many different browsers to account for any differences in rendering, and apply any tweaks that may be needed to make the display as uniform as possible.

3.) Overuse of IDs.  These should only be used when truly necessary.  IDs are more specific than classes.  When a class and ID are in conflict, the IDs properties will be applied.  This can be problematic in maintaining a webpage, as changing he style would require the developer to account for and update the many differnet IDs that could be present in the CSS.  By using classes instead of IDs, maintenance is made easier, as a few classes can be updated to make more sweeping style changines.

Sources: http://sixrevisions.com/css/12-common-css-mistakes-web-developers-make/
https://code.tutsplus.com/articles/are-you-making-these-10-css-mistakes--net-1692
http://www.creativebloq.com/css3/avoid-css-mistakes-10135080
```
