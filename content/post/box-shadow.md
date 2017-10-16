---
title: Box Shadow
prev: /post/css3text
next: /post/filters
weight: 3
---

<p>CSS3 Box-shadow property enables you to cast a drop shadow from the frame of almost any element. If a border-radius is specified on the element with a box shadow, the box shadow takes on the same rounded corners. The z-ordering of multiple box shadows is the same as multiple text shadows</p>

<p>box-shadow: [horizontal offset] [vertical offset] [blur radius] [optional spread radius] [color]</p>

<p><strong>Ex:</strong>  <span class="prop">
.shadow {
  box-shadow: 3px 3px 5px 6px #ccc;  /* Opera 10.5, IE 9, Firefox 4+, Chrome 6+, iOS 5
}

</span><p>

<p>The horizontal offset (required) of the shadow, positive means the shadow will be on the right of the box, a negative offset will put the shadow on the left of the box.
The vertical offset (required) of the shadow, a negative one means the box-shadow will be above the box, a positive one means the shadow will be below the box.
The blur radius (required), if set to 0 the shadow will be sharp, the higher the number, the more blurred it will be, and the further out the shadow will extend. For instance a shadow with 5px of horizontal offset that also has a 5px blur radius will be 10px of total shadow.
The spread radius (optional), positive values increase the size of the shadow, negative values decrease the size. Default is 0 (the shadow is same size as blur).
Color (required) - takes any color value, like hex, named, rgba or hsla. If the color value is omitted, box shadows are drawn in the foreground color (text color). But be aware, older WebKit browsers (pre Chrome 20 and Safari 6) ignore the rule when color is omitted.</p>

<h3>Need for this standard:</h3>

<p>This standard not only is helpful to provide shadow effect but also can be used to give multiple borders to an element.</p>



<h4>Working Section:</h4>

<a href="https://jsbin.com/negacekibo/edit?html,output">Box Shadow</a>


<h4>References:</h4>

https://css-tricks.com/almanac/properties/b/box-shadow/"

<h4>Point of Contact:</h4>

<p>Meghana Raju <a href="mailto:meraju@deloitte.com">meraju@deloitte.com</a></p>
