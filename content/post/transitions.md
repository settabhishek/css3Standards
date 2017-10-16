---
title: Transitions
prev: /post/transforms
next: /post/userinterface
weight: 8
---

<p>CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time. For example, if you change the color of an element from white to black, usually the change is instantaneous. With CSS transitions enabled, changes occur at time intervals that follow an acceleration curve, all of which can be customized.</p>


<h4>The different transition properties are:</h4>

<table>
  <tr>
  <td>transition-property</td>
  <td>The ‘transition-property’ property specifies the name of the CSS property to which the transition is applied.</td>
  </tr>
  <tr>
  <td>transition-duration</td>
  <td>The ‘transition-duration’ property defines the length of time that a transition takes.</td>
  </tr>
  <tr>
  <td>transition-timing-function</td>
  <td>The ‘transition-timing-function’ property describes how the intermediate values used during a transition will be calculated.</td>
  </tr>
  <tr>
  <td>transition-delay</td>
  <td>The ‘transition-delay’ property defines when the transition will start. It allows a transition to begin execution some some period of time from when it is applied.</td>
  </tr>
  <tr>
  <td>transition</td>
  <td>The ‘transition’ shorthand property combines the four properties described above into a single property.</td>
  </tr>
</table>

<h4>Specify the Speed Curve of the Transition</h4>
The transition-timing-function property can have the following values:
<ul>
<li>ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)</li>
<li>linear - specifies a transition effect with the same speed from start to end</li>
<li>ease-in - specifies a transition effect with a slow start</li>
<li>ease-out - specifies a transition effect with a slow end</li>
<li>ease-in-out - specifies a transition effect with a slow start and end</li>
<li>cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function</li>
</ul>

<a href="https://jsbin.com/zitize/edit?html,output">Transition-timing-function demo</a>

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
    <td>26.0<br/>4.0 -webkit-</td>
    <td>6.1<br/>3.1 -webkit</td>
    <td>16.0<br/>4.0 -moz-</td>
    <td>12.1<br/>10.5 -o-</td>
    <td>10.0</td>
    <td>2.1</td>
    <td>3.2</td>
  </tr>
</tbody>
</table>

<h3>Need for this standard:</h3>

<p>Normally when the value of a CSS property changes, the rendered result is instantly updated, with the affected elements immediately changing from the old property value to the new property value. Transitions properties are needed to animate smoothly from the old state to the new state over time.</p>


<h4>Working Section:</h4>

<a href="https://jsbin.com/daseva/edit?html,output">Transition</a>

<h4>References:</h4>

https://www.w3schools.com/css/css3_transitions.asp

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

<h4>Point of Contact:</h4>

<p>Sahil Kumar <a href="mailto:sahikumar@deloitte.com">sahikumar@deloitte.com</a></p>
