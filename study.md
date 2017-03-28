# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
Not sure the context of the question.  answer could be:
1. box-sizing: content-box which references the box of the content only, not the padding, border or margin
2. box-sizing: border-box which includes the content, padding and border, but not the margin

or you could be asking for the prefixes needed to support different browsers
-webkit-box-sizing: border-box = for safari, chrome
   -moz-box-sizing: border-box = firefox
        box-sizing: border-box = eventually will be supported by all browsers
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
position defauls to static or not positioned
relative will change the position away from normal with other coordinates such as top right bottom left
absolute  will change position relative to the nearest positioned
A positioned element is anything but static.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
Not exactly sure about the question.  Some mistakes could be:
1. Not coding for the size of the browser.   Media queries help correct that.
2. when using float ant the image is taller than the text.   Clearfix corrects this.
3. Making sure that our code is supported by all browsers.  Sometimes need the '-webkit-' (for safari or chrome) or '-moz-'(for firefox) prefixes to call on supported styles.

```
