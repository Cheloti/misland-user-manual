=====================
Vegetation Loss/Gain
=====================

.. |calculate| image:: ../_static/calculate.png
   :height: 32px

**1.** To start the vegetation degradation analysis, click the **calculate** icon highlighted |calculate|. This will open the **calculate** dialog.

.. figure:: ../_static/calculateVegetation.png
    :alt: Calculate Dialog
    :align: center

    *Figure 25: Calculate Dialog*

**2.** From here, click on the ``Vegetation Loss/Gain`` button highlighted in red. This will open the ``Vegetation Loss/Gain Dialog``.
Provide all parameters as required in the dialog and click ``Submit``.

.. figure:: ../_static/vegetation.png
    :alt: Vegetation Loss/Gain Dialog
    :align: center

    *Figure 26: Vegetation Loss/Gain Dialog*

.. admonition:: Note

    MISLAND allows users to assess vegetation using high resolution Landsat derived vegetation indices. If the selection of the data 
    is **Landsat** the option to specify the vegetation index .i.e NDVI, MSAVI or SAVI will appear under the ``Advanced Parameters`` option.

    .. figure:: ../_static/vegetationAdvanced.png
        :alt: Advanced Parameters
        :align: center

.. important::

    .. list-table:: Vegetation Loss/Gain Parameters
        :width: 100%
        :widths: 25 75
        :header-rows: 1

        * - Parameters
          - Definition
        * - Data Source
          - The data source to users
        * - Vegetation index
          - Vegetation Index of choice
        * - Reporting year
          - Year of analysis

**4.** The result will be as shown below.

.. figure:: ../_static/results/QGIS/vegetationLossResult.png
    :alt: Vegetation Loss/Gain Results
    :align: center

    *Figure 27: Vegetation Loss/Gain Results*