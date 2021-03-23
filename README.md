# OSM Bright Bicycle
[![Build Status](https://api.travis-ci.com/makina-maps/osm-bright-bicycle-gl-style.svg?branch=master)](https://travis-ci.com/github/makina-maps/osm-bright-bicycle-gl-style)

A Mapbox GL Bicycle map build on OpenStreetMap and [OpenMapTiles](https://github.com/openmaptiles/openmaptiles).

## Preview

![](networks.png)

![](facilities.png)

## OpenMapTiles Data Layer

This style require the extra layers from [openmaptiles-contrib-bicycle_hiking_route](https://github.com/makina-maps/openmaptiles-contrib-bicycle_hiking_route).

## Edit the Style

Use the [Maputnik CLI](http://openmaptiles.org/docs/style/maputnik/) to edit and develop the style.
After you've started Maputnik open the editor on `localhost:8000`.

```
maputnik --watch --file style.json
```
