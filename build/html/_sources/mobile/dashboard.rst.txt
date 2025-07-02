=================
Dashboard
=================

.. |profile| image:: ../_static/mobile/buttons/accounts.svg
   :height: 32px

.. |notifications| image:: ../_static/mobile/buttons/notification.svg
   :height: 32px

.. |layers| image:: ../_static/mobile/buttons/layers.svg
   :height: 32px

.. |statistics| image:: ../_static/mobile/buttons/statistics.svg
   :height: 32px

.. |basemaps| image:: ../_static/mobile/buttons/basemaps.png
   :height: 32px

.. |tutorial| image:: ../_static/mobile/buttons/tutorial.svg
   :height: 32px

.. |mylocation| image:: ../_static/mobile/buttons/myLocation.svg
   :height: 32px

.. |aoi| image:: ../_static/mobile/buttons/aoi.svg
   :height: 32px

.. |customDraw| image:: ../_static/mobile/buttons/customDraw.svg
   :height: 32px

.. |documentation| image:: ../_static/mobile/buttons/documentation.svg
   :height: 32px

.. |drawPolygon| image:: ../_static/mobile/buttons/drawPolygon.svg
   :height: 32px

.. |erase| image:: ../_static/mobile/buttons/erase.svg
   :height: 32px

Tutorial
-----------------
To see what each button on the dashboard does, click the ``Tutorials`` button |tutorial|. This will change the dashboard's mode to 
tutorials mode labelling all buttons with what they do.

.. raw:: html

    <div style="display: flex; gap: 8px; justify-content: center; align-items: center;">
        <div>
            <img src="../_static/mobile/dashboard.jpg" alt="Dashboard" style="height:500px">
            <p style="text-align: center;"><em>Dashboard</em></p>
        </div>
        <div>
            <img src="../_static/mobile/dashboardTutorial.jpg" alt="Dashboard Tutorial" style="height:500px">
            <p style="text-align: center;"><em>Dashboard Tutorial</em></p>
        </div>
    </div>

Selecting an Area of Interest
-----------------------------
To select an area of interest, click the ``Select Location`` button |aoi|. This will open a dialog from where you can select a country, region
and subregion.

.. raw:: html

    <div style="display: flex; gap: 8px; justify-content: center; align-items: center;">
        <div>
            <img src="../_static/mobile/aoiModal.jpg" alt="AOI dialog" style="height:500px">
            <p style="text-align: center;"><em>AOI Dialog</em></p>
        </div>
        <div>
            <img src="../_static/mobile/dashboardWithBoundary.jpg" alt="Area of Interest" style="height:500px">
            <p style="text-align: center;"><em>Area of Interest</em></p>
        </div>
    </div>

Drawing a Custom Area of Interest
---------------------------------

To draw a custom area of interest, follow the procedure below.
 1. Click the ``Custom Draw`` button |customDraw|.
 2. Click the ``Draw Polygon`` button |drawPolygon| to activate drawing mode.
 3. Tap on the dashboard and a polygon will be drawn automatically with the vertices being the points you tapped on the screen.

.. figure:: ../_static/mobile/dashboardWithCustomAOI.jpg
    :alt: Dashboard with custom AOI
    :height: 500
    :align: center

    *Dashboard with custom AOI*

.. admonition:: Note

    To erase the polygon, click the ``Erase`` button |erase| and the polygon will be erased automatically.
    A minimum of three points is required to create a polygon.


Selecting an indicator
----------------------
To select a layer, click the ``Indicators`` button |layers| to open the indicators dialog.

.. figure:: ../_static/mobile/indicatorsModal.jpg
    :alt: Indicators dialog
    :height: 500
    :align: center

    *Indicators Dialog*

.. admonition:: Note

    An area of interest must be selected before selecting an indicator.

Visulaizing statistics
-----------------------
To visualize statistics, click the ``Statistics`` button |statistics| to open the statistics dialog.

.. figure:: ../_static/mobile/statisticsModal.jpg
    :alt: Statistics dialog
    :height: 500
    :align: center

    *Statistics dialog*

.. admonition:: Note

    An indicator must have been selected before visualizing the statistics.