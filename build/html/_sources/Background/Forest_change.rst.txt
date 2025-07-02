Forest Change
=============

Forest Gain/Loss
_________________
The quantification of the forest gain/loss hotspots will be based on pre-existing high-resolution global maps derived from Hansen Global Forest change dataset that can be accessed using `Google Earth Engine API`_. 

    .. _Google Earth Engine API: https://earthenginepartners.appspot.com/science-2013-global-forest

The maps are produced from time-series analysis of Landsat images characterizing forest extent and change over time.

Forest Carbon Emission
________________________
The UNFCCC framework on REDD+ (Reducing Emissions from Deforestation and Forest Degradation in Developing countries) encourages developing countries to take actions for reducing emissions in the forestry sector. For receiving performance-based payments countries need – among others – to implement national forest monitoring systems and mechanisms for Measuring, Reporting and Verification (MRV) of achievements in avoiding deforestation and forest degradation and in related emission savings.

Estimating emissions from deforestation or forest degradation may be based on Activity Data (AD) and on Emission Factors (EF):

.. figure:: ../_static/Images/Service/ef.png
    :width: 235
    :align: center
    :height: 50
    :alt: Forest fires methodology
    :figclass: align-center

    Emission factor equation

Where; `AD` is the change in forest area or in area of degraded forest (in ha) and EF = emissions expressed in tC/ha.


Forest Fire Risk
_________________
The methodological approach that will be adapted to highlight susceptibility to fire integrates Land cover, temperature, slope, proximity to road, proximity to settlement, elevation and Aspect as depicted in the flow diagram below:

.. figure:: ../_static/Images/Service/fireriskflow.png
    :width: 618
    :align: center
    :height: 459
    :alt: Forest fires methodology
    :figclass: align-center

    Fire risk flow


The Land cover layer is used to segment the different vegetation types within the forests acting as fuel load. Surface temperature measures the possibility of ignition. Digital elevation model is employed to derive the probability of spread and sustainability of fire. Additionally, the anthropogenic data is put in place to satiate human induced aspects of fire. 
weighting analysis is applied to combine the individual layers and derive a composite layer depicting susceptibility to forest fire.


Forest Fires
_____________
Burnt areas and forest fires will be highlighted and mapped out form remotely sensed Landsat/Sentinel data using the Normalized Burn Ratio (NBR). NBR is designed to highlight burned areas and estimate burn severity. It uses near-infrared (NIR) and shortwave-infrared (SWIR) wavelengths. Before fire events, healthy vegetation has very high NIR reflectance and a low SWIR reflectance. In contrast, recently burned areas show low reflectance in the NIR and high reflectance in the SWIR band.

The NBR will be calculated for Landsat/Sentinel images before the fire (pre-fire NBR) and after the fire (post-fire NBR). The difference between the pre-fire NBR and the post-fire NBR referred to as delta NBR (dNBR) is computed to highlight the areas of forest disturbance by fire event.

Classification of the dNBR will be used for burn severity assessment, as areas with higher dNBR values indicate more severe damage whereas areas with negative dNBR values might show increased vegetation productivity. dNBR will be classified according to burn severity ranges proposed by the United States Geological Survey(USGS)

.. figure:: ../_static/Images/Forest_fires.png
    :width: 700
    :align: center
    :height: 500
    :alt: Forest fires methodology
    :figclass: align-center

    Sammury methodology for conputing Burnt Areas

.. toctree::
   :maxdepth: 3
