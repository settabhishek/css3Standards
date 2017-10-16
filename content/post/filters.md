---
title: Filters
prev: /post/drop-shadow
next: /post/flexiblebox
weight: 4
---
<p>CSS Filters are a powerful tool that authors can use to achieve varying visual effects (sort of like Photoshop filters for the browser). The CSS filter property provides access to effects like blur or color shifting on an element’s rendering before the element is displayed. Filters are commonly used to adjust the rendering of an image, a background, or a border.</p>


<h3>The different Filter Functions are :</h3>

<table>
<tr>
  <td>blur(px)</td>
  <td>Applies a blur effect to the image. A larger value will create more blur.</td>
  </tr>
  <tr>
  <td>brightness(%)</td>
  <td>Adjusts the brightness of the image.</td>
  </tr>
  <tr>
  <td>contrast(%)</td>
  <td>Adjusts the contrast of the image.</td>
  </tr>
  <tr>
  <td>drop-shadow(h-shadow v-shadow blur spread color)</td>
  <td>Applies a drop shadow effect to the image. </td>
  </tr>
  <tr>
  <td>grayscale(%)</td>
  <td>Converts the image to grayscale. </td>
  </tr>
  <tr>
  <td>hue-rotate(deg)</td>
  <td>Applies a hue rotation on the image.</td>
  </tr>
  <tr>
  <td>invert(%)</td>
  <td>Inverts the samples in the image.</td>
  </tr>
  <tr>
  <td>opacity(%)</td>
  <td>Sets the opacity level for the image.</td>
  </tr>
  <tr>
  <td>saturate(%)</td>
  <td>Saturates the image.</td>
  </tr>
  <tr>
  <td>sepia(%)</td>
  <td>Converts the image to sepia.</td>
  </tr>
  <tr>
  <td>url()</td>
  <td>The url() function takes the location of an XML file that specifies an SVG filter, and may include an anchor to a specific filter element.</td>
  </tr>
</table>

<h4>Syntax :</h4>
<span class="prop">filter: none | blur() | brightness() | contrast() | drop-shadow() | grayscale() | invert() | opacity() | saturate() sepia() | url();</span>

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
    <td>53.0<br/>18.0 -webkit-</td>
    <td>9.1<br/>6.0 -webkit-</td>
    <td>35.0</td>
    <td>40.0<br/>15.0 -webkit-</td>
    <td>13.0</td>
    <td>4.4 (-webkit-)</td>
    <td>6 (-webkit-)</td>
  </tr>
</tbody>
</table>

<h3>Need for this standard:</h3>

<p>The filter property used for graphical effects like blurring, sharpening, or color shifting an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders</p>

<h3>Negative Impact:</h3>
You may combine any number of functions to manipulate the rendering, but order still matters (i.e., using grayscale() after sepia() will result in completely gray output).


<h4>Working Section:</h4>

<a href="https://jsbin.com/toquqin/edit?html,output">All Filters</a>

<h4>References:</h4>
<a href="http://www.w3schools.com/cssref/css3_pr_filter.asp">http://www.w3schools.com/cssref/css3_pr_filter.asp</a><br>
<a href="https://css-tricks.com/almanac/properties/f/filter/">https://css-tricks.com/almanac/properties/f/filter/</a>

<h4>Point of Contact:</h4>

<p>Sahil Kumar <a href="mailto:sahikumar@deloitte.com">sahikumar@deloitte.com</a></p>
