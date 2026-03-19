# GPXRouteBuilder
Use the tool here: https://caledavis.github.io/GPXRouteBuilder/

Plan a cycling trip with turn-by-turn navigation on your GPS.

This tool was designed for personal use to fill a gap in the tools which currently exist for planning cycling trips.
## What does this do?
There are a lot of online route planners that produce GPX _tracks_. But there are no free ones which allow you to create GPX _routes_. This one does.
## What are GPX waypoints, tracks, and routes?
A GPX file contains waypoints, tracks, and routes. They serve different purposes.
- A waypoint is simply a point on a map, such as a cafe or your home address.
- A track is like a trail of breadcrumbs. It is just a line on a map.
- A route is basically a series of waypoints.
## Why are routes more useful than tracks for planning cycling trips?
When you tell your GPS to navigate along a _route_, the GPS itself figures out the best way to get between the different waypoints. This is really handy because:
1. If you have a routable map on your GPS (such as one from https://www.openfietsmap.nl), your GPS will navigate you along roads;
2. If a road is closed for whatever reason (or you get lost), your GPS will navigate you along roads back to the route;
3. You can set your GPS up to keep the screen off and to only turn it on and beep whenever a turn is approaching, so you don't have to be looking at your GPS the whole time.

Navigating along _tracks_, however, is not good for navigation because:
1. Even if you have a routable map on your GPS, the track is not 'snapped' to the roads;
2. Your GPS will not provide turn-by-turn navigation, meaning you have to be 'head down' in your GPS the whole time to make sure you don't miss a turn.
## Handy Features
1. Three different routing engines you can pick from which make routes appropriate for cyclists (which can even be toggled off entirely);
2. You can choose whether you want to see the CyclOSM map or the OpenStreetMap;
3. The option to toggle on and off international, national, regional, and local waymarked cycling routes;
4. The option to upload GPX files as overlays (so, for example, you can see where you've cycled in the past);
5. A greyscale toggle in case the map looks a bit too confusing.
## How was it made?
This tool was vibe coded with Claude using Sonnet 4.6.

Because of that, it is free and open-source. I have no programming skills to speak of, and the only way I was able to put this together was by using an AI model which was (in all likellihood) trained on stuff made by other people with infinitely more skills than me. 
