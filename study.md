Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.

RESPONSE: box-sizing prevents additional padding and border inside a box from expanding it's actual dimensions.  when additional padding of an element inside is added, or when a border is added, when box-sizing is set to border-box, the original size of the box will not be increased

    * In your own words, explain the difference between relative and absolute positioning.

response: the biggest difference is that absolute positioning is fixed positioning to its nearest possible ancestor.  it's positioning coordinates are based off of the positioning of its parent fixed positioned element.

    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.

    1. absolute positioning is tricky in CSS
    2. box-sizing - people forget to include the border-box value for box sizing and this effectively enlargens and mis-sizes box elements on teh page
    3. the clear property allows next div after the floating divs to clear or break the trend of floating.  it ususally places the cleared element beneath the floated elements
