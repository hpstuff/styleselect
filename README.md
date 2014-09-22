# Style Select

Simple, standalone styling for select boxes in modern browsers.

 - **Does not require jQuery**, or any other dependencies.
 - Written in SCSS for easy incorporation in your own code base.
 - Minimal out of the box styling, so you won't have to override anything.
 - Triggers 'change' events on real select boxes so you won't have to change event listeners.

## Demo

There's a live demo of the code in this repo. Just run `http-server` (or whatever your preferred static webserver is) in the current directory.

Open the JavaScript console on the demo page for more instructions.

## Usage:

### SASS

Include `styleselect.scss` in your project.

### JS

Style Select is a require/AMD module:

    var styleSelect = require('styleSelect');

To style a select box:

    styleSelect(selector);

Where `selector` is a CSS selector.

That's all. From then on you'll probably want to tweak styling.

## Credit

Style Select is based on [VisualSelect](https://github.com/LeslieOA/VisualSelect), created for Multplx Attract platform.

Style select adds standalone functionality, lots of bugfixes, docs and a demo, the license has also been changed from WTFPL to the MIT license.
