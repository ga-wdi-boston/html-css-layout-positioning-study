# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
content-box: (default) this option allows you to manually set the borders
and padding of an element
border-box: this makes it so an element's padding and border don't increase its width

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Relative position allows you to position the element away from its normal
position on the document, whereas it seems absoulute positioning fixes itself
on declared ancestors/parents when assigned. If none are assigned, it is
positioned in the doc body.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I would say it would be a common mistake is regarding the responsive design. I
think it could be fairly easy to forget to think about a certain device that
would be viewing your content. Another would be to not account for different
browsers and neglect testing/adding -moz/-webkit to necessary classes. Finally
it could be common for redundency, or DRY violations, wherein the developer
does not reuse code whereever possible.```
