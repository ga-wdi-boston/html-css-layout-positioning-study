# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
box-sizing property has default value of 'content-box', but can be set to border-box.  The difference:  With 'content-box', if you set width of a div to 100px with padding of 45px, and border of 5px, the width of your div will actually take up 150px on screen.  This is annoying if you only wanted your div to have width of 100px.  Setting box-sizing property to 'border-box' gets the browser to take content, padding, and border into account when setting width = 100px to make sure total width of your div stays at 100px
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning allows you to use properties (top, right, left, and bottom) to position an element relative to the sides of the viewport.  Absoulte positioning is similar, except when you use top, right, left and bottom, you are positioning the element relative to the nearest positioned ancester.  I used absolute during wdi-fundamentals to keep the footer at the bottom of the body div, even as the bottom of body was pushed off screen (as when resizing window). I was able to do this because I set the body to position: relative, resulting in body being the nearest positioned ancestor to footer.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. I think the largest gotcha is over-complicating your css through trial and error, forgetting to remove unnecessary css, leaving a whole bunch of messy, duplicate css properties.
2. Forgetting to clear after float
3. forgetting to position ancester element when using position: absolute
```
