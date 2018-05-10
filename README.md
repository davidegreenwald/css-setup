# Setup.css, a lightweight reset and normalization stylesheet

_A group of CSS reset and normalization files for modern browsers and backwards compatibility_

Meet the **Setup.css** reset:
If you, like me, want to reset everything you possible can, down to `button` fonts... this reset attempts to do that with the most minimal code possible.

This replaces the Eric Meyer reset with tested and targeted resets of box model and typography properties with a few extras. It also draws on the work of [Normalize.css](https://necolas.github.io/normalize.css/) and [Sanitize.css](https://jonathantneal.github.io/sanitize.css/).

Normalizations are organized by browser, not functionality, so you can more easily pick and choose what you need for your project.

This file is 8kb and 2.4kb minified.

Please let me know if you see anything weird, missing, broken, or out of date: david@davidgreenwald.com. This replaces my previous CSS reset projects, Scalpel and Another CSS Reset.

## Setup-basic.css

Like setup.css but for simpler websites: the "basic" version removes normalization support for IE9, older mobile browsers, and some form display styles. If you use and style your own forms and native audio/video, use the regular version.

This file is 5kb and 1kb minified.
