---
title: Animations
prev: /post
next: /post/css3text
weight: 1
---


<p>CSS animations are made up of two basic building blocks.</p>

<p> 1.<strong><i>@keyframes</i></strong>- defines the stages and styles of the animation. When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.
</p><p>To get an animation to work, you must bind the animation to an element.</p>

<p>2.<strong><i>Animation Properties</i></strong>- assign the @keyframes to a specific CSS element and define how it is animated.
Once the @keyframes are defined, the animation properties must be added in order for your animation to function.<p>

<p>There are basically two animation properties that are important for an animation to take place.</p>
    <ul>
        <li>animation-name</li>
        <li>animation-duration</li>
    </ul>
<p>Now to animate a div we can use the following code,</p>

<div style="display: flex;">
<div style="text-align:center;padding: 5px;margin:3px;">
<figcaption>Animation properties</figcaption>
<div class="prop">
  div<br/>
    {<br/>
    animation-duration: 2s;<br/>
    animation-name:bounceIn;<br/>
    @-keyframes bounceIn {
      0% {
        opacity: 0;
        -moz-transform: scale(0.8);
        }<br/>
      50% {
      opacity: 1;
      -moz-transform: scale(1.05);
      }<br/>
      100% {
      opacity: 1;
      -moz-transform: scale(1);
      }
    }
  }
</div>

</div>
<div style="text-align:center;padding: 5px;margin:3px;">
<figcaption>Shorthand syntax</figcaption>
  <div class="prop">
  div<br/> {<br/>
    animation: bounceIn 2s;<br/>
  }
  </div>    

</div>
</div>

<p><strong>Animation Property Shorthand:</strong></p>
<p><strong>animation: </strong>[animation-name] [animation-duration] [animation-timing-function] [animation-delay] [animation-iteration-count]  [animation-direction] [animation-fill-mode] [animation-play-state];</p>

<p><strong>Additional Animation Properties (recommended standard):</strong></p>
<ul>
  <li>animation-name</li>
  <li>animation-duration</li>
  <li>animation-timing-function</li>
  <li>animation-delay</li>
  <li>animation-iteration-count</li>
  <li>animation-direction</li>
  <li>animation-fill-mode</li>
  <li>animation-play-state</li>
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
    <td>43.0<br/>4.0 -webkit-</td>
    <td>9.0<br/>4.0 -webkit-</td>
    <td>16.0<br/>5.0 -moz-</td>
    <td>30.0<br/>15.0 -webkit-<br/>12.0 -o-</td>
    <td>10.0</td>
    <td>4.4</td>
    <td>4</td>
  </tr>
</tbody>
</table>

<h3>Need for this standard:</h3>

<p>For cleaner and faster code, one can use the animation shorthand, but it is always advisable to use the additional animation properties instead of the shorthand properties. This is because, not declaring few properties explicitly will set them to their default values which might take away the intention of the whole property. Also it becomes difficult to memorize the animation sequence for the shorthand, whereas it’s easier to remember them individually.</p>

<h3>Negative Impact:</h3>
<p>If one uses the shorthand property and fails to declare any property in the sequence, those properties will fall back to their default values.</p>
<p>Here is a table of the values that can be assigned to each property and their respective default values.</p>
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
    <td style="width:30%;">animation-timing-function</td>
    <td>ease</td>
    <td>ease | linear | ease-in | ease-out | ease-in-out | initial | inherit;
     One can creating custom timing functions using cubic-bezier curve.</td>
  </tr>
  <tr>
    <td>animation-delay</td>
    <td>0s</td>
    <td>time (positive or negative number of seconds (s) or milliseconds (ms))|initial | inherit;</td>
  </tr>
  <tr>
    <td>animation-iteration-count</td>
    <td>1</td>
    <td>number(number of times animation to be played) | infinite | initial | inherit;</td>
  </tr>
  <tr>
    <td>animation-direction</td>
    <td>normal</td>
    <td>normal | reverse | alternate | alternate-reverse | initial | inherit;</td>
  </tr>
  <tr>
    <td>animation-fill-mode</td>
    <td>none</td>
    <td>none | forwards | backwards | both | initial | inherit;</td>
  </tr>
    <tr>
    <td>animation-play-state</td>
    <td>running</td>
    <td>paused | running | initial | inherit;</td>
  </tr>
</tbody>
</table>

<h4>Working Section:</h4>
<p>Using shorthand property:</p>

<a href="https://jsbin.com/mopaze/2">Animation Shorthand</a>
<p>On not providing the animation-timing-function and animation-direction in the shorthand property it takes up their default values.</p>

<p>Using additional animation properties:</p>
<a href= "https://jsbin.com/ceqitov/4">Animation Properties</a>

<h4>References:</h4>
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations#Defining_the_animation_sequence_using_keyframes">Using CSS animations</a><br/>
<a href="https://www.w3.org/TR/css3-animations/#the-animation-shorthand-property-">CSS Animations</a><br/>
<a href="https://robots.thoughtbot.com/css-animation-for-beginners">CSS Animation for Beginners</a><br/>
<a href="http://caniuse.com/#feat=css-animation">CSS Animation</a><br/>
<a href="https://css-tricks.com/almanac/properties/a/animation/">CSS-Tricks Animation</a>

<h4>Point of Contact:</h4>

<p>Minu Kumari <a href="mailto:minkumari@deloitte.com">minkumari@deloitte.com</a></p>
