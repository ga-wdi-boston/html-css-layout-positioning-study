Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    * In your own words, explain the difference between relative and absolute positioning.
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

box-sizing options (from [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)): 1.) content-box: width and height properties are measured only with respect to the content, meaning that a developer or designer needs to add the padding, margin, and border widths to the specified box width and height in order to compute the full box dimensions and 2.) border-box makes things a bit simple by having the width and height properties of an element include the content, padding, and border. The margin is not taken into account whne specifying the width and height.

Relative versus absolute positioning: relative positioning moves an element relative to its normal position, e.g., if we have three elements that would normally be positioned as
1
2
3
if we set element 2 to relative and bottom: -50px (not exact), we might end up with
1
(gap stays here)
3
2
The relatively positioned element also moves along with the page.
Absolute positioning sets the position of an element relative to the nearest positioned, i.e., not static, element. For instance, if element1 was positioned releatively, we could tell element2 to be positioned absolutely to the top and right of element1, looking something like this:
        element2
element1
These descriptions were based on the Bocoup positioning tutorial [BoCoup Layout](http://learnlayout.com/position.html)

css "gotchas":

1. redundant properties, i.e., adding properties that area already covered by another selector. [Six Revisions](http://sixrevisions.com/css/12-common-css-mistakes-web-developers-make/)
2. not providing fallbacks, e.g., for rgba or font-families (since not all users have the same fonts!) [Six Revisions](http://sixrevisions.com/css/12-common-css-mistakes-web-developers-make/)
3. ignoring validators that catch errors, e.g., incorrect declarations and lack of fallbacks. [Web Design Ledger](http://webdesignledger.com/the-most-common-html-and-css-mistakes-to-avoid/) and [Pxyleyes](http://www.pxleyes.com/blog/2010/03/8-common-css-mistakes-and-how-to-fix-them/)
