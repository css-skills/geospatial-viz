# Geospatial visualizations with R

## Overview

R contains many different packages for importing, structuring, and visualizing geospatial datasets. In this workshop we will consider two workflows for drawing geospatial data visualizations (aka data maps). In the first method we will obtain pre-generated mapping tiles from sources such as Stamen Maps using the `ggmap` package. With the second method, we will use spatial data files which contain detailed information to draw all the components of a map (e.g. points, lines, polygons) using the simple features framework and the `sf` package. These methods integrate directly into tidy workflows and visualization methods such as `ggplot2`.

## Objectives

- Introduce the major components of a geospatial visualization
- Identify how to obtain map tiles using `ggmap` and `get_map()`
- Generate plots overlaying data on raster map tiles
- Define common data structures for storing spatial data objects
- Import spatial data using the `sf` package
- Draw maps using `ggplot2` and `geom_sf()`
- Change coordinate systems

## Audience

This workshop is designed for individuals with a basic familiarity using R and `ggplot2` for data visualization.

## Location

Room 295 in [1155 E 60th St](https://goo.gl/maps/7n7wDsd9mjnfRBtR8).

## Prework

- Register for this workshop. Due to the current public health crisis, all participants must register in advance using [this form](https://forms.gle/DUuSYvCdEa2TR2ZR9).
- Please sign up for a free [RStudio Cloud account](https://rstudio.cloud).
- If you have not participated in a previous workshop meeting, [join the workshop organization.](https://rstudio.cloud/spaces/177434/join?access_code=cGV7c0V8%2Bpr0kFC5NkOX%2FgxNNhIm3PchWX1CjdBf)

## Links

- [Source materials for the workshop on GitHub](https://github.com/css-skills/geospatial-viz)

To download these materials to your local computer, use the code below:

```r
usethis::use_course("css-skills/geospatial-viz")
```
