Proximity analysis
==================

We will now focus on operations involving point layers. Please note that QGIS, when clipping a Point layer, also converts 
its geometry type to MultiPoint. This geometry type is not suitable for some of the functions we will use in the next step 
and therefore we see first how to convert the geometry type back to Point.

.. figure:: ../img/3.4_MultiPoint.PNG

    In the information of the :file:`places` layer we can see that its geometry is MultiPoint

Convert geometry type
#####################

    Available at *Processing Toolbox->Vector geometry->Convert geometry type*, it provides an algorithm that allows to convert the 
    MultiPoint features to single Point features. To do so, the input parameters are:

    + *Input layer*: the point layer whose geometry we want to convert. In this example we use the :file:`places` layer
    + *New geometry type*: select Centroids
    + *Converted*: the path and the name of the output vector layer. Note that if left empty a temporary layer will be created

    In order to continue with the following functions, please convert the geometry type for all the point layers.

    .. note:: After you are done with the conversion, you can remove the previous point layers and include in the project only the new ones.

Average Nearest Neighbor
========================