# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
1. box sizing: when you set box sizing, the padding and border of the element no longer increase its width, so the element width can be the width of the element itself
2. Moz box sizing: box sizing element to make sure that your box sizing works w/older verisons of common browsers
3. Webkit box sizing: boz sizing element to make sure that your box sizing works w/older versions of common browsers
```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
An element w/relative postioning that has declared postioning attributes, will shift its position based on the declared attributes that many pxs up, left, right, down from where it would be if you hadn't called out relative positioning in the first place. Relative position is thought of in terms of the element's position relative to itself.

  Important things to remember regarding relative positioning- does not impact other elements on the page aka push them down/up/left/right- so can cause overlapping.

 When you create an absolute element, the element will be postioned relative to its parent- if there is no such parent, the element will be relative to the page itselfs (html element)

 Important thing to remember regarding absolute positioning: If you want an absolute elment to honor the positioning of it's parent. The parent element must have "position: relative" declared.

Source: https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/
http://cssreset.com/understanding-css-relative-and-absolute-positioning-explained/
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
1. For absolute positioning, not giving the parent element relative positioning.
2. Forgetting about mediaprint aka that your site should look good across diferent sized browsers/devices
3. Putting formatting/styles directly into your html file vs adding the formatting/styles to yoru css fiel
```
