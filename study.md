# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md

Border-box: makes it so the padding and border no longer increase the max width
of a box. This avoids the need for manually keeping track of and subtracting out
the padding and border from the max-width of a box.  Margin is not accounted for
however.

Content-box: This is the default, as CSS was before box-sizing came along. Width/height does not account for padding, border, or margin.

Padding-box: Deprecated, and only originally implemented in Firefox.  This
included the padding with the content for height/width calculations but did not
include border or margin.
```

In your own words, explain the difference between relative and absolute
 positioning.

```md
Absolute positioning places elements with respect to the most recent non-static
containier, so 200px would be measured from the edge of the nearest parent
element that has been positioned.
Relative positioning places elements with respect to the browser window (the
viewport).  Adjusting top, right, bottom left will place the element relative to
its default static position.
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
Clear-fix issues/forgetting to do it (this happened to me a lot in Fundamentals/Dash)

Forgetting which properties are not supported by default and forgetting to add
their prefixes (moz / webkit)/Deciding if you want to bother supporting
Microsoft's browsers.

Getting mixed up with DOM element hierarchy - this could include not setting a
selector to the element you intended because you used repetitive names and
didn't call with respect to the element's container(s), or it could be
accidentally overriding an earlier selector by mistake.
```
