# HTML CSS Layout Study

## Reading

Read [Learn CSS Layout](http://learnlayout.com). This should take about 45
 minutes to an hour.

## Questions

Submit a pull request with responses to the following questions

What is the different options for `box-sizing`? Explain the differences between
 them. 

```md
Box-sizing was created to remedy the problem of an element's border and padding stretching out the element beyond its specified width. When you add box-sizing: border-box to an elementh this will prevent that padding and border from increasing the element's overall size, giving it the same look and as an element that didn't have any padding or border. It's best practice to include the -webkit and -moz prefixes on this property since its so new.

```

In your own words, explain the difference between relative and absolute
 positioning.

```md

A relatively0positioned element will leave its original position, and leave a gap behind if it's given additional positioning properties such as top or right. Other content will not fill this gap.

Absolute will remain 'fixed' on it's neearest positioned parent element, otherwise it will use the document body. There is no gap left behind with an abosolutely-positioned element.

```

What are three "gotchas" when working with CSS layouts? "Gotchas" are common
 mistakes that are easy to make, even if you know better.

```md
1. Using width instead of max-width to accommodate smaller screen sizes.
2. Clearing floats
3. Forgetting to include the prefixes for older browswers on a property or double checking to ensure that your code will work in older browsers, or if there's additional work involved to accommodate.
```
