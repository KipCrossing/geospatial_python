# Geospatial Python

These are a collections of discussions and tutorials where we explore concepts and tools for geospatial tasks within the python ecosystem.

## Motivation

### Abstractions

Often, when performing geospatial tasks in python, I find that the tools and practices abstract a lot of the 'behind the scenes' stuff that help up to achieve our goals. Although this is fine for common tasks, we can start to hit limits when trying to achieve a truly innovative or creative solution. Python, being a high-level object-orientated programing language, is full of abstractions. Abstractions, are great as they allow us to cut straight to the problem-solving task without having to learn new standards, specifications, syntax, jargon or logical techniques. I mean, that's why programming languages exist in the first place isn't it? However, in the context of creative geometry, I believe that abstracting the data can limit our understanding of how the data is processed and manipulated and, in turn, limiting our ability to be creative with it. 

It's like any tool, by learning how to use it instead of how it works, we are limited to the features that the tool provides. When developing a tool and trying to maximize both ease of use and flexibility, there becomes a limit were flexibility will be sacrificed for ease of use, or vise versa. For these lesions, I have chosen the packages that, I believe, will keep us close to the data and geometry but abstract a lot of the logic that's required to load, visualize and save it. 

Therefore, many commonly used geospatial python packages will not be included in these discussions as, I believe, they either remove the user too far from the data, are too hard to use or are not designed/tailored for a specific task.


### Usefulness

I'd like you coming away from this feeling like you are more useful to those you work with. Whatever geospatial discipline you are in, from GIS analytics to spatial data science or just starting out, I hope you will come away from this as a geospatial python programmer with the ability to provide quality code that is innovative and ready for integration and production. 

All of these packages are easy to install with pip and therefore you will be able to start writing creative code without hours (or days) of banging you head against the wall trying to debug instillation errors. Having an OS independent approach means your code be run wherever. Aiming for pure-python will allow your code to be pickled and make it scalable friendly.

## Prerequisites 

Must:

- Decent mathematical ability
- Python scripting

Should:

- git

## Table of Contents

### Setting up a Geospatial Python Project

- make a vertical environment
- set up your module
- initialize git
- Install and folium

### Plotting Points on a Map

- Coordinates (lat, lon)
- loading data from file
- Reading and writing text files
- The json module
- The csv package

### Vector

- Shapely
- geojson
- PyShp
- KML

### Raster

- geotiff
- numpy
- xarray (netcdf)
- mercantile and leaflet APIs 

### Conversions 

- utm
- PyProj
- pycrs

### Visualization 

- folium
- Python Imaging Library - pillow
- The svg package
- dash-plotly

### Interpolation and Analysis 

- numpy
- scipy
- xarray
- csaps
- PyKrige
- xarray-spatial

### Processing

- zarr
- dask
- numba
- CuPy
- PyTorch
