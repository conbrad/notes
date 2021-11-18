---
id: skuK3wKzCehUeboW5rWfq
title: Gis
desc: ""
updated: 1637261628763
created: 1637261483839
---

### OGR

- OGR used to stand for OpenGIS Simple Features Reference Implementation.
- See: https://trac.osgeo.org/gdal/wiki/FAQGeneral#WhatdoesOGRstandfor

#### Shapfile to GeoJSON

`ogr2ogr -f GeoJSON -t_srs crs:84 output.geojson input.shp`
