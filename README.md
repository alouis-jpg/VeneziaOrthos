# Venezia ortho photos

This is a temporary github page to display Venezia ortho photos.

### Run things locally

To serve the static files locally, a webserver must be run locally so the ajax request to get the tiles don't trigger CORS issues.

For example, it is possible to use node module `http-server`:
`
npm install -g http-server
http-server
`

Then, open https://localhost:8080 in a browser to be served index.html 
If the dzi are not accessible on this repo's github page, replace tileSources endpoint `https://alouis-jpg.github.io/VeneziaOrthos/DZI/$filename` with `http://localhost:8080/DZI/$filename`