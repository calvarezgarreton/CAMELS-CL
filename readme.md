# CAMELS-CL

CAMELS-CL is a catchment database that relies on multiple data sources (including ground data, remote-sensed products and reanalyses) to characterise the hydroclimatic conditions and landscape of Chile, a region where in situ measurements are scarce. The dataset includes 516 catchments and provides boundaries, daily streamflow records and basin-averaged daily time series of precipitation (from one national and three global datasets), maximum, minimum and mean temperatures, potential evapotranspiration (PET; from two datasets), and snow water equivalent. We calculated hydro-climatological indices using these time series, and leveraged diverse data sources to extract topographic, geological and land cover features. Relying on publicly available reservoirs and water rights data for the country, we estimated the degree of anthropic intervention within the catchments. To facilitate the use of this dataset and promote common standards in large-sample studies, we computed most catchment attributes introduced by [Addor et al. (2017)](https://www.hydrol-earth-syst-sci.net/21/5293/2017/) in their Catchment Attributes and MEteorology for Large-sample Studies (CAMELS) dataset (doi:10.5065/D6G73C3Q), and added several others.

CAMELS-CL can be visualised from https://camels.cr2.cl. 

What you will find in this repository:

1) The codes used to compute catchment attributes.
2) Examples on how to download and use the dataset.
3) Information about updates in the dataset.
4) A platform to provide comments, to request specific information (scripts, examples, data sources, etc.), and to inform about bugs and errors found while using the dataset: [Comments & issues](https://github.com/calvarezgarreton/camels-cl/issues) 

Reference: Alvarez-Garreton, C., Mendoza, P. A., Boisier, J. P., Addor, N., Galleguillos, M., Zambrano-Bigiarini, M., Lara, A., Puelma, C., Cortes, G., Garreaud, R., McPhee, J., and Ayala, A.: The CAMELS-CL dataset: catchment attributes and meteorology for large sample studies – Chile dataset, Hydrol. Earth Syst. Sci., 22, 5817-5846, https://doi.org/10.5194/hess-22-5817-2018, 2018. 

### Table of Contents

* [Datasets description](#description)
* [Provide comments, request information and report issues](#issues)
* [Examples](#examples)
    * [Load and visualise data for single catchment](#one_catchment)
    * [Load and visualise data for several catchments](#several_catchments)
* [Codes for computing catchment attributes](#codes)
* [Current applications](#applications)
* [Future work](#future_work)

<a name="description"></a>
### 1. Datasets description

<a name="issues"></a>
### 2. Comments and issues
In this [link](https://github.com/calvarezgarreton/camels-cl/issues), you can provide comments, report bugs and errors and request for specific information (e.g., scripts, examples, data sources) and suggest for examples to be published in the repository. 

To inform about bugs and errors found while using the dataset is critical for generating improved versions of the dataset. One of the main sources of errors is streamflow gauge location (see discussion in [Alvarez-Garreton et al., (2018)](https://www.hydrol-earth-syst-sci.net/22/5817/2018/)), therefore, if a better location (based on field data) is provided we can update all the information for the corresponding catchment.

<a name="examples"></a>
### 3. Examples
We have an example oon how to load and visualise data for single catchment: [github example](https://github.com/calvarezgarreton/camels-cl/blob/master/examples/load_single_catchment.md)

<a name="codes"></a>
### 4. Codes
The codes for computing catchment attributes were obtained from Nans Addor Github (https://github.com/naddor/camels). These codes were used for computing the CAMELS dataset for the US [(Addor et al., 2017)](https://www.hydrol-earth-syst-sci.net/21/5293/2017/)  

<a name="applications"></a>
### 4. Current applications


<a name="future_work"></a>
### 5. Future work
