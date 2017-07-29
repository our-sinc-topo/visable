# visable![Science of Where](https://media.licdn.com/media/AAEAAQAAAAAAAAxMAAAAJGU5OTMyZjM3LWQyYmQtNGNmZC1hOWFmLWMyOTk0ZWM5MzhhZA.png)

## Description
Created as part of the Esri intern hackathon and earning the 1st Place Award, this is a Chrome browser extension that parses out geographic locations in your active tab and lets you visualize them on a WebGL globe using Esri's JavaScript API. It is intended to visually contextualize page content and enhance geoliteracy with minimal overhead by seamlessly integrating into your daily workflow in Chrome.

## Dates
July 21, 2017 - July 23, 2017

## Team Name & Members:
_Our Sincerest Topologies_:
* __Evgeni Dobranov__: HTML parsing, Chrome extension build and central front/back end integration
* __Thomas Binu__: Visualization, geocoding, and interfacing with ArcGIS JavaScript API
* __Gracen Hanley__: ArcGIS Online integration, UI/UX design, and demonstration
* __Cyrus Maden__: Spatial Analysis/GIR, UI/UX design, and demonstration
* __Ankur Rastogi__: NLTK setup, customization, and Flask web microframework

## Installation Instructions
1) Either download & extract, or simply clone this repo to your computer using `git clone <repository name here>`.
2) Type `chrome://extensions` in your Chrome browser's URL bar and hit enter.
3) Check `Developer Mode` in the upper right hand corner of the extensions page.
4) Hit `Load unpacked extension...` on the upper left hand side.
5) Navigate to the root directory of the extension and select it (should have the `manifest.json` file there).
6) Try it out by going to a page and clicking the extension's icon!

## Technologies Used
#### Front End
* [Chrome Extension Dev Environment](https://developer.chrome.com/extensions): Core integration & functionality
* [Bootstrap](http://getbootstrap.com/): CSS and styling for smaller extension display
* [jQuery](https://jquery.com/): Simplify POST requests, element listeners and manipulation, etc.
* [Planetary.js](http://planetaryjs.com/): Loading icon
* [Esri JavaScript API v4.4](https://developers.arcgis.com/javascript/): [Geocoding](https://developers.arcgis.com/features/geocoding/), [geographic enrichment](https://developers.arcgis.com/features/geo-enrichment/), and 3D mapping via SceneView
* [ArcGIS Online](https://www.arcgis.com/home/index.html): In-extension maps, layers, scenes, etc. browsing

#### Back End
* [NLTK](http://www.nltk.org/) - Python natural language processing platform to perform geoparsing
* [Flask](http://flask.pocoo.org/) - Web microframework to host Python programs
* [ngrok](https://ngrok.com/) - Serve localhost Flask server for initial demo purposes
