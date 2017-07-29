# Esri Intern Hackathon Project
![Esri Logo](http://mms.businesswire.com/media/20170317005158/en/570118/4/esri_logo17.jpg)

## Team Name & Members:
_Our Sincerest Topologies_: Thomas Binu, Evgeni Dobranov, Gracen Hanley, Cyrus Maden, Ankur Rastogi

## Dates
July 21, 2017 - July 23, 2017

## Description
A Chrome browser extension that parses out geographic locations in your active tab and lets you visualize them on a WebGL globe using Esri's JavaScript API.

## Installation Instructions
1) Either download & extract, or simply clone this repo to your computer using `git clone <repository name here>`.
2) Type `chrome://extensions` in your Chrome browser's URL bar and hit enter.
3) Check `Developer Mode` in the upper right hand corner of the extensions page.
4) Hit `Load unpacked extension...` on the upper left hand side.
5) Navigate to the root directory of the extension and select it (should have the `manifest.json` file there).
6) Try it out by going to a page and clicking the extension's icon!

## Technologies Used
#### Front End
* [Chrome Extension Dev Environment](https://developer.chrome.com/extensions) - Core integration & functionality
* [Bootstrap](http://getbootstrap.com/) - CSS and styling for smaller extension display
* [jQuery](https://jquery.com/) - Simplify POST requests, element listeners and manipulation, etc.
* [Planetary.js](http://planetaryjs.com/) - Loading icon
* [Esri JavaScript API v4.4](https://developers.arcgis.com/javascript/) - Geocoding & 3D mapping

#### Back End
* [NLTK](http://www.nltk.org/) and [Flask](http://flask.pocoo.org/) - Python server to perform geoparsing
* [ngrok](https://ngrok.com/) - Serve localhost Flask server for initial demo purposes
