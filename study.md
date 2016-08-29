# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
-manually adjusting the box and border size with margin, padding and
border-width. This requires calculatons be made on the exact size of the element.

-applying box-sizing: border-box on an element. The element's width is not
increaced with its padding and border.

--applying box-sizing: border-box to the entire page. All elements will no longer
increace in width when padding and border are modified.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
In a default state relative positioning is the same as static positioning-
the element is not positioned. Relative positioning allows the element to be
adjusted with top, left, bottom and right properties.

Absolut positioning is also similar to static, but the element is positioned
relative to its nearest ancestor element. If an ancestor doesn't exist,
the element is postitoned relative to the document body and moves with
page scrolling.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Not clearing after floating an element on top of another.
Setting a 'width' instead of 'max-width', resulting in poor mobile experience.
Not adding -webkit- and -moz- for newer CSS features.
```
