:index:`Kernel density <single: Kernel density>`
================================================

A useful tool to visualize the density of a point layer it is the Heatmap. In QGIS, we can directly use a styling option of the layer.

    + Right-click the :file:`places_clip` layer on the Layers panel
    + Select Properties
    + In the menu on the left, select "Symbology"

    .. image:: ../img/3.6_simbology.PNG
        :width: 800px
    
    |

    + In the dropdown menu on top, select Heatmap

    .. image:: ../img/3.6_simbology_heatmap.PNG
        :width: 800px

    |

    + Now you only have to choose the parameters:

        - Color ramp: reds
        - Radius and radius unit of measure: 10 millimetres
        - Maximum value (leave Automatic)

    .. image:: ../img/3.6_heatmap_parameters.PNG
        :width: 800px

    |

    + Then click OK button on the bottom

    The result is the visualization of the places layer as a heatmap:

    .. figure:: ../img/3.6_heatmap_result.PNG
        :width: 100%

        Comparison between the heatmap and a copy of the :file:`places_clip` layer with the point symbology