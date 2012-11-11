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
* Сonsult browser docs if you need to support earlier versions (e.g., IE 7, Fx 3.6).
* Some prefixed properties have slightly different syntax (e.g., `-webkit-border-radius`). Consult browser docs before using them.

## List of properties

<table>
<thead>
<tr><th>Property</th><th>Can be used without prefix</th><th>-webkit</th><th>-moz</th><th>-ms</th><th>-o</th></tr>
</thead>
<tbody>
<tr><td>accelerator</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>align-content</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>align-items</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>align-self</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>animation</td><td>IE 10, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-delay</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-direction</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-duration</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-fill-mode</td><td>IE 10</td><td>Safari 5+, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-iteration-count</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-name</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-play-state</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>animation-timing-function</td><td>IE 10</td><td>Safari, Chrome</td><td>Fx 5+</td><td></td><td>Opera</td></tr>
<tr><td>app-region</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>appearance</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>aspect-ratio</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>backface-visibility</td><td>IE 10</td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>background</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-attachment</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-clip</td><td>Chrome, Fx, IE 9+, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>background-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-composite</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>background-image</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-inline-policy</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-origin</td><td>Chrome, Fx, IE 9+, Opera 12.10+</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>background-position</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-position-x</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>background-position-y</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>background-repeat</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-repeat-x</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-repeat-y</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>background-size</td><td>Chrome, Fx, IE 9+, Opera 12.10+</td><td>Safari, Chrome, Opera 12.10+</td><td>Fx</td><td></td><td>O 9.6–10.5</td></tr>
<tr><td>behavior</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>blend-mode</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>block-progression</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>border</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-after-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-before-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-bottom</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-colors</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-left-radius</td><td>Chrome, Fx, IE 9+</td><td>Safari, Chrome, Opera</td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-right-radius</td><td>Chrome, Fx, IE 9+</td><td>Safari, Chrome, Opera</td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-bottom-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-collapse</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-end</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-end-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-end-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-end-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-fit</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-horizontal-spacing</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-image</td><td>Chrome</td><td>Safari, Chrome</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>border-image-outset</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-image-repeat</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-image-slice</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-image-source</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-image-width</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-left</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-left-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-left-colors</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-left-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-left-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-radius</td><td>Chrome, Fx, IE 9+, Opera 12.10+</td><td>Safari, Chrome, Opera 12.10+</td><td></td><td></td><td></td></tr>
<tr><td>border-radius-bottomleft</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-radius-bottomright</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-radius-topleft</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-radius-topright</td><td></td><td></td><td>Fx</td><td></td><td></td></tr>
<tr><td>border-right</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-right-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-right-colors</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-right-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-right-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-spacing</td><td>Safari, Chrome, Fx, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-start</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-start-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-start-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-start-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-style</td><td>Safari, Chrome, Fx, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-top</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-top-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-top-colors</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-top-left-radius</td><td>Chrome, Fx, IE 9+</td><td>Safari, Chrome, Opera</td><td></td><td></td><td></td></tr>
<tr><td>border-top-right-radius</td><td>Chrome, Fx, IE 9+</td><td>Safari, Chrome, Opera</td><td></td><td></td><td></td></tr>
<tr><td>border-top-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-top-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>border-vertical-spacing</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>border-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>bottom</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>box-align</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-decoration-break</td><td>Opera</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>box-direction</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-flex</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-flex-group</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>box-lines</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>box-ordinal-group</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-orient</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-pack</td><td></td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-reflect</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>box-shadow</td><td>Chrome, IE 9+, Opera</td><td>Safari, Opera, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>box-sizing</td><td>Chrome, Opera, IE</td><td>Safari</td><td>Fx</td><td></td><td></td></tr>
<tr><td>break-after</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>break-before</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>break-inside</td><td>IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>caption-side</td><td>Safari, Chrome, Fx, IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>clear</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>clip</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>clip-path</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>color-correction</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-axis</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-break-after</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-break-before</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-break-inside</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-count</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-fill</td><td>IE 10, Opera</td><td></td><td>Fx 13+</td><td></td><td></td></tr>
<tr><td>column-gap</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-progression</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-rule</td><td>Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-rule-color</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-rule-style</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-rule-width</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>column-span</td><td>IE 10, Opera</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>column-width</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx</td><td></td><td></td></tr>
<tr><td>columns</td><td>IE 10, Opera</td><td>Safari, Chrome</td><td>Fx 9+</td><td></td><td></td></tr>
<tr><td>content</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>counter-increment</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>counter-reset</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>cursor</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>dashboard-region</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>device-pixel-ratio</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>direction</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>display</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>empty-cells</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>filter</td><td></td><td>Chrome</td><td></td><td>IE</td><td></td></tr>
<tr><td>flex</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-basis</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-direction</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-flow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-grow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-shrink</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flex-wrap</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>float</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>flow-intro</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>flow-from</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-family</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-feature-settings</td><td>IE 10</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-kerning</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-language-override</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-size</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-size-adjust</td><td>Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-size-delta</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-smoothing</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-stretch</td><td>Chrome, Fx 9+, IE 9+</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-variant</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>font-variant-ligatures</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>font-weight</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>grid-column</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>grid-columns</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>grid-row</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>grid-rows</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>height</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>highlight</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-character</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-limit-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-limit-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>hyphenate-limit-chars</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
<tr><td>hyphenate-limit-lines</td><td></td><td>Chrome</td><td></td><td>IE 10</td><td></td></tr>
<tr><td>hyphenate-limit-zone</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
<tr><td>hyphens</td><td></td><td></td><td></td><td>IE 10</td><td></td></tr>
<tr><td>icon</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>image-rendering</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>image-resolution</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>image-orientation</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>ime-mode</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>interpolation-mode</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>justify-content</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>layout-grid</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>layout-grid-char</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>layout-grid-line</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>layout-grid-mode</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>layout-grid-type</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>left</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>letter-spacing</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>line-align</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-box-contain</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-break</td><td></td><td>Safari, Chrome</td><td></td><td>IE</td><td></td></tr>
<tr><td>line-clamp</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-grid</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>line-height</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>line-snap</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>list-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>list-style-image</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>list-style-position</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>list-style-type</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>locale</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-after-collapse</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-before-collapse</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-bottom</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-bottom-collapse</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-collapse</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-end</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-left</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-right</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-start</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>margin-top</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>margin-top-collapse</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marks</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>marquee</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-direction</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-increment</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-repetition</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-play-count</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>marquee-speed</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>marquee-style</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-attachment</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-outset</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-repeat</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-slice</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-source</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-box-image-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-clip</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-composite</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-image</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-origin</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-position</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-position-x</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-position-y</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-repeat</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-repeat-x</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-repeat-y</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>mask-size</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>max-height</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>max-logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>max-logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>min-logical-height</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>min-logical-width</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>max-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>max-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>min-height</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>min-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>min-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nav-down</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nav-index</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nav-left</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nav-right</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nav-up</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>nbsp-mode</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>object-fit</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>object-position</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>opacity</td><td>Safari, Chrome, Fx, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>order</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>orientation</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>orphans</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-color</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-offset</td><td>Safari, Chrome, Fx, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-radius</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-radius-bottomleft</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-radius-bottomright</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-radius-topleft</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-radius-topright</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-style</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>outline-width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>overflow</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>overflow-scrolling</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>overflow-wrap</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>overflow-x</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>overflow-y</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>padding</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>padding-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>padding-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>padding-bottom</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>padding-end</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>padding-left</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>padding-right</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>padding-start</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>padding-top</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>page</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>page-break-after</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>page-break-before</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>page-break-inside</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>perspective</td><td>IE 10</td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>perspective-origin</td><td>IE 10</td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>perspective-origin-x</td><td>IE 10</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>perspective-origin-y</td><td>IE 10</td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>pointer-events</td><td>Safari, Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>position</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>print-color-adjust</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>quotes</td><td>Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>region-overflow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>region-break-after</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>region-break-before</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>region-break-inside</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>resize</td><td>Safari, Chrome, Fx</td><td></td><td></td><td></td><td></td></tr>
<tr><td>right</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>rtl-ordering</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>ruby-align</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>ruby-overhang</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>ruby-position</td><td>IE</td><td></td><td></td><td></td><td></td></tr>
<tr><td>scrollbar-3dlight-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-arrow-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-base-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-darkshadow-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-face-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-highlight-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-shadow-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>scrollbar-track-color</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>shape-inside</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>shape-outside</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>size</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>src</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>speak</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>tab-size</td><td>Chrome</td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>table-baseline</td><td></td><td></td><td></td><td></td><td>Opera</td></tr>
<tr><td>table-layout</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>tap-highlight-color</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-align</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-align-last</td><td>IE</td><td></td><td>Fx 12+</td><td>IE</td><td></td></tr>
<tr><td>text-autospace</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>text-combine</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-decoration</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-decoration-color</td><td></td><td></td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>text-decoration-line</td><td></td><td>Chrome</td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>text-decoration-skip</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-decoration-style</td><td></td><td>Chrome</td><td>Fx 6+</td><td></td><td></td></tr>
<tr><td>text-decorations-in-effect</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-color</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-position</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-emphasis-style</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-fill-color</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-indent</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-justify</td><td>IE</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>text-kashida-space</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>text-line-through</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-color</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-mode</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-style</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-line-through-width</td><td>*Chrome*</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-orientation</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-overflow</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>text-overflow-ellipsis</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overflow-mode</td><td>Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-color</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-mode</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-style</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-overline-width</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-rendering</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-security</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-shadow</td><td>Safari, Chrome, Fx, IE 10, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-size-adjust</td><td></td><td>Safari iOS, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke-color</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-stroke-width</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>text-transform</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-color</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-mode</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-position</td><td></td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>text-underline-style</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>text-underline-width</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>top</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>touch-callout</td><td></td><td>Safari iOS</td><td></td><td></td><td></td></tr>
<tr><td>transform</td><td>IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td>IE 9</td><td>Opera</td></tr>
<tr><td>transform-origin</td><td>IE 10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td>IE 9</td><td>Opera</td></tr>
<tr><td>transform-origin-x</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>transform-origin-y</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>transform-origin-z</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>transform-style</td><td>IE 10</td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>transition</td><td>IE 10, Opera 12.10+</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>transition-delay</td><td>IE 10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>transition-duration</td><td>IE 10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>transition-property</td><td>IE 10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>transition-timing-function</td><td>IE 10</td><td>Safari, Chrome, Opera</td><td>Fx</td><td></td><td>Opera</td></tr>
<tr><td>unicode-bidi</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>unicode-range</td><td>Safari, Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>user-drag</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>user-modify</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>user-select</td><td></td><td>Safari, Chrome</td><td></td><td></td><td></td></tr>
<tr><td>user-zoom</td><td>Chrome</td><td></td><td></td><td></td><td></td></tr>
<tr><td>vertical-align</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>visibility</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>white-space</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>widows</td><td>Safari, Chrome, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>width</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>window-shadow</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td>word-break</td><td>Safari, Chrome, IE</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>word-spacing</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>word-wrap</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td>IE</td><td></td></tr>
<tr><td>wrap</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>wrap-flow</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>wrap-margin</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>wrap-padding</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>wrap-through</td><td></td><td>Chrome</td><td></td><td></td><td></td></tr>
<tr><td>writing-mode</td><td>IE</td><td>Chrome</td><td></td><td>IE</td><td></td></tr>
<tr><td>z-index</td><td>Safari, Chrome, Fx, IE, Opera</td><td></td><td></td><td></td><td></td></tr>
<tr><td>zoom</td><td>Safari, Chrome</td><td></td><td></td><td>IE</td><td></td></tr>
</tbody>
<table>

## Reference

[CSS properties supported by Mozilla](https://developer.mozilla.org/en-US/docs/Mozilla_CSS_support_chart)    
[CSS properties supported by Apple](http://developer.apple.com/library/safari/#documentation/appleapplications/reference/safaricssref/articles/standardcssproperties.html)    
[CSS properties supported by Microsoft](http://msdn.microsoft.com/en-us/library/windows/apps/hh767304.aspx)    
[CSS properties recognized by Webkit](http://trac.webkit.org/browser/trunk/Source/WebCore/css/CSSPropertyNames.in)
