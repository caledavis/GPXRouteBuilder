<img width="1091" height="103" alt="logo" src="https://github.com/user-attachments/assets/3d326dae-edda-4f20-9d6e-c4be57242e1e" />

## About
Use the tool here: https://caledavis.github.io/GPXRouteBuilder/

Plan a cycling trip with turn-by-turn navigation on your GPS.

This tool was designed for personal use to fill a gap in the tools which currently exist for planning cycling trips.
## What does this do?
There are a lot of online route planners that produce GPX _tracks_. But there are no free ones which allow you to create GPX _routes_. This one does.

In other words, it produces GPX routes where the routes are defined as <rte> and the route points as <rtept> elements.
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
1. Three different maps you can pick from, including a custom Bright map; CyclOSM; and OpenStreetMap;
2. You can plan multi-day cycling trips by dividing the route into segments (and it shows how long each segment is);
3. The export function automatically divides the GPX route up so that each file contains no more than 40 waypoints (which is a limitation of some GPS devices);
4. The option to toggle on and off international, national, regional, and local waymarked cycling routes;
5. The option to upload GPX files as overlays (so, for example, you can see where you've cycled in the past);
6. A greyscale toggle in case the map looks a bit too confusing;
7. An elevation plot;
## How was it made?
This tool was vibe coded with Claude using Sonnet 4.6.

It makes use of other free tools, which are credited in the attributins box.

Because of that, it is free and open-source. No accounts, no costs, no nothing.
