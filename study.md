# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them.

```md
webkit-box-sizing: border-box; for safari and chrome
moz-box-sizing: border-box; for firefox
box-sizing: border-box; for IE
<!-- your answer here -->
These make it so that the adjusting(increasing) of either the border or the
padding property don't make it so that the width of the element increases also.

some people like these so much that instead of doing it for each individual
element or class or id, they do it for the entire css style sheet by doing * {

}

```

In your own words, explain the difference between relative and absolute
 positioning.

```md
relative and static, when set as defaults are the same. However, when the top,
left, right, and bottom properties are given values which are not their default,
this is no longer the case and relative then behaves differently than static. Also
if there was a gap left by doing this, no other content can be adjusted to fit
there.

Absolute is an element which stays at the same location, but in relation to
another posititioned element on the page, not to the page itself. If there is no other
positioned elements it will use the page body.
<!-- your answer here -->
```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
<!-- your answer here -->

I couldn't find any documentation directly siting 'gotchas'. However the things
which the tutorial seemed to point out were:

-the clearfix hack
-float and clear
-flexbox


```
