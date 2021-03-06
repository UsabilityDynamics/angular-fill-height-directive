﻿Angular fill-height directive
====

Angular directive to change the height of a div to fill the available space in the window.

Usage
----

Add `fill-height` directive to any block element.

Optional

* To specify the id of an element (such as a footer) whose height should be included in the calculation, use the `footer-element-id` attribute.
* To specify an additional padding amount to use in the height calculation, add a `additional-padding` attribute.
* To specify a debounce wait time in ms (default 250ms), add `debounce-wait` attribute. Use a wait time of 0 to disable.

Example


    <div fill-height footer-element-id="footer" additional-padding="70" debounce-wait="300">
        content goes here
    </div>


Live demo: [anthonychu.github.io/angular-fill-height-directive/demo/](http://anthonychu.github.io/angular-fill-height-directive/demo/)
