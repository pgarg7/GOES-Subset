# GOES-Subset
Code to subset a given GOES 16/17 data within a given lat-lon box 

This notebook provides a working example of utilizing [goes2go](https://blaylockbk.github.io/goes2go/_build/html/user_guide/index.html) package developed by Dr. Brian Blaylock (University of Utah) to read, process, and subset a given GOES 16/17 file around a given lat-lon box. The data is obtained from [GOES AWS Server](https://noaa-goes16.s3.amazonaws.com/index.html). <br />
The method to find latitude and longitudes of a given GOES image projection is derived from [Grid Projection mathematics of GOES](https://makersportal.com/blog/2018/11/25/goes-r-satellite-latitude-and-longitude-grid-projection-algorithm).<br />
I would therefore wish to acknowledge both the sources used to create a working example of fetching the data from AWS and the post-process it to include latitude and longitude information in order to subset the data within a given box. 
