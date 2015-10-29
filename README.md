# polymer-bem-test

## Setup

* `$ bower install`
* Open index.html from a local server
* Resizing the browser window reveals the second square doesn't change colour with media query
* Looking at the contents of included shared-styles in dev tools reveals that `.foo--bar` is missing `:not([style-scope]):not(.style-scope)` selector within the media query
