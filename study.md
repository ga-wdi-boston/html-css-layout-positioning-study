# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
I used the CSS Layout Tutorial to answer these questions, as it's the most up-to-date resource I have encountered since learning CSS. There were a lot of idea in here that I hadn't been exposed to yet, like Box-Sizing and Flexbox.

The conventional method for sizing elements requires developers to do a little math if the desired outcome is for two elements to have equal widths/heights. The height/width designated for an element does NOT take into account border/padding settings. This means that two elements with width: 500px could look to be different sizes if one element has borders/padding set to a value and the other does not. The element with a border/padding value will look larger. To make the two elements equal, developers need to do some basic math to subtract border/padding from the element.

Box-Sizing takes care of this issue. Setting 'box sizing: border-box' indicates that the true size of the element should not be increased by the combined width of the border/padding. These widths are applied inside the set width/height of the element, effectively making the element sizes the same. This is a much more intuitive way of sizing elements.

```

## Relative vs Absolute Positioning

A relatively positioned element will be adjusted away from it's normal, static position if the appropriate proerties are set to adjust it.

An absolutely position element behaves like a relative element, but it is positioned according to its nearest positioned ancester rather than the normal viewport static position.

```md
<!-- your answer here -->
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. Placing an image in an element and having that image overflow its container. The clarfix hack is needed to address this.

2. Forgetting to apply clear to an element that should display below other floated elements. The result is an overlap of the elements since floated elements are pulled out of the document flow.

3. Setting elements to fixed width. When viewed from a smaller device, or when the window is resized, the element has an ugly scroll bar to ensure you can still read the content contained within. Not a nice look.
```
