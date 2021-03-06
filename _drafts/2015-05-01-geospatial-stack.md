---
name: ropensci-geospatial-stack
layout: post
title: Overview of the rOpenSci geospatial stack
date: 2016-03-10
authors:
  - name: Scott Chamberlain
tags:
- R
- API
- geo
- spatial
---



Geospatial data input/output, manipulation, and vizualization are tasks that are common to many disciplines. Thus, we're keenly interested in making great tools. We have an increasing set of spatial tools.

## geojsonio

<span class="label label-warning">downloads</span>

[geojsonio](https://github.com/ropensci/geojsonio) - A tool for converting to and from geojson data. For example:


```r
library("geojsonio")
'xxx'
#> [1] "xxx"
```
## wellknown

[wellknown](https://github.com/ropensci/wellknown) - A tool for converting to and from well-known text data. For example:


```r
library("wellknown")
'xxx'
#> [1] "xxx"
```

## gistr

[gistr](https://github.com/ropensci/gistr) - This is not a geospatial tool per se, but it's extremely useful for sharing maps. For example, with just a few lines, you can share an interactive map to GitHub.


```r
library("gistr")
'xxx'
#> [1] "xxx"
```

## lawn

An R client for [turf.js](http://turfjs.org/).


```r
library("lawn")
'xxx'
#> [1] "xxx"
```

## proj

An R client for [proj4js](https://github.com/proj4js/proj4js), a Javascript library for projections.

Main features:

* x
* y
* z

## Maps

There's an increasing number of options for mapping in R. rOpenSci has two offerings in this space: `plotly` and `cartographer`.

### plotly

[plotly](https://github.com/ropensci/plotly) is an R client for [Plotly](https://plot.ly/) - a web interface and API for creating interactive graphics.


```r
library("plotly")
'xxx'
#> [1] "xxx"
```

### cartographer

[cartographer](https://github.com/ropensci/cartographer) - xxdasfaff. For example:


```r
library("cartographer")
'xxx'
#> [1] "xxx"
```

## Maptools Task View

[Jeff Hollister](http://jwhollister.com/) is leading the [maptools task view](https://github.com/ropensci/maptools) to organize R mapping tools packages, sources of data, projections, static and interactive mapping, data transformation, and more.
