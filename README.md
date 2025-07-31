# spatial-r
Tutorials on spatial data analysis in R for ecologists

## Preliminary program
**Day 1**  
- lesson1 : INTRODUCTION GIS, vector vs raster view, projection system (CRS)   
- tuto1 : VECTOR: create points and polygons; map and project spatial objects, calculate distance and areas   
- tuto2 : RASTER: load and download rasters, change their resolutions, map etc   
- tuto3 : EXTRACT: how to mix them: raster and points, raster and buffer, raster and polygons, projection raster>polygon  

**Day 2**  
- lesson2 : INTRODUCTION GIS, vector vs raster view, projection system (CRS)     
- tuto4 : STACK: how to load and manipulate multilayer rasters (e.g. remote sensing), thresholding multi day, and multi spectral   
- tuto5 : COMBINE MULTI-SOURCE DATA - reprojecting rasters, tips and tricks    
- tuto6 : INTERACTIVE maps with leaflet, mapview, or tmap   


**Extra**:  
- tutoE1 : POLYGON: calculate convex hull, simplify geometries, aggregate, union, etc... spatial influence  
- tutoE2 : get data from WMS or WFS  
- tutoE3 : spatial autocorrelation - how to measure it, what to do about it? spatial regression model, local regression  
- tutoE4 : Krigging and interpolation  
- tutoE5 : remote sensing, landsat and modis  
- tutoE6 : GoogleEarthEngine, what it is and how to use it (mostly out of R)



## technical notes
```
quarto publish gh-pages
```

## Inspiration

https://github.com/rspatial/rspatial-terra-web
https://github.com/edzer/sdsr/