# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
<!--

css/html clarity:  3.7
css/html comfort:  2.9

Different options for box-sizing:

Overall, my understanding is that the differences in the box models are in how the padding/borders are calculated.

    content-box:  I understand this i the default box-sizing and applys to content only and the developer needs to calculate and design the padding and border boxes.

    padding-box:height and width apply to the box's content and it's padding.  Firefox appears to be only browser that supports this.

    border-box:  height/width values apply to box's content, borders, and paddings.  this is most popular; easy to set up and adjusts to window and browsers.  the boxes, padding, borders remain proportional to each other, no matter the shape of the window.


    some sites I reviewed:
    https://css-tricks.com/almanac/properties/b/box-sizing/
    (https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
    https://css-tricks.com/box-sizing/

    -->
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
<!--

I understand relative positioning to be scooting an element around using top/bottom, left/right precisely with the starting of point of its current location while absolute positioning is setting location of an element by the location on page, not connected to any other other elements and without consideration of its current location

an additional video:  http://cssreset.com/understanding-css-relative-and-absolute-positioning-explained/-->
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!-- running out of time to finish; spent 2.5 hours on tonights homework... partly because I'm curious and partly because I forgot a comma in an array for the javascripting stuff

1) inline stylings?  (overrides styles)

2) not using a reset file leading to browser issues

3) using ids instead of classes (not understanding the cascading characteristic

http://www.pxleyes.com/blog/2010/03/8-common-css-mistakes-and-how-to-fix-them/)

http://stackoverflow.com/questions/1190953/common-mistakes-for-css-designers-to-avoid/1191386
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS-->
```
