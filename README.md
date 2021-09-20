# Spectral-Heatmaps

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
======================

Most everyone is familiar with heatmaps in a general way. It’s hard not to run into them. Let’s consider some variations:

A heatmap is a 2D array of rectangular cells colored by value. Generally, the rows and columns are ordered in some purposeful manner. These are very commonly encountered in microarrays for example.An image is a type of heatmap in which the ordering of the rows and columns is defined spatially – it would not make sense to reorder them. This kind of data arises from the physical dimensions of a sensor, for instance the sensor on a digital camera or a raman microscope. An image might also arise by a decision to subset and present data in a “square” format. An example would be the topographic maps provided by the US government which cover a rectangular latitude/longitude range. This type of data can also be presented as a contour plot. 

A chloropleth is a map with irregular geographic boundaries and regions colored by some value. These are typically used in presenting social or political data. A chloropleth is not really a heatmap but it is often mis-characterized as one.

These three types of plots are conceptually unified in that they require a 3D data set. In the case of the heatmap and the image, the underlying data are on a regular x, y grid of values; mathematically, a matrix. The row and column indices are mapped to the x, y values, and the matrix entries are the z values. A chloropleth can be thought of as a very warped matrix where the cells are not on a regular grid but instead a series of arbitrary connected paths, namely the geographic boundaries. There is a value inside each connected path (the z value), but naturally the specification of the paths requires a completely different data structure.

Wilke Documentation : https://clauswilke.com/dataviz/geospatial-data.html#cartograms

ChemoSpec Refrence : https://bryanhanson.github.io/ChemoSpec/reference/index.html
