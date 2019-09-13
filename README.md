ggiraph R package
================

[![Build
Status](https://travis-ci.org/davidgohel/ggiraph.svg?branch=master)](https://travis-ci.org/davidgohel/ggiraph)
[![Build
status](https://ci.appveyor.com/api/projects/status/github/davidgohel/ggiraph?branch=master)](https://ci.appveyor.com/project/davidgohel/ggiraph/branch/master)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/ggiraph)](https://cran.r-project.org/package=ggiraph)
![cranlogs](http://cranlogs.r-pkg.org./badges/ggiraph) [![Project
Status: Active – The project has reached a stable, usable state and is
being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

<p align="center">

<img width="15%" src="https://www.ardata.fr/img/hexbin/ggiraph.svg">

</p>

> Make ‘ggplot’ Graphics Interactive

## Overview

`ggiraph` is an htmlwidget and a ggplot2 extension. It allows ggplot
graphics to be interactive, by exporting them as SVG documents and using
special attributes on the various elements.

Interactivity is added to ggplot geometries, legends and theme elements,
via some parameters:

  - `tooltip`: column of dataset that contains tooltips to be displayed
    when mouse is over elements.
  - `onclick`: column of dataset that contains javascript function to be
    executed when elements are clicked.
  - `data_id`: column of dataset that contains id to be associated with
    elements.

If used within a shiny application, elements associated with an id
(`data_id`) can be selected and manipulated on client and server sides.

<iframe width="100%" height="550" src="https://www.youtube.com/embed/cJt5hlCi_do" frameborder="0" allowfullscreen>

</iframe>

## Installation

##### Get development version on github

``` r
devtools::install_github('davidgohel/ggiraph')
```

##### Get CRAN version

``` r
install.packages("ggiraph")
```
