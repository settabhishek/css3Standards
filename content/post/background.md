---
title: Background
prev: /post/border
weight: 12
---


<p>CSS3 Background has about 8 properties which is all included in the shorthand ‘background’.
The Background shorthand takes the following property values in the same order:</p>

<p> background: background-image | background-position / background-size | background-repeat | background-attachment | background-origin | background-clip | background-color</p>

<p><strong>Ex:</strong>  <span class="prop">background: url(myImg.jpg) bottom 20px right 20px / 200px 100px no-repeat fixed red;</span><p>

The different CSS3 Background properties are:

<ul>
  <li>background-attachment</li>
  <li>background-color</li>
  <li>background-image</li>
  <li>background-position</li>
  <li>background-position-x</li>
  <li>background-position-y</li>
  <li>background-repeat</li>
  <li>background-clip</li>
  <li>background-origin</li>
  <li>background-size</li>
  <li>background-inline-policy</li>
</ul>

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
    <td>background-image (with multiple backgrounds)</td>
    <td>4.0</td>
    <td>3.1</td>
    <td>3.6</td>
    <td>11.5</td>
    <td>9.0</td>
    <td>2.2</td>
    <td>4</td>
  </tr>
  <tr>
    <td>background-size</td>
    <td>4.0<br/>1.0 -webkit-</td>
    <td>4.1<br/>3.0 -webkit-</td>
    <td>4.0<br/>3.6 -moz-</td>
    <td>10.5<br/>10.0 -o-</td>
    <td>9.0</td>
    <td>2.3</td>
    <td>4.0</td>
  </tr>
  <tr>
    <td>background-origin</td>
    <td>1.0</td>
    <td>3.0</td>
    <td>4.0</td>
    <td>10.5</td>
    <td>9.0</td>
    <td>2.2</td>
    <td>4</td>
  </tr>
  <tr>
    <td>background-clip</td>
    <td>4.0</td>
    <td>3.0</td>
    <td>4.0</td>
    <td>10.5</td>
    <td>9.0</td>
    <td>2.2</td>
    <td>4</td>
  </tr>
</tbody>
</table>

<h3>Need for this standard:</h3>

<p>It is always advisable to use the above properties in specific instead of using the shorthand as not declaring few properties explicitly will set them to their default values which might take away the intention of the whole property.</p>
<p>We can specify multiple background images by comma separating them. This enables to increase the scope of the background property.</p>

<h3>Negative Impact:</h3>
If you use the background shorthand and fail to declare any of the individual properties that make up the shorthand, those properties will revert to their default values listed below:

<ul>
<li>background-color: transparent</li>
<li>background-position: 0% 0%</li>
<li>background-size: auto auto</li>
<li>background-repeat: repeat repeat</li>
<li>background-clip: border-box</li>
<li>background-origin: padding-box</li>
<li>background-attachment: scroll</li>
<li>background-image: none</li>
</ul>


<h4>Working Section:</h4>

<a href="https://jsbin.com/johariyina/edit?html,output">Background Shorthand</a>

<a href= "https://jsbin.com/xaseyahade/edit?html,output">Background Properties</a>

<h4>References:</h4>

http://www.standardista.com/css3/css3-background-properties/


<h4>Point of Contact:</h4>

<p>Meghana Raju <a href="mailto:meraju@deloitte.com">meraju@deloitte.com</a></p>
