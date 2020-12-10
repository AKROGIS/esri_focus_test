# Broken Focus Ring Demo

Simple example of keyboard focus styling with [ArcGIS API for javascript](https://developers.arcgis.com/javascript/)

This web page was designed to show esri that the stylesheet in version 3.10 broke accessibility standards by
removing the focus ring (required for keyboard navigation) on not only the map elmenets, but also other
elments on the page.

The index.html describes the problem.  It also provides links to the other 3 pages and describes their purpose
in the demonstration.

Thankfully esri fixed this in a subsequent release of the javascript library.

## Using

1) Clone the repo to your web server or a local file system.
   - The maps will only display if loaded to a web server, however the focus ring behavior is the same regardless.
2) Open index.html in a web browser.
3) Use the tab key to navigate the links and see (or not see) the focus ring.
