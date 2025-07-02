Calculate Vegetation Loss/Gain indicators
==========================================

To compute vegetation loss/gain on the service platform,

1. On the services menu, select the |veglossicon| option 

.. figure:: ../_static/Images/vegetation_gain_loss.png
    :width: 705
    :align: center
    :height: 374
    :alt: Vegetation gain/loss service
    :figclass: align-center

    Selecting the vegetation Loss/Gain Service

2. Click on the |cog| icon to open the layer settings dialog and select the data source and reporting year as shown below.

.. figure:: ../_static/Images/vegetation_gain_loss3.png
    :width: 711
    :align: center
    :height: 234
    :alt: vegetation gain/loss
    :figclass: align-center

    Vegetation gain/loss outputs

To compute vegetation indices using Landsat derived vegetation indices(NDVI, MSAVI, SAVI), 

1. On the Vegetation loss/gain dialog, select Landsat under the SELECT DATA SOURCE dropdown and click on the |advancedparameters| options to access the list of indices.

.. figure:: ../_static/Images/Service/landsat.png
    :width: 709
    :align: center
    :height: 381
    :alt: Vegetation gain/loss service
    :figclass: align-center

    Selecting the Landsat-derived vegetation index option

2. select the vegetation index form the SELECT VEGEATATION INDEX dropdown that is revealed. Select the reporting period before clicking on the |submit| button.

.. figure:: ../_static/Images/Service/vegindex.png
    :width: 349
    :align: center
    :height: 372
    :alt: select vegetation index
    :figclass: align-center

    Choosing the vegetation index to compute

The map and computed statistics will be displayed on the map panel and summary pannel respectively.

.. figure:: ../_static/Images/Service/landsat_vegetation_loss.png
    :width: 712
    :align: center
    :height: 394
    :alt: register
    :figclass: align-center

    Landsat derived vegetation loss and gain output

.. toctree::
   :maxdepth: 3


.. |advancedparams| image:: ../_static/Images/Service/advanceparams.png
.. |submit| image:: ../_static/Images/Service/submit.png
.. |veglossbutton| image:: ../_static/Images/Service/veglossbutton.png
.. |veglossicon| image:: ../_static/Images/Service/veglossicon.png
.. |advancedparameters| image:: ../_static/Images/advancedparameters.png
.. |cog| image:: ../_static/Images/Service/cog.png