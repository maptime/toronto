---
layout: event
category: event
title: MaptimeTO Launch
rsvp: https://www.eventbrite.com/e/maptimeto-launch-event-tickets-11709255699
published: false
---

<script src='https://api.tiles.mapbox.com/mapbox.js/v1.6.3/mapbox.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox.js/v1.6.3/mapbox.css' rel='stylesheet' />

Join us Thursday May 29th for the first ever Maptime meetup in Toronto! Venue space has been generously donated by [Mozilla](http://mozilla.org) at their [community space](http://to.mozillacanada.org/).

<div id='map' class='row8 fill-blue col12 map space-bottom2'></div>
<script>
var map = L.mapbox.map('map', 'tristen.h186knp8')
    .setView([43.6472593973924, -79.39437925815582], 17);

var marker = L.mapbox.featureLayer({
  'type': 'Feature',
  'properties': {
    'title': 'Mozilla Community Space',
    'description': 'Suite 500, 366 Adelaide St W',
    'marker-color': '#ff8888'
  },
  'geometry': {
    'type': 'Point',
    'coordinates': [-79.39437925815582, 43.6472593973924 ]
  }
}).addTo(map);

marker.eachLayer(function(m) {
    m.openPopup();
});
</script>

We'll start promptly at 7pm with an opening presentation on what is Maptime followed by table introductions
with laptops open and dive into some map related projects.

Bring your laptops, enthusiasm, experience, projects and any questions. Beginners encouraged!
