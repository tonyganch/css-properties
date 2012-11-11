# CSS properties

List of CSS properties supported by at least one of modern browsers.    
In alphabetical order.

## Legend

If no version is given:
 
* Safari = Safari 4 or later
* Chrome = last version of Chrome (current one is 23)
* Fx = Firefox 4 or later
* IE = Internet Explorer 8 or later
* Opera = Opera 11.60 or later

If browser name is given in italics (e.g., *Chrome*), it means the browser recognizes the property, but if you try to set it, nothing happens.

When choosing between prefixed/unprefixed property name, please keep in mind following:

* Use unprefixed property name when it's possible to ensure compatibility in the future.
* Сonsult browser docs if you need to support earlier versions (e.g., IE 7).
* Some prefixed properties have slightly different syntax (e.g., `-webkit-border-radius`). Consult browser docs before using them.

## List of properties

<table>
<thead>
<tr><th>Property</th><th>Can be used without prefix</th><th>-webkit</th><th>-moz</th><th>-ms</th><th>-o</th></tr>
</thead>
<tbody>
<tr><td>[accelerator][accelerator]</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
[accelerator]: http://msdn.microsoft.com/en-us/library/ie/ms530713(v=vs.85).aspx
<tr><td>[align-content](http://dev.w3.org/csswg/css3-flexbox/#align-content)</td><td>Fx 18+, Opera 12.10</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[align-items](http://dev.w3.org/csswg/css3-flexbox/#align-items)</td><td> Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[align-self](http://dev.w3.org/csswg/css3-flexbox/#align-self)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[animation](http://dev.w3.org/csswg/css3-animations/#animation)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-delay](http://dev.w3.org/csswg/css3-animations/#animation-delay)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-direction](http://dev.w3.org/csswg/css3-animations/#animation-direction)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-duration](http://dev.w3.org/csswg/css3-animations/#animation-duration)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-fill-mode](http://dev.w3.org/csswg/css3-animations/#animation-fill-mode)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari 5+, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-iteration-count](http://dev.w3.org/csswg/css3-animations/#animation-iteration-count)</td><td>Fx 16+, IE 10, Opera 12.10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-name](http://dev.w3.org/csswg/css3-animations/#animation-name)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-play-state](http://dev.w3.org/csswg/css3-animations/#animation-play-state)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>[animation-timing-function](http://dev.w3.org/csswg/css3-animations/#animation-timing-function)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera 12</td></tr>
<tr><td>app-region</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[appearance](http://css-tricks.com/almanac/properties/a/appearance/)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>aspect-ratio</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[backface-visibility](http://dev.w3.org/csswg/css3-transforms/#backface-visibility-property)</td><td>Fx 16+, IE 10</td><td>Safari, Chrome</td><td>Fx 10+</td><td></td><td></td></tr>
<tr><td>[background](http://www.w3.org/TR/CSS1/#background)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-attachment](http://www.w3.org/TR/CSS1/#background-attachment)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-clip](http://dev.w3.org/csswg/css3-background/#the-background-clip)</td><td>Chrome, Fx, IE 9+, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[background-color](http://www.w3.org/TR/CSS1/#background-color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-composite](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-background-composite)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[background-image](http://www.w3.org/TR/CSS1/#background-image)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-inline-policy](https://developer.mozilla.org/en-US/docs/CSS/-moz-background-inline-policy)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[background-origin](http://dev.w3.org/csswg/css3-background/#the-background-origin)</td><td>Chrome, Fx, IE 9+, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>background-origin-x</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-origin-y</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-position](http://www.w3.org/TR/CSS1/#background-position)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-position-x](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-background_position_x)</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>[background-position-y](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-background_position_y)</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>[background-repeat](http://www.w3.org/TR/CSS1/#background-repeat)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-repeat-x</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-repeat-y</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[background-size](http://dev.w3.org/csswg/css3-background/#the-background-size)</td><td>Safari, Chrome, Fx, IE 9+, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[behavior](https://developer.mozilla.org/en-US/docs/CSS/-moz-binding)</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>[binding][binding]</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
[binding]: http://msdn.microsoft.com/en-us/library/ie/ms530723(v=vs.85).aspx
<tr><td>blend-mode</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[block-progression][block-progression]</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
[block-progression]: http://msdn.microsoft.com/en-us/library/ie/dd229917(v=vs.85).aspx
<tr><td>[border](http://www.w3.org/TR/CSS1/#border)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom](http://www.w3.org/TR/CSS1/#border-bottom)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom-color](http://www.w3.org/TR/CSS2/box.html#border-color-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom-colors](https://developer.mozilla.org/en-US/docs/CSS/-moz-border-bottom-colors)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[border-bottom-left-radius](http://dev.w3.org/csswg/css3-background/#border-bottom-left-radius)</td><td>Safari 5+, Chrome, Fx, IE 9+, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom-right-radius](http://dev.w3.org/csswg/css3-background/#border-bottom-right-radius)</td><td>Safari 5+, Chrome, Fx, IE 9+, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom-style](http://www.w3.org/TR/CSS2/box.html#border-style-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-bottom-width](http://www.w3.org/TR/CSS2/box.html#border-width-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-collapse](http://www.w3.org/TR/CSS2/tables.html#borders)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-color](http://www.w3.org/TR/CSS1/#border-color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-end</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-end-color</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-end-style</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-end-width</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-fit</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-horizontal-spacing</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[border-image](http://dev.w3.org/csswg/css3-background/#border-image)</td><td>Chrome</td><td>Safari, Chrome, Fx 15+</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[border-image-outset](http://dev.w3.org/csswg/css3-background/#border-image-outset)</td><td>Chrome, Fx 15+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-image-repeat](http://dev.w3.org/csswg/css3-background/#border-image-repeat)</td><td>Chrome, Fx 15+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-image-slice](http://dev.w3.org/csswg/css3-background/#border-image-slice)</td><td>Chrome, Fx 15+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-image-source](http://dev.w3.org/csswg/css3-background/#border-image-source)</td><td>Chrome, Fx 15+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-image-width](http://dev.w3.org/csswg/css3-background/#border-image-width)</td><td>Chrome, Fx 13+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-left](http://www.w3.org/TR/CSS1/#border-left)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-left-color](http://www.w3.org/TR/CSS2/box.html#propdef-border-left-color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-left-colors](https://developer.mozilla.org/en-US/docs/CSS/-moz-border-left-colors)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[border-left-style](http://www.w3.org/TR/CSS2/box.html#border-style-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-left-width](http://www.w3.org/TR/CSS1/#border-left-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-radius](http://dev.w3.org/csswg/css3-background/#border-radius)</td><td>Safari 5+, Chrome, Fx, IE 9+, Opera</td><td>Safari, Opera 12.10+</td><td></td><td></td><td></td></tr>
<tr><td>[border-radius-bottomleft](http://dev.w3.org/csswg/css3-background/#border-bottom-left-radius)</td><td></td><td></td><td>Fx 12-</td><td></td><td></td></tr>
<tr><td>[border-radius-bottomright](http://dev.w3.org/csswg/css3-background/#border-bottom-right-radius)</td><td></td><td></td><td>Fx 12-</td><td></td><td></td></tr>
<tr><td>[border-radius-topleft](http://dev.w3.org/csswg/css3-background/#the-border-radius)</td><td></td><td></td><td>Fx 12-</td><td></td><td></td></tr>
<tr><td>[border-radius-topright](http://dev.w3.org/csswg/css3-background/#the-border-radius)</td><td></td><td></td><td>Fx 12-</td><td></td><td></td></tr>
<tr><td>[border-right](http://dev.w3.org/csswg/css3-background/#border-radius)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-right-color](http://www.w3.org/TR/CSS2/box.html#border-color-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-right-colors](https://developer.mozilla.org/en-US/docs/CSS/-moz-border-right-colors)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[border-right-style](http://www.w3.org/TR/CSS2/box.html#border-style-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-right-width](http://dev.w3.org/csswg/css3-background/#the-border-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-spacing](http://www.w3.org/TR/CSS2/tables.html#separated-borders)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-start</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-start-color</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-start-style</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-start-width</td><td></td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[border-style](http://dev.w3.org/csswg/css3-background/#border-style)</td><td>Safari, Chrome, Fx, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-top](http://dev.w3.org/csswg/css3-background/#border-top)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-top-color](http://dev.w3.org/csswg/css3-background/#border-top-color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-top-colors](https://developer.mozilla.org/en-US/docs/CSS/-moz-border-top-colors)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[border-top-left-radius](http://dev.w3.org/csswg/css3-background/#the-border-radius)</td><td>Safari 5+, Chrome, Fx, IE 9+, Opera</td><td>Safari, Chrome, Opera</td><td></td><td></td><td></td></tr>
<tr><td>[border-top-right-radius](http://dev.w3.org/csswg/css3-background/#the-border-radius)</td><td>Safari 5+, Chrome, Fx, IE 9+, Opera</td><td>Safari, Opera</td><td></td><td></td><td></td></tr>
<tr><td>[border-top-style](http://dev.w3.org/csswg/css3-background/#the-border-style)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[border-top-width](http://dev.w3.org/csswg/css3-background/#the-border-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-vertical-spacing</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[border-width](http://dev.w3.org/csswg/css3-background/#the-border-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[bottom](http://www.w3.org/TR/CSS2/visuren.html#propdef-bottom)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[box-align](https://developer.mozilla.org/en-US/docs/CSS/box-align)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-decoration-break</td><td>Opera</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[box-direction](https://developer.mozilla.org/en-US/docs/CSS/box-direction)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[box-flex](https://developer.mozilla.org/en-US/docs/CSS/-moz-box-flex)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-flex-group</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[box-float-edge](https://developer.mozilla.org/en-US/docs/CSS/-moz-float-edge)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[box-force-broken-image-icon](https://developer.mozilla.org/en-US/docs/CSS/-moz-force-broken-image-icon)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-lines</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[box-ordinal-group](https://developer.mozilla.org/en-US/docs/CSS/-moz-box-ordinal-group)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[box-orient](https://developer.mozilla.org/en-US/docs/CSS/-moz-box-orient)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[box-pack](https://developer.mozilla.org/en-US/docs/CSS/-moz-box-pack)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[box-reflect](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW16)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[box-shadow](http://dev.w3.org/csswg/css3-background/#box-shadow)</td><td>Safari 5.1+, Chrome, Fx, IE 9+, Opera</td><td>Safari, Opera</td><td></td><td></td><td></td></tr>
<tr><td>[box-sizing](http://dev.w3.org/csswg/css3-ui/#box-sizing)</td><td>Safari 5.1+, Chrome, IE, Opera</td><td>Safari</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[break-after](http://dev.w3.org/csswg/css3-break/#break-after)</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[break-before](http://dev.w3.org/csswg/css3-break/#break-before)</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[break-inside](http://dev.w3.org/csswg/css3-break/#break-inside)</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[caption-side](http://www.w3.org/TR/CSS2/tables.html#caption-position)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[clear](http://www.w3.org/TR/CSS1/#clear)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[clip](http://www.w3.org/TR/CSS2/visufx.html#clipping)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[clip-path](http://www.w3.org/TR/SVG11/masking.html#ClipPathProperty)</td><td>Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[color](http://www.w3.org/TR/CSS1/#color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>color-correction</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-axis</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-break-after](http://dev.w3.org/csswg/css3-multicol/#break-after)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-break-before](http://dev.w3.org/csswg/css3-multicol/#break-before)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-break-inside](http://dev.w3.org/csswg/css3-multicol/#break-inside)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-count](http://dev.w3.org/csswg/css3-multicol/#column-count)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[column-fill](http://dev.w3.org/csswg/css3-multicol/#column-fill)</td><td>IE 10, Opera</td><td></td><td>Fx 13+</td><td></td><td></td></tr>
<tr><td>[column-gap](http://dev.w3.org/csswg/css3-multicol/#column-gap)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-progression</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-rule](http://dev.w3.org/csswg/css3-multicol/#column-rule)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[column-rule-color](http://dev.w3.org/csswg/css3-multicol/#crc)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[column-rule-style](http://dev.w3.org/csswg/css3-multicol/#crs)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[column-rule-width](http://dev.w3.org/csswg/css3-multicol/#crw)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[column-span](http://dev.w3.org/csswg/css3-multicol/#column-span0)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[column-width](http://dev.w3.org/csswg/css3-multicol/#cw)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[columns](http://dev.w3.org/csswg/css3-multicol/#columns)</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx 9+</td><td></td><td></td></tr>
<tr><td>[content](http://www.w3.org/TR/CSS2/generate.html#content)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[content-zoom-chaining][content-zoom-chaining]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-chaining]: http://msdn.microsoft.com/en-us/library/ie/hh771889(v=vs.85).aspx
<tr><td>[content-zoom-limit][content-zoom-limit]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-limit]: http://msdn.microsoft.com/en-us/library/ie/jj127330(v=vs.85).aspx
<tr><td>[content-zoom-limit-max][content-zoom-limit-max]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-limit-max]: http://msdn.microsoft.com/en-us/library/ie/jj127331(v=vs.85).aspx
<tr><td>[content-zoom-limit-min][content-zoom-limit-min]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-limit-min]: http://msdn.microsoft.com/en-us/library/ie/jj127332(v=vs.85).aspx
<tr><td>[content-zoom-snap][content-zoom-snap]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-snap]: http://msdn.microsoft.com/en-us/library/ie/hh771893(v=vs.85).aspx
<tr><td>[content-zoom-snap-points][content-zoom-snap-points]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-snap-points]: http://msdn.microsoft.com/en-us/library/ie/hh771895(v=vs.85).aspx
<tr><td>[content-zoom-snap-type][content-zoom-snap-type]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zoom-snap-type]: http://msdn.microsoft.com/en-us/library/ie/hh771896(v=vs.85).aspx
<tr><td>[content-zooming][content-zooming]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[content-zooming]: http://msdn.microsoft.com/en-us/library/ie/hh771891(v=vs.85).aspx
<tr><td>[counter-increment](http://www.w3.org/TR/CSS2/generate.html#propdef-counter-increment)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[counter-reset](http://www.w3.org/TR/CSS2/generate.html#propdef-counter-reset)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[cursor](http://dev.w3.org/csswg/css3-ui/#cursor)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>dashboard-region</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>device-pixel-ratio</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>[direction](http://www.w3.org/TR/CSS2/visuren.html#direction)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[display](http://dev.w3.org/csswg/css3-box/#display)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[empty-cells](http://www.w3.org/TR/CSS2/tables.html#empty-cells)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[filter](http://dvcs.w3.org/hg/FXTF/raw-file/tip/filters/index.html#FilterProperty)</td><td></td><td>Chrome</td><td></td><td>IE</td><td></td></tr>
<tr><td>[flex](http://dev.w3.org/csswg/css3-flexbox/#flex)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>[flex-align][flex-align]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[flex-align]: http://msdn.microsoft.com/en-us/library/ie/jj127298(v=vs.85).aspx
<tr><td>[flex-basis](http://dev.w3.org/csswg/css3-flexbox/#flex-basis)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[flex-direction](http://dev.w3.org/csswg/css3-flexbox/#flex-direction)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>[flex-flow](http://dev.w3.org/csswg/css3-flexbox/#flex-flow)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[flex-grow](http://dev.w3.org/csswg/css3-flexbox/#flex-grow)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[flex-order][flex-order]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[flex-order]: http://msdn.microsoft.com/en-us/library/ie/jj127303(v=vs.85).aspx
<tr><td>[flex-pack][flex-pack]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[flex-pack]: http://msdn.microsoft.com/en-us/library/ie/jj127304(v=vs.85).aspx
<tr><td>[flex-shrink](http://dev.w3.org/csswg/css3-flexbox/#flex-shrink)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[flex-wrap](http://dev.w3.org/csswg/css3-flexbox/#flex-wrap)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>[float](http://www.w3.org/TR/CSS1/#float)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>flow-from</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>flow-intro</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>[font](http://dev.w3.org/csswg/css3-fonts/#font)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[font-family](http://dev.w3.org/csswg/css3-fonts/#font-family-prop)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[font-feature-settings](http://dev.w3.org/csswg/css3-fonts/#propdef-font-feature-settings)</td><td>IE 10</td><td>Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>font-kerning</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-language-override</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[font-size](http://dev.w3.org/csswg/css3-fonts/#propdef-font-size)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[font-size-adjust](http://dev.w3.org/csswg/css3-fonts/#propdef-font-size-adjust)</td><td>Fx, IE 10</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-size-delta</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-smoothing</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[font-stretch](http://dev.w3.org/csswg/css3-fonts/#propdef-font-stretch)</td><td>Chrome, Fx 9+, IE 9+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[font-style](http://dev.w3.org/csswg/css3-fonts/#font-style-prop)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[font-variant](http://dev.w3.org/csswg/css3-fonts/#propdef-font-variant)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-variant-ligatures</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[font-weight](http://dev.w3.org/csswg/css3-fonts/#font-weight-prop)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[grid-column][grid-column]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[grid-column]: http://msdn.microsoft.com/en-us/library/ie/hh772242(v=vs.85).aspx
<tr><td>[grid-column-align][grid-column-align]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[grid-column-align]: http://msdn.microsoft.com/en-us/library/ie/hh772245(v=vs.85).aspx
<tr><td>[grid-column-span][grid-column-span]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[grid-column-span]: http://msdn.microsoft.com/en-us/library/ie/hh772248(v=vs.85).aspx
<tr><td>[grid-columns][grid-columns]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[grid-columns]: http://msdn.microsoft.com/en-us/library/ie/hh772246(v=vs.85).aspx
<tr><td>[grid-row][grid-row]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[grid-row]: http://msdn.microsoft.com/en-us/library/ie/hh772254(v=vs.85).aspx
<tr><td>[grid-row-align][grid-row-align]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[grid-row-align]: http://msdn.microsoft.com/en-us/library/ie/hh772256(v=vs.85).aspx
<tr><td>[grid-row-span][grid-row-span]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[grid-row-span]: http://msdn.microsoft.com/en-us/library/ie/hh772260(v=vs.85).aspx
<tr><td>[grid-rows][grid-rows]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[grid-rows]: http://msdn.microsoft.com/en-us/library/ie/hh772258(v=vs.85).aspx
<tr><td>[height](http://dev.w3.org/csswg/css3-box/#the-width-and-height-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[high-contrast-adjust][high-contrast-adjust]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[high-contrast-adjust]: http://msdn.microsoft.com/en-us/library/ie/hh771863(v=vs.85).aspx
<tr><td>highlight</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-character</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-limit-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-limit-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[hyphenate-limit-chars][hyphenate-limit-chars]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[hyphenate-limit-chars]: http://msdn.microsoft.com/en-us/library/ie/hh771865(v=vs.85).aspx
<tr><td>[hyphenate-limit-lines][hyphenate-limit-lines]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[hyphenate-limit-lines]: http://msdn.microsoft.com/en-us/library/ie/hh771867(v=vs.85).aspx
<tr><td>[hyphenate-limit-zone][hyphenate-limit-zone]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[hyphenate-limit-zone]: http://msdn.microsoft.com/en-us/library/ie/hh771869(v=vs.85).aspx
<tr><td>[hyphens](http://dev.w3.org/csswg/css3-text/#hyphens)</td><td></td><td>Safari 5.1+, Chrome</td><td>Fx 6+</td><td>IE 10</td><td></td></tr>
<tr><td>icon</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>[image-region](https://developer.mozilla.org/en-US/docs/CSS/-moz-image-region)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[image-rendering](http://dev.w3.org/csswg/css4-images/#image-rendering)</td><td>Safari 5+, Chrome, Fx, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>image-resolution</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[image-orientation](http://dev.w3.org/csswg/css3-images/#image-orientation)</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[ime-mode](http://dev.w3.org/csswg/css3-ui/#input-method-editor)</td><td>Fx, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[interpolation-mode][interpolation-mode]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[interpolation-mode]: http://msdn.microsoft.com/en-us/library/ie/ms530822(v=vs.85).aspx
<tr><td>[justify-content](http://dev.w3.org/csswg/css3-flexbox/#justify-content)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[layout-flow][layout-flow]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-flow]: http://msdn.microsoft.com/en-us/library/ie/ms530770(v=vs.85).aspx
<tr><td>[layout-grid][layout-grid]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-grid]: http://msdn.microsoft.com/en-us/library/ie/ms530771(v=vs.85).aspx
<tr><td>[layout-grid-char][layout-grid-char]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-grid-char]: http://msdn.microsoft.com/en-us/library/ie/ms530772(v=vs.85).aspx
<tr><td>[layout-grid-line][layout-grid-line]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-grid-line]: http://msdn.microsoft.com/en-us/library/ie/ms530773(v=vs.85).aspx
<tr><td>[layout-grid-mode][layout-grid-mode]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-grid-mode]: http://msdn.microsoft.com/en-us/library/ie/ms530774(v=vs.85).aspx
<tr><td>[layout-grid-type][layout-grid-type]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[layout-grid-type]: http://msdn.microsoft.com/en-us/library/ie/ms530775(v=vs.85).aspx
<tr><td>[left](http://www.w3.org/TR/CSS2/visuren.html#propdef-left)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[letter-spacing](http://dev.w3.org/csswg/css3-text/#letter-spacing)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>line-align</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-box-contain</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-break</td><td></td><td>Safari, Chrome</td><td></td><td>IE</td><td></td></tr>
<tr><td>line-clamp</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-grid</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[line-height](http://www.w3.org/TR/CSS1/#line-height)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>line-snap</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[list-style](http://dev.w3.org/csswg/css3-lists/#list-style)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[list-style-image](http://dev.w3.org/csswg/css3-lists/#list-style-image)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[list-style-position](http://dev.w3.org/csswg/css3-lists/#list-style-position)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[list-style-type](http://dev.w3.org/csswg/css3-lists/#list-style-type)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>locale</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[margin](http://www.w3.org/TR/CSS1/#margin)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-after-collapse</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-before-collapse</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[margin-bottom](http://www.w3.org/TR/CSS1/#margin-bottom)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[margin-bottom-collapse](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-margin-bottom-collapse)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[margin-collapse](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-margin-collapse)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[margin-end](https://developer.mozilla.org/en-US/docs/CSS/-moz-margin-end)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[margin-left](http://www.w3.org/TR/CSS1/#margin-left)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[margin-right](http://www.w3.org/TR/CSS1/#margin-right)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[margin-start](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-margin-start)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[margin-top](http://www.w3.org/TR/CSS1/#margin-top)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[margin-top-collapse](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-margin-top-collapse)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[marks](http://dev.w3.org/csswg/css3-gcpm/#marks)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>marquee</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-direction</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-increment</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-repetition</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-play-count</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>marquee-speed</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-style</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW17)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-attachment](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW3)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-box-image](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW14)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-outset</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-repeat</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-slice</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-source</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-clip](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW4)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-composite](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW13)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-image](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW7)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-origin](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW6)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-position](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW18)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-position-x](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW19)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-position-y](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW20)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-repeat](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW8)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-repeat-x</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-repeat-y</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[mask-size](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW21)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>match-nearest-mail-blockquote-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[max-height](http://www.w3.org/TR/CSS2/visudet.html#propdef-max-height)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>max-logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>max-logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[max-width](http://www.w3.org/TR/CSS2/visudet.html#propdef-max-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>max-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[min-height](http://www.w3.org/TR/CSS2/visudet.html#propdef-min-height)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>min-logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>min-logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[min-width](http://www.w3.org/TR/CSS2/visudet.html#propdef-min-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>min-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[nav-down](http://dev.w3.org/csswg/css3-ui/#nav-down)</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[nav-index](http://dev.w3.org/csswg/css3-ui/#nav-index0)</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[nav-left](http://dev.w3.org/csswg/css3-ui/#nav-left)</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[nav-right](http://dev.w3.org/csswg/css3-ui/#nav-right)</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[nav-up](http://dev.w3.org/csswg/css3-ui/#nav-up)</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nbsp-mode</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>object-fit</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>object-position</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>[opacity](http://dev.w3.org/csswg/css3-color/#opacity)</td><td>Safari, Chrome, Fx, IE 9+, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[order](http://dev.w3.org/csswg/css3-flexbox/#order-property)</td><td>Fx 18+, Opera 12.10+</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[orient](https://developer.mozilla.org/en-US/docs/CSS/-moz-orient)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>orientation</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[orphans](http://dev.w3.org/csswg/css3-page/#orphans)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[outline](http://dev.w3.org/csswg/css3-ui/#outline)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[outline-color](http://dev.w3.org/csswg/css3-ui/#outline-color)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[outline-offset](http://dev.w3.org/csswg/css3-ui/#outline-offset)</td><td>Safari, Chrome, Fx, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[outline-radius](https://developer.mozilla.org/en-US/docs/CSS/-moz-outline-radius)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[outline-radius-bottomleft](https://developer.mozilla.org/en-US/docs/CSS/-moz-outline-radius-bottomleft)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[outline-radius-bottomright](https://developer.mozilla.org/en-US/docs/CSS/-moz-outline-radius-bottomright)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[outline-radius-topleft](https://developer.mozilla.org/en-US/docs/CSS/-moz-outline-radius-topleft)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[outline-radius-topright](https://developer.mozilla.org/en-US/docs/CSS/-moz-outline-radius-topright)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[outline-style](http://dev.w3.org/csswg/css3-ui/#outline-style)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[outline-width](http://dev.w3.org/csswg/css3-ui/#outline-width)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[overflow](http://dev.w3.org/csswg/css3-box/#overflow1)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>overflow-scrolling</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[overflow-style][overflow-style]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[overflow-style]: http://msdn.microsoft.com/en-us/library/ie/hh771902(v=vs.85).aspx
<tr><td>overflow-wrap</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[overflow-x](http://dev.w3.org/csswg/css3-box/#overflow-x)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>[overflow-y](http://dev.w3.org/csswg/css3-box/#overflow-y)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>[padding](http://dev.w3.org/csswg/css3-box/#the-padding)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>padding-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>padding-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[padding-bottom](http://dev.w3.org/csswg/css3-box/#the-padding)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[padding-end](https://developer.mozilla.org/en-US/docs/CSS/-moz-padding-end)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[padding-left](http://dev.w3.org/csswg/css3-box/#the-padding)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[padding-right](http://dev.w3.org/csswg/css3-box/#the-padding)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[padding-start](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266--webkit-padding-start)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[padding-top](http://dev.w3.org/csswg/css3-box/#the-padding)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>page</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[page-break-after](http://dev.w3.org/csswg/css3-page/#page-break-after)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[page-break-before](http://dev.w3.org/csswg/css3-page/#page-break-before)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[page-break-inside](http://dev.w3.org/csswg/css3-page/#page-break-inside)</td><td>Safari, Chrome, Fx 19+, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[perspective](http://dev.w3.org/csswg/css3-transforms/#perspective)</td><td>Fx 16+, IE 10</td><td>Safari, Chrome</td><td>Fx 10+</td><td></td><td></td></tr>
<tr><td>[perspective-origin](http://dev.w3.org/csswg/css3-transforms/#perspective-origin)</td><td>Fx 16+, IE 10</td><td>Safari, Chrome</td><td>Fx 10+</td><td></td><td></td></tr>
<tr><td>perspective-origin-x</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>perspective-origin-y</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[pointer-events](http://www.w3.org/TR/SVG11/interact.html#PointerEventsProperty)</td><td>Safari, Chrome, Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[position](http://www.w3.org/TR/CSS2/visuren.html#propdef-position)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>print-color-adjust</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[progress-appearance][progress-appearance]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[progress-appearance]: http://msdn.microsoft.com/en-us/library/ie/hh781491(v=vs.85).aspx
<tr><td>[quotes](http://www.w3.org/TR/CSS2/generate.html#quotes)</td><td>Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>region-overflow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[region-break-after](http://dev.w3.org/csswg/css3-regions/#break-after)</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[region-break-before](http://dev.w3.org/csswg/css3-regions/#break-before)</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[region-break-inside](http://dev.w3.org/csswg/css3-regions/#break-inside)</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[resize](http://dev.w3.org/csswg/css3-ui/#resize)</td><td>Safari, Chrome, Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[right](http://www.w3.org/TR/CSS2/visuren.html#propdef-right)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>rtl-ordering</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[ruby-align][ruby-align]</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
[ruby-align]: http://msdn.microsoft.com/en-us/library/ie/ms531150(v=vs.85).aspx
<tr><td>[ruby-overhang][ruby-overhang]</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
[ruby-overhang]: http://msdn.microsoft.com/en-us/library/ie/ms531151(v=vs.85).aspx
<tr><td>[ruby-position][ruby-position]</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
[ruby-position]: http://msdn.microsoft.com/en-us/library/ie/ms531152(v=vs.85).aspx
<tr><td>script-level</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>script-min-size</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>script-size-multiplier</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[scrollbar-3dlight-color][scrollbar-3dlight-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-3dlight-color]: http://msdn.microsoft.com/en-us/library/ie/ms531153(v=vs.85).aspx
<tr><td>[scroll-chaining][scroll-chaining]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-chaining]: http://msdn.microsoft.com/en-us/library/ie/hh772034(v=vs.85).aspx
<tr><td>[scroll-limit][scroll-limit]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-limit]: http://msdn.microsoft.com/en-us/library/ie/jj127336(v=vs.85).aspx
<tr><td>[scroll-limit-x-max][scroll-limit-x-max]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-limit-x-max]: http://msdn.microsoft.com/en-us/library/ie/jj127337(v=vs.85).aspx
<tr><td>[scroll-limit-x-min][scroll-limit-x-min]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-limit-x-min]: http://msdn.microsoft.com/en-us/library/ie/jj127338(v=vs.85).aspx
<tr><td>[scroll-limit-y-max][scroll-limit-y-max]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-limit-y-max]: http://msdn.microsoft.com/en-us/library/ie/jj127339(v=vs.85).aspx
<tr><td>[scroll-limit-y-min][scroll-limit-y-min]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-limit-y-min]: http://msdn.microsoft.com/en-us/library/ie/jj127340(v=vs.85).aspx
<tr><td>[scroll-rails][scroll-rails]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-rails]: http://msdn.microsoft.com/en-us/library/ie/hh772035(v=vs.85).aspx
<tr><td>[scroll-snap-points-x][scroll-snap-points-x]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-snap-points-x]: http://msdn.microsoft.com/en-us/library/ie/hh772036(v=vs.85).aspx
<tr><td>[scroll-snap-points-y][scroll-snap-points-y]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-snap-points-y]: http://msdn.microsoft.com/en-us/library/ie/hh772037(v=vs.85).aspx
<tr><td>[scroll-snap-type][scroll-snap-type]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-snap-type]: http://msdn.microsoft.com/en-us/library/ie/hh772038(v=vs.85).aspx
<tr><td>[scroll-snap-x][scroll-snap-x]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-snap-x]: http://msdn.microsoft.com/en-us/library/ie/hh772039(v=vs.85).aspx
<tr><td>[scroll-snap-y][scroll-snap-y]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-snap-y]: http://msdn.microsoft.com/en-us/library/ie/hh772040(v=vs.85).aspx
<tr><td>[scroll-translation][scroll-translation]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scroll-translation]: http://msdn.microsoft.com/en-us/library/ie/hh973361(v=vs.85).aspx
<tr><td>[scrollbar-arrow-color][scrollbar-arrow-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-arrow-color]: http://msdn.microsoft.com/en-us/library/ie/ms531154(v=vs.85).aspx
<tr><td>[scrollbar-base-color][scrollbar-base-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-base-color]: http://msdn.microsoft.com/en-us/library/ie/ms531155(v=vs.85).aspx
<tr><td>[scrollbar-darkshadow-color][scrollbar-darkshadow-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-darkshadow-color]: http://msdn.microsoft.com/en-us/library/ie/ms531156(v=vs.85).aspx
<tr><td>[scrollbar-face-color][scrollbar-face-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-face-color]: http://msdn.microsoft.com/en-us/library/ie/ms531157(v=vs.85).aspx
<tr><td>[scrollbar-highlight-color][scrollbar-highlight-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-highlight-color]: http://msdn.microsoft.com/en-us/library/ie/ms531158(v=vs.85).aspx
<tr><td>[scrollbar-shadow-color][scrollbar-shadow-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-shadow-color]: http://msdn.microsoft.com/en-us/library/ie/ms531159(v=vs.85).aspx
<tr><td>[scrollbar-track-color][scrollbar-track-color]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[scrollbar-track-color]: http://msdn.microsoft.com/en-us/library/ie/ms531160(v=vs.85).aspx
<tr><td>shape-inside</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>shape-outside</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>size</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[src](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-src)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>speak</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[stack-sizing](https://developer.mozilla.org/en-US/docs/CSS/-moz-stack-sizing)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>svg-shadow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[tab-size](http://dev.w3.org/csswg/css3-text/#tab-size)</td><td>Chrome</td><td>Fx</td><td></td><td></td><td>Opera</td></tr>
<tr><td>table-baseline</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>[table-layout](http://www.w3.org/TR/CSS2/tables.html#width-layout)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>tap-highlight-color</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-align](http://dev.w3.org/csswg/css3-text/#text-align)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-align-last](http://dev.w3.org/csswg/css3-text/#text-align-last)</td><td></td><td></td><td>Fx 12+</td><td>IE 10</td><td></td></tr>
<tr><td>[text-autospace][text-autospace]</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
[text-autospace]: http://msdn.microsoft.com/en-us/library/ie/ms531164(v=vs.85).aspx
<tr><td>[text-blink](https://developer.mozilla.org/en-US/docs/CSS/-moz-text-blink)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>text-combine</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-decoration](http://dev.w3.org/csswg/css3-text/#text-decoration)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-decoration-color](http://dev.w3.org/csswg/css3-text/#text-decoration-color)</td><td></td><td></td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>[text-decoration-line](http://dev.w3.org/csswg/css3-text/#text-decoration-line)</td><td></td><td>Chrome</td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>text-decoration-skip</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-decoration-style](http://dev.w3.org/csswg/css3-text/#text-decoration-style)</td><td></td><td>Chrome</td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>text-decorations-in-effect</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-position</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-fill-color</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-indent](http://dev.w3.org/csswg/css3-text/#text-indent)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-justify][text-justify]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[text-justify]: http://msdn.microsoft.com/en-us/library/ie/ms531172(v=vs.85).aspx
<tr><td>[text-kashida-space][text-kashida-space]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[text-kashida-space]: http://msdn.microsoft.com/en-us/library/ie/ms531173(v=vs.85).aspx
<tr><td>text-line-through</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-color</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-mode</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-style</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-width</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-orientation</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-overflow](http://dev.w3.org/csswg/css3-ui/#text-overflow)</td><td>Safari, Chrome, Opera</td><td></td><td></td><td>IE 10</td><td></td></tr>
<tr><td>text-overflow-ellipsis</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overflow-mode</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-color</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-mode</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-style</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-width</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-rendering](http://www.w3.org/TR/SVG11/painting.html#TextRenderingProperty)</td><td>Safari 5+, Chrome, Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-security</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-shadow](http://dev.w3.org/csswg/css3-text/#text-shadow)</td><td>Safari, Chrome, Fx, IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-size-adjust</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke-color</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke-width</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[text-transform](http://dev.w3.org/csswg/css3-text/#text-transform)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-color</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-mode</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[text-underline-position][text-underline-position]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[text-underline-position]: http://msdn.microsoft.com/en-us/library/ie/ms531176(v=vs.85).aspx
<tr><td>text-underline-style</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-width</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[top](http://www.w3.org/TR/CSS2/visuren.html#propdef-top)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[touch-action][touch-action]</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
[touch-action]: http://msdn.microsoft.com/en-us/library/ie/hh772044(v=vs.85).aspx
<tr><td>touch-callout</td><td></td><td>Safari iOS</td><td></td><td></td><td></td></tr>
<tr><td>[transform](http://dev.w3.org/csswg/css3-transforms/#transform)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td>IE 9</td><td>Opera</td></tr>
<tr><td>[transform-origin](http://dev.w3.org/csswg/css3-transforms/#transform-origin)</td><td>Fx 16, IE 10, Opera 12.10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td>IE 9</td><td>Opera</td></tr>
<tr><td>[transform-origin-x](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-_webkit_transform_origin_x)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[transform-origin-y](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-_webkit_transform_origin_y)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[transform-origin-z](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-SW22)</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[transform-style](http://dev.w3.org/csswg/css3-transforms/#transform-style)</td><td>Fx 16+, IE 10</td><td>Safari, Chrome</td><td>Fx 10+</td><td></td><td></td></tr>
<tr><td>[transition](http://dev.w3.org/csswg/css3-transitions/#transition)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[transition-delay](http://dev.w3.org/csswg/css3-transitions/#transition-delay)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[transition-duration](http://dev.w3.org/csswg/css3-transitions/#transition-duration)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[transition-property](http://dev.w3.org/csswg/css3-transitions/#transition-property)</td><td>Fx 16+, IE 10, Opera 12.10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[transition-timing-function](http://dev.w3.org/csswg/css3-transitions/#transition-timing-function)</td><td>Fx 16+, IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>[unicode-bidi](http://dev.w3.org/csswg/css3-writing-modes/#unicode-bidi)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td>Fx 10+</td><td></td><td></td></tr>
<tr><td>[unicode-range](http://developer.apple.com/library/safari/documentation/appleapplications/reference/safaricssref/Articles/StandardCSSProperties.html#//apple_ref/doc/uid/TP30001266-unicode_range)</td><td>Safari, Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>user-drag</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[user-focus](https://developer.mozilla.org/en-US/docs/CSS/-moz-user-focus)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[user-input](https://developer.mozilla.org/en-US/docs/CSS/-moz-user-input)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[user-modify](https://developer.mozilla.org/en-US/docs/CSS/-moz-user-modify)</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>[user-select][user-select]</td><td></td><td>Safari, Chrome</td><td>Fx</td><td>IE 10</td><td></td></tr>
[user-select]: http://msdn.microsoft.com/en-us/library/ie/hh781492(v=vs.85).aspx
<tr><td>user-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[vertical-align](http://www.w3.org/TR/CSS1/#vertical-align)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[visibility](http://dev.w3.org/csswg/css3-box/#the-visibility-property)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>white-space</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[widows](http://dev.w3.org/csswg/css3-break/#widows-orphans)</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[width](http://dev.w3.org/csswg/css3-box/#the-width-and-height-properties)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[window-shadow](https://developer.mozilla.org/en-US/docs/CSS/-moz-window-shadow)</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>[word-break](http://dev.w3.org/csswg/css3-text/#word-break)</td><td>Safari, Chrome, Fx 15+, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[word-spacing](http://dev.w3.org/csswg/css3-text/#word-spacing)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>[word-wrap](http://dev.w3.org/csswg/css3-text/#overflow-wrap)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>wrap</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[wrap-flow][wrap-flow]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[wrap-flow]: http://msdn.microsoft.com/en-us/library/ie/hh772045(v=vs.85).aspx
<tr><td>[wrap-margin][wrap-margin]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[wrap-margin]: http://msdn.microsoft.com/en-us/library/ie/hh772042(v=vs.85).aspx
<tr><td>wrap-padding</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>[wrap-through]</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
[wrap-through]: http://msdn.microsoft.com/en-us/library/ie/hh771900(v=vs.85).aspx
<tr><td>[writing-mode]</td><td></td><td>Chrome</td><td></td><td>IE</td><td></td></tr>
[writing-mode]: http://msdn.microsoft.com/en-us/library/ie/ms531187(v=vs.85).aspx
<tr><td>[z-index](http://www.w3.org/TR/CSS2/visuren.html#z-index)</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>zoom</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
</tbody>
<table>

## Reference

[CSS properties supported by Mozilla](https://developer.mozilla.org/en-US/docs/Mozilla_CSS_support_chart)    
[CSS properties supported by Apple](http://developer.apple.com/library/safari/#documentation/appleapplications/reference/safaricssref/articles/standardcssproperties.html)    
[CSS properties supported by Microsoft](http://msdn.microsoft.com/en-us/library/windows/apps/hh767304.aspx)    
[CSS properties recognized by Webkit](http://trac.webkit.org/browser/trunk/Source/WebCore/css/CSSPropertyNames.in)
