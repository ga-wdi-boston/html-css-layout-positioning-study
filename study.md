# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
width: the first layer which is the width from the text.
padding: between the width and the border. this makes the box bigger.
border: when colored and such it will be visible and will show what humans call a box.
margin: outside the border, kinda like it's personal space if you will... which can move the box away or closer to others.```

In your own words, explain the difference between relative and absolute
 positioning.

```md
relative is independently positioned using the whole page as it's placement. Aboslute's properties will be from the closest last positioned element (not a static one though as that is not considered positioned).```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. recognizing when to use clearfix
2. forgeting that peolpe experience the web through mobiles. So one might forget to use min-width and max-width.
3. using display: inline-block; will hava an effect called 'hasLayout' for IE6 and IE7 support.'```
