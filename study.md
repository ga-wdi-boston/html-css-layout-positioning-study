# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
  The default value for 'box-sizing' is 'content-box', which means the width & height
  of the element includes the _content only_, and border / padding / margin are
  not included in the total width. This means that the element width can often
  end up being larger than we expect.

  Alternative, there is 'border-box', which means the width and height of the element
  is calculated including the content, padding, and border (though not the margin).
  This is helpful for when we need to precisely position elements based on their
  widths.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
  Relative positioning is similar to the default 'static' positioning, except
  that the element is moved and positioned _relative to itself_. It is moved from its location by setting the 'top/right/left/bottom' values, which moves the element in relation to where it would normally be placed.

  Absolute positioning, however, means the element is positioned based on its
  nearest ancestor that has a set position (other than static). If it has no
  positioned ancestors, it'll use the document body. This is used to place any
  element precisely where we want it on the page.

  However, absolute-positioned elements are removed from the flow of the page,
  meaning it's position does not affect other elements, nor is it affected by other
  elements. This can affect the flexibility of the site.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
  There are approximately a bajillion gotchas when working with CSS, but the
  most common ones that come to mind are:

  > remembering to use box-sizing when we are setting precise element widths to make sure they're accurate.
  > Remembering to set max-width as well as width, in case the browser window is narrower than the width of the element (and otherwise remembering to scale for browser/window size)
  > Remembering to 'reset' the CSS (if needed), so the default styles of an element don't interfere with the styling we're adding as well.
```
