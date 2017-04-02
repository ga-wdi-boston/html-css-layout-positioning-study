# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
content-box is the default value and deals only with the content in the container, border-box includes the content and padding .
There is also the padding-box property value but its use has been discontinued in modern browsers
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative position allows you to push or pull an element on the page without effecting the rest of the elelmens on the page, whle the absolute position can result in overlapping elements, it basically allows you to put a element anywhere you want it on the page.
http://cssreset.com/understanding-css-relative-and-absolute-positioning-explained/
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1- Not using shorthand properties creting clunky and redundent code if you can write something on one line, why waste the time and write four lines of code.
2- Using color names, this allows the browser to decide for you and not all browser have the same idea when you type blue it puts in its choice of blue.  The dev should use hexdecimal color codes as they are specific and used by all browsers.
3- Writing redundent code lie using the same properties on multiple elements when in reality you only had to add the selector to the first one you wrote and combine it with a comma.
http://sixrevisions.com/css/12-common-css-mistakes-web-developers-make/
```
