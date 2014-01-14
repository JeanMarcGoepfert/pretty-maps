#prettymaps.js

Prettymaps is a lightweight jQuery plugin that allows you to easily set up a basic styled map with jQuery.

##Example

      $('#foo').prettyMaps({
          address: 'Melbourne, Australia',
          image: 'map-icon.png',
          hue: '#FF0000',
          saturation: -20
      });

gives you a map that looks like this.

![](http://i.imgur.com/4Ms2V3f.jpg)

The following options have been set as defaults. Check [google](https://developers.google.com/maps/documentation/javascript/tutorial) for a full list of options.
   
      zoom: 13,
      panControl: false,
      zoomControl: false,
      mapTypeControl: false,
      scaleControl: false,
      streetViewControl: false,
      overviewMapControl: false,
      scrollwheel: true
    
##Requirements

jQuery
Google Maps API Library.

####Including Google Maps API Library:

Load this link in a script tag on your page

http://maps.google.com/maps/api/js?sensor=false

When using the google maps api in production, you'll need to get an API key. 

Follow the 4 steps (should take about 2 minutes) [here](https://developers.google.com/maps/documentation/javascript/tutorial) to get your api key, and include it in the script parameters like so:

      <script src="https://maps.googleapis.com/maps/api/js?key=API_KEY&sensor=false">
    
That's pretty much it, clone the repo and check examples.html for some live examples