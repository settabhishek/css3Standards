---
title: User interface
prev: /post/transitions
next: /post/border
weight: 9
---

<p>CSS3 brings some great new properties relating to resizing elements, cursors, outlining, box layout and more. Here we will be focusing on three of the most significant user interface enhancements:</p>
<ul>
<li>resize</li>
<table>
<thead>
  <tr>
    <th>Property</th>
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
    <td>resize</td>
    <td>4.0</td>
    <td>4.0</td>
    <td>5.0<br/>4.0 -moz-</td>
    <td>15.0</td>
    <td>Not supported</td>
    <td>unknown</td>
    <td>unknown</td>
  </tr>
</tbody>
</table>
<li>box-sizing</li>
<table>
<thead>
  <tr>
    <th>Property</th>
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
  <td>box-sizing</td>
  <td>10.0<br/>4.0 -webkit-</td>
  <td>5.1<br/>3.1 -webkit-</td>
  <td>29.0<br/>2.0 -moz-</td>
  <td>9.5</td>
  <td>8.0</td>
  <td>2.1 -webkit-</td>
  <td>3.2</td>
  </tr>
</tbody>
</table>
<li>outline-offset</li>
<table>
<thead>
  <tr>
    <th>Property</th>
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
    <td>outline-offset</td>
    <td>4.0</td>
    <td>4.0</td>
    <td>5.0<br/>4.0 -moz-</td>
    <td>9.5</td>
    <td>Not supported</td>
    <td>unknown</td>
    <td>unknown</td>
  </tr>
</tbody>
</table>
</ul>
<p>The following table shows the default values of the user interface properties:</p>

<table>
  <thead>
    <tr>
      <th>Properties</th>
      <th>Default value</th>
      <th>Property Values</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>resize</td>
    <td>none</td>
    <td>none|both|horizontal|vertical|initial|inherit;</td>
  </tr>
  <tr>
    <td>box-sizing</td>
    <td>content-box</td>
    <td>content-box|border-box|initial|inherit;</td>
  </tr>
    <tr>
    <td>outline-offset</td>
    <td>0</td>
    <td>length|initial|inherit;</td>
  </tr>
</tbody>
</table>

<h4>Browser Support:</h4>
<p>The numbers in the table specify the first browser version that fully supports the property.</p>
<p>Numbers followed by -webkit-, -moz-, or -o- specify the first version that worked with a prefix.</p>
<table>
<thead>
  <tr>
    <th>Property</th>
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
    <td>resize</td>
    <td>4.0</td>
    <td>4.0</td>
    <td>5.0<br/>4.0 -moz-</td>
    <td>15.0</td>
    <td>Not supported</td>
    <td>unknown</td>
    <td>unknown</td>
  </tr>
  <tr>
    <td>outline-offset</td>
    <td>4.0</td>
    <td>4.0</td>
    <td>5.0<br/>4.0 -moz-</td>
    <td>9.5</td>
    <td>Not supported</td>
    <td>unknown</td>
    <td>unknown</td>
  </tr>
  <tr>
  <td>box-sizing</td>
  <td>10.0<br/>4.0 -webkit-</td>
  <td>5.1<br/>3.1 -webkit-</td>
  <td>29.0<br/>2.0 -moz-</td>
  <td>9.5</td>
  <td>8.0</td>
  <td>2.1 -webkit-</td>
  <td>3.2</td>
  </tr>
</tbody>
</table>


<h3>Resize:</h3>
<p>The resize property specifies whether or not an element should be resizable by the user.</p>

<h4>Need for this standard:</h4>
<p>The purpose of the resize property is to also allow control over the appearance and function of the resizing mechanism on the element.</p>
<p><strong><i>Note:</i></strong> The resizing mechanism is NOT the same as the scrolling mechanism. The scrolling mechanism allows the user to determine which portion of the contents of an element is shown. The resizing mechanism allows the user to determine the size of the element.</p>
<p>The resize property applies to elements whose computed ‘overflow’ value is something other than ‘visible’.</p>

<h4>Negative Impact:</h4>
<p>The effect of the resize property on generated content is undefined. Implementations should not apply the resize property to generated content.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/xovezey/1">Using resize</a><br>
<a href= "https://jsbin.com/cesijic/3">Effect of the resize property on generated content</a>

<h3>Box-sizing:</h3>
<p>The CSS3 box-sizing property allows us to include the padding and border in an element's total width and height. The box sizing aspect allows you to define certain elements to fit an area in a certain way. For example, if we want two bordered boxes side by side, it can be achieved by setting box-sizing to ‘border-box’. This forces the browser to render the box with the specified width and height, and place the border and padding inside the box.</p>
<p>By default, the width and height of an element is calculated like this:</p>
<p>width + padding + border = actual width of an element</p>
<p>height + padding + border = actual height of an element</p>
<p>This means that when we set width/height of an element it will appear bigger that the actual size we defined. The CSS3 box-sizing property allows us to include the padding and border in an element's total width and height.</p>
<p>We can include the padding and border in the width/height defined without increasing the required size of the element using <i>‘box-sizing: border-box’</i>.</p>




<h4>Negative Impact:</h4>
<p>It is advised to use this property and define its value, as most of the libraries and browser may or may not define its value. In both the cases it will take the default value and again the designer might not get the desired output.</p>

<h4>Positive Impact:</h4>
<p>For a long time web developers have specified a smaller width value than they wanted, because they had to subtract out the padding and borders. The CSS3 box-sizing property allows us to include the padding and border in an element's total width and height there by allowing us to give values as required.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/dunafux/3">Box-Sizing</a>

<h3>Outline offset:</h3>
<p>CSS3 includes the facility to offset the outline away from the element – as the value is defined.</p>
<p>Outlines differs from a border in two ways:</p>
    <ul>
        <li>Outlines do not take up space</li>
        <li>Outlines may be non-rectangular</li>
    </ul>
<h4>Need for this standard:</h4>
<p>The outline-offset is such property of the CSS3 User Interface, which can be used to define the space between the element's border and its outline. By default, the outline is drawn starting just outside the border edge.</p>
<p>The space will be transparent (the parent will determine the background).</p>
<p>Negative values must cause the outline to shrink into the border box.</p>

<h4>Negative Impact:</h4>
<p>This property is not supported in Internet Explorer, so if designed in some other browser, your design may break in IE.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/kisunay/1">Outline-offset</a>

<h4>References:</h4>

https://www.w3.org/TR/css-ui-3/#propdef-box-sizing

http://www.html5andcss3.org/css3userinterface.php

http://caniuse.com/#search=resize

http://www.w3schools.com/css/css3_user_interface.asp

https://drafts.csswg.org/css-ui-3/#outline-offset

<h4>Point of Contact:</h4>

<p>Minu Kumari <a href="mailto:minkumari@deloitte.com">minkumari@deloitte.com</a></p>
