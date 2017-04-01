# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
border-box: includes content, padding and border but not margin.
content-box:  width and height  are measured including only content, not the padding, border or margin.
initial: sets property to default value.
inherit: inherits property from parent element.
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
absolute positioning allows us to put an element where we want it. We can do this with
the top, bottom, left and right positioning properties.

relative positioning is similar to absolute. It is "relative" to either page margins of the document or relevant container (such as a div or header etc.)
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1.) Using floats but then not clearing them.
2.) Not letting their parents contain them properly.
3.) Not understanding the concept of "cascading" or top to bottom execution
```
