# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
You can use the originl method of adding the elements of the box (width, padding, etc) around the box but this makes it so you need to add the numbers to find the total box size. This has been updated by adding the box-sizing feature that allows the elements to be subtractive (width, padding, etc reduce the interior space), this makes it so you can easilly match the size of boxes without having to calculate the sizes, woo!
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Items that are positioned with relative behave like static elements and content will not be adjusted to fill the gaps, elements that are positioned with absolute behave like fixed, they do not leave gaps where they would have been positioned and their position can be based on the location of another element.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
A big one to remember is clearing after using floats, I've already run into issues dealing with them. It is also very important to make sure that the size of elements doesn't end up being larger than their containing boxes, this is common with nav bars and images. A third item is having boxes scale to a smaller size than their content, this can make it so the content is not visible when the window is smaller than a certain size.
```
