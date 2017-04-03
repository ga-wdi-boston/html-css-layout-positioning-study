# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
You could create a box using either 'width', 'max-width', 'margin', 'padding' or 'box-sizing' or more than one of these combined. Max-width will set the maximum space a box can occupy in a page, but will stretch in case the page displayed gets stretched by the user. Width, however, will remain still, making it uncomfortable for the user to see. Padding can make a box bigger, but using the box-sizing element, the developer will make it keep the wanted size.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
In relative positions, you can adjust where the element will be on the page, using margin on top, right, bottom and left sides. Absolute position will be fixed, but positioned according to its parent. In other words, they will be positioned in a fixed way, but relative to its parent.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I'm not sure, but here is my guess:
  - Adjusting block elements to fit every screen, regardless the browser;
  - Making your style available in every browser (even the older ones);
  - Using adjustable arguments, instead of fixed ones, like '%' vs 'px'
```
