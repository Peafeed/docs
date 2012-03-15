# Designing for Different Devices

## Retina screens

Devices such as iPad and iPhone have hi-DPI screens, which have a pixel density of about twice their normal sisters. Peafeed fires a JavaScript function when the page has loaded that can replace image sources with a different image, and retain the width and height.

Use the HTML5 property `data-retina` to indicate the URI of the hi-DPI image.

~~~
<img src="http://domain.com/logo.png" alt="My Logo" data-retina="http://domain.com/logo@2x.png" />
~~~

In the example above I’ve used the naming convention `@2x`, but you could use your own system keeping them in a different folder or alike.

TODO: Domain setting to apply one rule to all images.