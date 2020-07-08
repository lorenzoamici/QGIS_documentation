Preparation
===========

In this section we will show all the necessary setup steps in order to follow along the QGIS exercise.

Install QGIS
###############

Download QGIS 3.10 (Long Term Release) for Windows 64bit at `<https://qgis.org/downloads/QGIS-OSGeo4W-3.10.6-1-Setup-x86_64.exe>`_. 
Other versions are available in the `QGIS Download page <https://qgis.org/en/site/forusers/download.html>`_.

.. note:: After downloading QGIS, you will have various option to launch the program, as you see in this image:
          In order to complete this exercise be sure to launch the one with GRASS since we will need some 
          functionalities that are only available using the tools that GRASS offers.

Download the data
####################

Create a new project
####################

Before starting with the analysis of the data, we have to set up a new Project. To do so, run QGIS with GRASS and click on *New Project* (or press :kbd:`Ctrl+N`).

#. **Import vector data**
    To import vector data, go to *Layer->Add layer->Add vector layer* or use the Browser panel (usually placed above the Layer Panel on 
    the left side of the screen; if not, you can enable it by clicking *View->Panels* and tick “Browser panel”). In the Browser, you can 
    search the data folder and simply drag and drop the files in the map.
    For this excercise, we will use the following layers:

    + :file:`buildings_a.shp`
    + :file:`landuse_a.shp`
    + :file:`natural.shp`
    + :file:`places.shp`
    + :file:`pofw_a.shp`
    + :file:`pois_a.shp`
    + :file:`roads.shp`
    + :file:`water_a.shp`

#. **Import raster data**
    To import raster data, you can go to *Layer->Add layer->Add raster layer* or drag and drop them from the Browser panel.
    For this exercise, you can add the following data:

    + :file:`Seoul_DTM.tif`