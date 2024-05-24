# awesome-maps-r

This repository aggregates helpful resources for creating maps in `R`.

## Books

- [Analyzing US Census Data - Chapter 5 -Census geographic data and applications in R](https://walker-data.com/census-r/census-geographic-data-and-applications-in-r.html)

- [Big Book of R - Chapter 18 - Geospatial](https://www.bigbookofr.com/geospatial)

- [Geocomputation with R](https://r.geocompx.org)

- [ggplot2: Elegant Graphics for Data Analysis (3e)- Chapter 6 - Maps](https://ggplot2-book.org/maps.html)

- [Spatial Data Science Code With Applications in R](https://r-spatial.org/book/)

## Datasets

- [USGS - Great Lakes and Watershed Shape Files](https://www.sciencebase.gov/catalog/item/530f8a0ee4b0e7e46bd300dd)

## Packages

- `ggplot2`

- `sf` package by Edzer Pebesma is the default toolset for working with geographic data in R.

- `rmapshaper` can simplify polygons and reduce file sizes.

- `rmapshaper` package is a "wrapper around the 'mapshaper' 'JavaScript' library by Matthew Bloch <https://github.com/mbloch/mapshaper/> to perform topologically-aware polygon simplification, as well as other operations such as clipping, erasing, dissolving, and converting 'multi-part' to 'single-part' geometries." The project has a wiki.

- The maps from the `rnaturalearth` package were used to construct the maps here.  According to their [website](https://www.naturalearthdata.com), Natural Earth "is a public domain map dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software." 

- [`USAboundaries`](https://docs.ropensci.org/USAboundaries/) package "includes contemporary state, county, and Congressional district boundaries, as well as zip code tabulation area centroids. It also includes historical boundaries from 1629 to 2000 for states and counties from the Newberry Library’s Atlas of Historical County Boundaries, as well as historical city population data from Erik Steiner’s “United States Historical City Populations, 1790-2010.” The package has some helper data, including a table of state names, abbreviations, and FIPS codes, and functions and data to get State Plane Coordinate System projections as EPSG codes or PROJ.4 strings."

- [`tigris`](https://github.com/walkerke/tigris) package allows users "to directly download and use TIGER/Line shapefiles from the US Census." Tiger/Line shapefiles contain "current geographic extent and boundaries of both legal and statistical entities (which have no governmental standing) for the United States, the District of Columbia, Puerto Rico, and the Island areas."

## Resources

- [Mapshaper](https://mapshaper.org)

- [EPSG Geodetic Parameter Dataset](https://epsg.org/home.html) "contains definitions of coordinate reference systems and coordinate transformations which may be global, regional, national or local in application."

- [Mapshaper](https://mapshaper.org)

- [Map Projection Explorer](https://www.geo-projections.com)

- [Projection Wizard](https://projectionwizard.org/#)

- [Proj](https://proj.org/en/9.4/) "supports more than a hundred different map projections and can transform coordinates between datums using all but the most obscure geodetic techniques."

## Contribute

Contributions are always welcome! Please read the contribution [guidelines](./CONTRIBUTIONS.MD) first.

## License

![](./img/cc-zero.svg)

`awesome-maps-r` by Rob Wiederstein is marked with CC0 1.0.  See the [`LICENSE.md`](./LICENSE.MD) for more details.
