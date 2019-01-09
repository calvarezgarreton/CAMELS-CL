# CAMELS-CL

CAMELS-CL is a catchment database developed by [Alvarez-Garreton et al., (2018)](https://www.hydrol-earth-syst-sci.net/22/5817/2018/) for large sample studies in the field of hydro-meteorology. 

CAMELS-CL relies on multiple data sources (including ground data, remote-sensed products and reanalyses) to characterise the hydroclimatic conditions and landscape of Chile, a region where in situ measurements are scarce. The dataset includes 516 catchments and provides boundaries, daily streamflow records and basin-averaged daily time series of precipitation (from one national and three global datasets), maximum, minimum and mean temperatures, potential evapotranspiration (PET; from two datasets), and snow water equivalent. We calculated hydro-climatological indices using these time series, and leveraged diverse data sources to extract topographic, geological and land cover features. Relying on publicly available reservoirs and water rights data for the country, we estimated the degree of anthropic intervention within the catchments. To facilitate the use of this dataset and promote common standards in large-sample studies, we computed most catchment attributes introduced by [Addor et al. (2017)](https://www.hydrol-earth-syst-sci.net/21/5293/2017/) in their Catchment Attributes and MEteorology for Large-sample Studies (CAMELS) dataset (doi:10.5065/D6G73C3Q), and added several others.

This repository contains the codes used to compute catchment attributes, and provides examples on how to download and use the dataset.

Importantly, we will inform here to the community if there is any update in the database.

CAMELS-CL can be visualised from https://camels.cr2.cl.  

### Table of Contents

* [Datasets description](#description)
* [Examples](#examples)
    * [Load and visualise data for single catchment](#IssueTracking)
    * [Load and visualise data for several catchment](#OpenSourceResources)

<a name="Downloading"></a>
