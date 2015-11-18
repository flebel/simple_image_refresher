# Simple Image Refresher

SIR is a lightweight JavaScript implementation of an image resource automatic refresher. Rather than
making use of a meta refresh tag, it uses JavaScript to refresh an image resource at a regular
interval.

## Configuration

The image resource and refresh frequency can be set through query string parameters.

`img` is used to pass an URL to an image resource, URI-encoded if necessary.

`freq` is the refresh frequency in milliseconds.

Example::

    http://localhost:8080?img=http://test.com/img.jpg&freq=1000

