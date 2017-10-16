---
title: Multi Column
prev: /post/gradients
next: /post/transforms
weight: 7
---


<p>CSS columns you can create a print-inspired layout  that can adapt to a responsive canvas</p>

<p> There are three different ways to declare columns:</p>

<ul>
  <li>Declare column-count</li>
  <li>Declare column-width</li>
  <li>Declare both (recommended)</li>
</ul>

<h4>Browser Support:</h4>
<p>The numbers in the table specify the first browser version that fully supports the property.</p>
<p>Numbers followed by -webkit-, -moz-, or -o- specify the first version that worked with a prefix.</p>
<table>
  <thead>
    <tr>
      <th>Chrome</th>
      <th>Safari</th>
      <th>Firefox</th>
      <th>Opera</th>
      <th>Internet Explorer</th>
      <th>Android</th>
      <th>iOS</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>50.0<br/>4.0 -webkit-</td>
    <td>9.0<br/>3.1 -webkit-</td>
    <td>2.0 -moz-</td>
    <td>37.0<br/>15.0 -webkit-<br/>11.1</td>
    <td>10.0</td>
    <td>2.1</td>
    <td>3.2</td>
  </tr>
</tbody>
</table>

<p>Browsers that do not support these properties like Internet Explorer 8 or 9 (and below) will display your content in one single column.
We can provide a fallback for IE8 and the likes by detecting support for multiple columns by using Modernizr.
</p>

<h3>Need for this standard:</h3>

<p>Though there is no as such specs provided for this property it is always recommended never to use both column-count and column-width together.</p>

<h3>Negative Impact:</h3>
Using both column-count and column-width together will behave different in different browsers which will impact the look and feel of the page being rendered.
Firefox creates  columns to fill the width of the parent div; WebKit creates columns of exactly the specified column width each, leaving a large blank area to the right of the element.



<h4>Working Section:</h4>

<p>Try the below link in both firefox and chrome to see the difference!!<p>
<a href="http://codepen.io/katydecorah/pen/39ea7b0f24b5806969dc4c275461c5b1">Multi column</a>

<h4>References</h4>

https://css-tricks.com/guide-responsive-friendly-css-columns/

https://caniuse.com/#search=column

<h4>Point of Contact:</h4>

<p>Meghana Raju <a href="mailto:meraju@deloitte.com">meraju@deloitte.com</a></p>
