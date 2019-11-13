 # css
css stand for cascading style sheet. Is a stylesheet language that is used to described the presentation of the html  document on screen, on paper or other media.
 ## css type
External stylesheet you can change the look of the entire website by changing just one file 

```
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>

An internal style sheet may be used if one single page has a unique style. 
Internal styles are defined within the <style> element, inside the <head> section of an HTML page:Example

<head>
<style>
body {
    background-color: linen;
}

h1 {
    color: maroon;
    margin-left: 40px;
}
</style>
</head>

Inline Styles
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

The example below shows how to change the color and the left margin of a <h1> element:Example

<h1 style="color:blue;margin-left:30px;">This is a heading.</h1>

 ## css selector
It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.
 ## types of selector
Element selector it select element based on the element name for instance

p{
    text-align: center;
    color: red;
}

The id selector uses the attribute of an html element to select a specific element for example

#pra1{
    text-align: center;
    color: green;
}

A class selector looks just like an element selector, but instead of using names that are tied to the names of HTML elements, you make up the name and then you prefix it with a dot (.). 
For instance:

.red { 
    text-align: center;
    color: red;
}

## Css property
CSS properties are used to apply styles to structured documents, such as those created with HTML. CSS properties are specified in the CSS standard. Each property has a set of possible values. for instance

body{
    background-color: red;
}

background-color is the property
## css value
CSS values are set against CSS Properties and reside within CSS declaration block, which is a part of the CSS rule / statement.
CSS allows following types of values : Integers and real numbers, Lengths, Percentages, URLs and URIs, Counters, Colors,
Strings, Unsupported Values.
body{
    background-color: orange;
}
```
orange is the value.
