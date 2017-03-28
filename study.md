# HTML CSS Layout Study

Use your favorite search engine and the provided readings to research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your search. We ask you to write responses in your own words in order to see how you process what you've read. Please do not respond with direct quotes from source material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- Read [Learn CSS Layout](http://learnlayout.com).
  - This should take about 45 to 60 minutes

## CSS box-sizing

What are the different options for `box-sizing`? Explain the differences between them.

```md
 Content-box: box's width and height doesn't include padding border and margin.
 Renders outside of the box often causing sizing issues
 Border-box: box's width and height include padding and border but not margin
 padding-box: include content and padding, but not border or margin

```

## Relative vs Absolute Positioning

In your own words, explain the difference between relative and absolute positioning.

```md
Absolute positioning depends on the elements on the page near it to determine
where things will fall. Relative is tied to the screen itself and handles
reizing a bit better.
```

## CSS Gotchas

What are three "gotchas" when working with CSS layouts? "Gotchas" are common gimistakes that are easy to make, even if you know better.

```md
I honestly read, and re-read this material and did not see any mention of common
mistakes that stood out to me. I read it last night and did not have an answer.
I woke up to re-read the material with some caffiene and sleep...still not seeing it.
I can say that I personally found layout to be much trickier than it seems at
face value. So if I had to guess at a few mistakes folks make based on what I read...
Not using clear might be one. I could see not understanding the box-sizing
properties fully as an issue that would be common for early devs and cause some
funky looking layouts until the dev is more comfortable. And possibly misuse of
relative and absolute positioning. Honestly still a little fuzzy on what would
fall where using these and will need some practice. 
```
