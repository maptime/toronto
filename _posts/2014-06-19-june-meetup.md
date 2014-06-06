---
layout: event
category: event
title: Web Maps 101: Presentation and Workshop
rsvp: https://www.eventbrite.com/e/maptime-toronto-june-2014-tickets-11883857939?aff=site
---

<script src='https://api.tiles.mapbox.com/mapbox.js/v1.6.3/mapbox.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox.js/v1.6.3/mapbox.css' rel='stylesheet' />

Join us Thursday June 19th for the next Maptime Toronto! Venue space has been generously donated by [Mozilla](http://mozilla.org) at their [community space](http://to.mozillacanada.org/).

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

Building on the success of our first #maptime event and incorporating feedback from it, we present the June 2014 MaptimeTO. We're doing a combination Workshop and Hack. 

<h2>Presentation: Web Maps 101!</h2>

A short presentation will introduce the broad potential for telling your stories with web maps. The presentation will introduce web mapping concepts and techniques to beginners, and will also be entertaining for the experts in the room.

<h2>Beginners' Workshop: Build your first web map.</h2> 
The remainder of the evening will allow workshoppers to build their first web map, either as self learners, gently guided, or with peer-coaching. Prerequisites: Workshoppers are expected to know how to create a web page, html / xml, and css. Workshoppers should bring their own laptop computer with wifi connectivity. #Maptime Hack

Intermediate and advanced attendees will work on their own projects, collaborate and network. #maptime at its best. #maptimers should bring their laptops and projects.

Doors at 6:30 with the action starting shortly after. 

Bring your laptops, enthusiasm, experience, projects and any questions. Beginners encouraged!
