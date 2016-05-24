Instructions
------------

1. Read [Learn CSS Layout](http://learnlayout.com). This should take about 45 minutes to an hour.
1. Submit a pull request with responses to the following questions:
    * What is the different options for `box-sizing`? Explain the differences between them.
    Sizing of elements with the default 'box-sizing' property of content-box can produce differences in actual element width despite setting widths to the same value. Without the 'box-sizing' property set to 'box-border' you will get a wider box if you set padding & border. With 'box-sizing' set to 'box-border' you can maintain the same absolute width for all items regardless of padding & border settings.
    * In your own words, explain the difference between relative and absolute positioning.
    Relative positioning sets the position of an element relative to its normal position (where it would show up if it was set to position:static) using the top right bottom & left properties.
    Absolute positioning, on the other hand, is set relative to the closest previous element that is positioned (ie not static.)
    * What are three "gotchas" when working with CSS layouts? "Gotchas" are common mistakes that are easy to make, even if you know better.
    1. Setting width rather than max-width can cause problems when the screen is smaller than the width set.
    2. Not setting box-sizing to box-border will cause elements meant to be the same width to show up as different sizes because of padding & border properties.
    3. Not using clearfix can cause floated images that are taller than their containers to flow outside the container.
