pdf-scribe
==========

A simple HTML proof of concept to get PDF scribing working.

### Assumptions

PDF file has already converted to individual SVG files by using PDF.js from Mozilla.
Fabric.js will be used.

Run this from a local web server instead of opening the file directly in the browser.
If opened as a file, loading will not work as it depends on a HTTP request.
Also, the background SVG file will not open.

### Future work

Figure out how to integrate this with the Rails project Coursemology.
