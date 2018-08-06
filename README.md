TGRASS: temporal data processing with GRASS GIS
===============================================

This repo was created for the workshop **Big geodata management and analysis using GRASS GIS** at FOSS4G 2018 in Dar er Salaam (https://2018.foss4g.org//programme/list-of-presentations/).

Abstract
--------

Earth Observation (EO) big data are nowadays easily accessible and consist of long time-spanning data series which are often used to perform different kinds of analysis in several fields of application. During this workshop we will show how to manage and analyze big EO data in a simple way with GRASS GIS using its temporal framework (TGRASS). GRASS GIS is a Free and Open Source geographic information system (GIS) with support for raster, 3D raster and vector data processing. It provides more than 400 core modules, plus hundreds of Add-ons, to run any kind of geographical analysis. GRASS GIS offers a useful graphical interface to make it user friendly like any other desktop GIS software. Importantly, it also offers the capabilities to be used as a backend tool to run analysis in an automatic way, not only in a personal computer, but also within HPC systems. The GRASS GIS temporal framework is composed of more than 60 GRASS GIS modules able to manage, modify, analyse, extract and export big series of data in a really simple way. The workshop will start showing the basics about GRASS GIS and it will continue processing data with the TGRASS. The workshop will be an intuitive mix of theoretical and hands-on sections using MODIS and Copernicus Sentinel-2 data.

First steps
-----------

Software requirements:
* GRASS GIS 7.4: 
 * Stand-alone installer: https://grass.osgeo.org/download/software/
 * OSGeo-live: https://live.osgeo.org/
 
* GRASS GIS Add-ons: 
 * r.modis: https://grass.osgeo.org/grass72/manuals/addons/r.modis
 * v.strds.stats: https://grass.osgeo.org/grass72/manuals/addons/v.strds.stats.html
* pyModis library: http://www.pymodis.org

Sample data:
* North Carolina basic location (50 MB): https://grass.osgeo.org/sampledata/north_carolina/nc_basic_spm_grass7.tar.gz

Register at NASA to be able to download MODIS data (https://urs.earthdata.nasa.gov/users/new). Once registered, log in and go to your profile page. In **My application** tab, approve the following applications *LP DAAC Data Pool* and *Earthdata Search*.

Enjoy! 

Authors
-------

* Veronica Andreo
* Luca Delucchi
* Markus Neteler
* Marco Ciolli

License
-------

The workshop text and images:

* Creative Commons Attribution-ShareAlike 4.0 International License

JavaScript code for tabs and other things:

* BSD 2-Clause License

Some other content is included too:

* jQuery library (MIT license)
* higlight.js (BSD 3-Clause License)
* GRASS GIS CSS file
* Python and CC logos

See specific files for thier licenses.
