# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   Read [Learn CSS Layout](http://learnlayout.com).
    -   This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
content-box - The box is created using the height/width specified, and then the padding/border are added to the box so if there if there is padding or a border, then the true height/width will be larger than initially specified

border-box - When the box is created, it will have the height/width specified *including* padding and border
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative positioning indicates that the element is within the normal flow of the document but can be adjusted left or right.

Absolute positioning means the element is not within the normal flow and is positioned within its parent element based on the properties given for left,right,top,bottom
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. A page that looks nice on a large browser can look squished on a smaller screen, even when trying to use responsive css
2. When you use floats you have to remember to "clear" the next element if you dont want it to get messed up
3. Certain browsers don't have support for all the CSS properties that we might want to use
```
