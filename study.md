# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
<!-- if you use the traditional box model, you might not get the expected width and height, depending on the border and padding.  the box-sizing method eliminates any additional math or guess work and allows you to get the expected width and height each time by adding the box-sizing: border-box property to your CSS. -->
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
<!-- a relative positioned element will position itself like a static element and fit itself to the web page's body/window.  If you add padding or margins or properties to move it, the relative element will move away from where it would have been, like a static element.  If you code left 20px, then the element will move 20 pixels to the right and will take up that space.  nothing will fill in the gaps ie no text will be floated/wrapped into the hole.

absolute positioning will adopt the nearest positioned ancestor, and almost think of that as the main body/window of the web page (intead of the document window) and then position itself accordingly inside of that window/element.     -->
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
<!-- 1) Not linking the css properly to html properly (might be one, but read first before anwering)
    2) using width instead of max-width.  max-width will react better to adjusting the size of a page.  if you use width, it won't adjust.
    3) being aware of older browsers or newer techniques that haven't been adopted yet and making sure you add the correct code so that your CSS won't look bad in those browsers. -->
```
