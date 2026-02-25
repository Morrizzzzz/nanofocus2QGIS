# Processing Confocal Microscopy data using GIS tooling and analysis methods

*Memo dr. Maurice de Kleijn*

## Context
During the site visit of the archaeology department from RCE Amersfoort at the Rijkserfgoed lab in Amsterdam on the 29th of January an archaeology colleague brought a Bronze Tin Axe dating 1600-1400 BCE (figure 1). Liesbeth was interested to know if instruments at the Rijkserfgoedlab could help her to answer the question if the cut/edge of the axe has been sharpend or hammering. 

![figure 1 - Bronze Tin Axe 1600-1400 BCE](/images/fig1.jpg)

One of the instruments that was used to gain a better understanding on whether the axe was hammered or sharpend was a Mahr Confocal Microscope (figure 2). 

![figure 2 -  Bronze Tin Axe placed under Mahr Confocal Microscope](/images/fig2.jpg)

The data that came out of the microscope was then processed in a dedicated software package (MarSurf? By Mahr) which allows to explore the data visually and make cross sections (figure 3). 

![figure 3 -  Data exploration in MarSurf](/images/fig3.jpg)

When Maurice saw the data and software it directly reminded him of GIS tooling. The outcome data looks like a Digital Elevation Model ([DEM](https://en.wikipedia.org/wiki/Digital_elevation_model) ). Therefore, Maurice proposed to explore a series of GIS analysis methods to see what possible new insights these could provide. This memo provides an overview of GIS methods that have been explored to analyse Confocal Microscopy data. 


## Getting the data into GIS software:
The RCE-lab colleague shared an export of the Axe in .csv format as show below:

```# NanoFocus AG Topography
# PointsX: 1199
# PointsY: 1199
# DeltaX: 1.34774
# DeltaY: 1.34734
# Unit: 1e-06
# X,Y,Z,Intensity,Mask
0,0,-10.8702,2174,1
1.34774,0,-13.294,1472,1
2.69549,0,-12.6749,926,1
4.04323,0,-11.3976,746,1
…
```

Since we foremost want to explore the data Maurice’s first approach is to add the data to QGIS. All processing in QGIS can also be done using jupyter notebooks, which is worth to explore, but would require a bit more time to do so.
Using GenAI I created a QGIS plugin with which the data can easily be loaded into QGIS. This plugin can be accessed here = >  





