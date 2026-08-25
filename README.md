# Awesome Environmental Science

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of awesome open-source projects, datasets, papers, and learning
resources for **environmental science** — spanning the atmosphere, hydrosphere,
cryosphere, biosphere, land, climate, energy, pollution, and the data-science
tooling used to study them.

The goal is to help researchers, students, and practitioners quickly find
high-quality, actively maintained resources instead of digging through search
results. Every entry is expected to have a public source (GitHub repository,
official data portal, or stable paper link).

## Contents

- [Atmosphere](#atmosphere)
- [Hydrosphere](#hydrosphere)
- [Cryosphere](#cryosphere)
- [Biosphere](#biosphere)
- [Land and Soil](#land-and-soil)
- [Climate Change](#climate-change)
- [Energy and Sustainability](#energy-and-sustainability)
- [Pollution and Environmental Health](#pollution-and-environmental-health)
- [Remote Sensing and GIS](#remote-sensing-and-gis)
- [Environmental Data Science and AI](#environmental-data-science-and-ai)
- [Datasets](#datasets)
- [Papers and Journals](#papers-and-journals)
- [Courses, Books, and Communities](#courses-books-and-communities)
- [Contributing](#contributing)
- [License](#license)

## Atmosphere

*Meteorology, air quality, atmospheric chemistry, and climate modeling.*

- [WRF](https://github.com/wrf-model/WRF) - The Weather Research and Forecasting model, a widely used mesoscale numerical weather prediction and atmospheric simulation system.
- [CMAQ](https://github.com/USEPA/CMAQ) - The EPA's Community Multiscale Air Quality model for simulating ozone, particulates, toxics, and deposition.
- [GEOS-Chem](https://github.com/geoschem/geos-chem) - Global 3-D atmospheric chemistry model for composition, aerosols, and air-quality research.
- [MPAS-Model](https://github.com/MPAS-Dev/MPAS-Model) - Model for Prediction Across Scales, a global and regional atmospheric model with variable-resolution meshes.
- [UFS Weather Model](https://github.com/ufs-community/ufs-weather-model) - NOAA's Unified Forecast System model for operational weather prediction.
- [ClimaX](https://github.com/microsoft/ClimaX) - Foundation model for weather and climate, pre-trained on CMIP6 and ERA5 for forecasting and downscaling.

## Hydrosphere

*Hydrology, oceanography, water quality, and coastal systems.*

- [MODFLOW 6](https://github.com/MODFLOW-USGS/modflow6) - The USGS modular hydrologic model for simulating groundwater flow and contaminant transport.
- [SWMM](https://github.com/USEPA/Stormwater-Management-Model) - The EPA Storm Water Management Model for urban runoff, drainage, and water quality.
- [EPANET](https://github.com/OpenWaterAnalytics/EPANET) - Open-source engine for hydraulic and water-quality modeling of water distribution networks.
- [Delft3D](https://github.com/Deltares/Delft3D) - Deltares' open-source suite containing both Delft3D 4 and Delft3D Flexible Mesh kernels for hydrodynamics, water quality, and morphology.
- [NEMO](https://forge.nemo-ocean.eu/nemo/nemo) - Nucleus for European Modelling of the Ocean, the community ocean model for dynamics, biogeochemistry, and sea ice.
- [MITgcm](https://github.com/MITgcm/MITgcm) - General circulation model used for both atmospheric and oceanic research.
- [VIC](https://github.com/UW-Hydro/VIC) - Variable Infiltration Capacity macroscale hydrologic model for water and energy balance.
- [Thetis](https://github.com/ThetisProject/thetis) - Unstructured-grid coastal ocean model built on the Firedrake finite-element framework.

## Cryosphere

*Glaciers, ice sheets, sea ice, snow, and permafrost.*

- [OGGM](https://github.com/OGGM/oggm) - Open Global Glacier Model for simulating glacier evolution and past and future change.
- [PISM](https://github.com/pism/pism) - Parallel Ice Sheet Model for ice sheets, ice shelves, and glaciers at high resolution.
- [CISM](https://cism.github.io/) - Community Ice Sheet Model, the ice-dynamics component of CESM, for sea-level-rise projections.
- [Elmer/Ice](https://github.com/elmercsc/elmerfem) - Full-Stokes ice-flow model built on the Elmer multiphysics software.

## Biosphere

*Ecology, biodiversity, vegetation, forests, and wildlife.*

- [biomod2](https://github.com/biomodhub/biomod2) - R platform for ensemble species distribution modeling (SDM) and biodiversity projections.
- [rgbif](https://github.com/ropensci/rgbif) - R interface to the Global Biodiversity Information Facility (GBIF) API.
- [pygbif](https://github.com/sckott/pygbif) - Python client for the GBIF API.
- [iNaturalist](https://github.com/inaturalist/inaturalist) - Open-source citizen-science platform for recording and identifying organisms.
- [PyTorch-Wildlife](https://github.com/microsoft/Pytorch-Wildlife) - Collaborative deep-learning framework and model zoo for conservation and wildlife monitoring.
- [MegaDetector](https://github.com/microsoft/CameraTraps) - AI for detecting animals, people, and vehicles in camera-trap imagery.
- [BirdNET-Analyzer](https://github.com/kahst/BirdNET-Analyzer) - Deep-learning tool for automated bird sound identification.
- [FATES](https://github.com/NGEET/fates) - Functionally Assembled Terrestrial Ecosystem Simulator for vegetation dynamics in land models.

## Land and Soil

*Soil science, land use and land cover, and land degradation.*

- [DSSAT](https://github.com/DSSAT/dssat-csm-os) - Decision Support System for Agrotechnology Transfer, simulating 45+ crops.
- [ApsimX](https://github.com/APSIMInitiative/ApsimX) - APSIM Next Generation, a framework for agricultural and environmental simulation.
- [AquaCrop](https://github.com/KUL-RSDA/AquaCrop) - FAO crop-water productivity model for irrigation and yield simulation.
- [SoilGrids250m](https://github.com/ISRICWorldSoil/SoilGrids250m) - Global soil property predictions at 250 m resolution from ISRIC.
- [apsimx](https://github.com/femiguez/apsimx) - R interface to the APSIM Next Generation model.

## Climate Change

*Global warming, the carbon cycle, mitigation, and adaptation.*

- [CESM](https://github.com/ESCOMP/CESM) - Community Earth System Model, a fully coupled global climate model.
- [ESMValTool](https://github.com/ESMValGroup/ESMValTool) - Community tool for evaluating Earth system models against observations.
- [CDO](https://code.mpimet.mpg.de/projects/cdo) - Climate Data Operators for standard processing and analysis of climate and NWP data.
- [NCO](https://github.com/nco/nco) - NetCDF Operators for manipulating and analyzing geoscientific data.
- [GCAM](https://github.com/JGCRI/gcam-core) - Global Change Analysis Model, an integrated assessment model for energy, land, and climate policy.
- [MESSAGEix](https://github.com/iiasa/message_ix) - IIASA's framework for integrated energy-economy-environment modeling.
- [pyam](https://github.com/IAMconsortium/pyam) - Python package for analysis and visualization of integrated-assessment and climate scenarios.

## Energy and Sustainability

*Renewable energy, energy systems, and sustainable development.*

- [PyPSA](https://github.com/PyPSA/PyPSA) - Python for Power System Analysis, simulating and optimizing modern energy systems.
- [oemof-solph](https://github.com/oemof/oemof-solph) - Open Energy Modelling Framework for energy-system optimization (LP/MILP).
- [pvlib-python](https://github.com/pvlib/pvlib-python) - Community toolbox for simulating photovoltaic system performance.
- [Calliope](https://github.com/calliope-project/calliope) - Multi-scale energy-system modeling framework.
- [EnergyPlus](https://github.com/NREL/EnergyPlus) - Whole-building energy simulation engine from the U.S. DOE and NREL.
- [atlite](https://github.com/PyPSA/atlite) - Converts weather data into power-system resource time series.
- [Brightway](https://github.com/brightway-lca/brightway2) - Python framework for life-cycle assessment (LCA).
- [openLCA](https://github.com/GreenDelta/olca-app) - Open-source software for life-cycle assessment and sustainability.

## Pollution and Environmental Health

*Air, water, and soil pollution, ecotoxicology, and environmental health.*

- [GEM](https://github.com/keithwlittle/GEM) - Generic Environmental Model for chemical fate and transport across soil, water, and air.
- [tcpl](https://github.com/USEPA/CompTox-ToxCast-tcpl) - EPA ToxCast pipeline for high-throughput chemical toxicity screening.
- [httk](https://github.com/USEPA/CompTox-ExpoCast-httk) - EPA high-throughput toxicokinetics models for exposure and risk assessment.
- [harmonize-wq](https://github.com/USEPA/harmonize-wq) - EPA tool for harmonizing heterogeneous water-quality data.
- [StreamCatTools](https://github.com/USEPA/StreamCatTools) - R package for the EPA StreamCat watershed-characterization data.
- [lakecat](https://github.com/USEPA/lakecat) - EPA LakeCat dataset and tools for lake water-quality characterization.

## Remote Sensing and GIS

*Earth observation, satellite data, SAR, LiDAR, and geospatial analysis.*

- [QGIS](https://github.com/qgis/QGIS) - Free and open-source desktop geographic information system for viewing, editing, and analyzing geospatial data.
- [Google Earth Engine](https://earthengine.google.com/) - Cloud platform for planetary-scale environmental and geospatial analysis over petabytes of satellite imagery.
- [GDAL](https://github.com/OSGeo/gdal) - Geospatial Data Abstraction Library for reading, writing, and transforming raster and vector geodata formats.
- [rasterio](https://github.com/rasterio/rasterio) - Python library for reading and writing geospatial raster data, built on GDAL.
- [geemap](https://github.com/gee-community/geemap) - Python package for interactive mapping and geospatial analysis with Google Earth Engine.
- [leafmap](https://github.com/opengeos/leafmap) - Python package for interactive geospatial analysis and visualization in Jupyter.
- [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) - Advanced open-source geospatial data analysis platform for remote sensing and GIS workflows.
- [Orfeo ToolBox](https://www.orfeo-toolbox.org/) - Library for remote sensing image processing, from pre-processing to classification and segmentation.
- [SNAP](https://github.com/senbox-org/snap-engine) - ESA's open-source toolbox for processing Sentinel and other satellite data.

## Environmental Data Science and AI

*The Python scientific ecosystem, Pangeo, machine learning, and scientific
computing for environmental applications.*

- [xarray](https://github.com/pydata/xarray) - Labeled N-dimensional arrays, the de facto standard for working with multi-dimensional Earth science data in Python.
- [Pangeo](https://pangeo.io/) - Community platform for big data geoscience built on xarray, Dask, and Jupyter.
- [Dask](https://github.com/dask/dask) - Parallel and out-of-core computing that scales NumPy and Pandas workflows to large environmental datasets.
- [MetPy](https://github.com/Unidata/MetPy) - Python library for meteorological data analysis and visualization.
- [cartopy](https://github.com/SciTools/cartopy) - Cartographic projections and geospatial data processing for Python.
- [Satpy](https://github.com/pytroll/satpy) - Python library for reading, resampling, and processing satellite imagery.
- [Iris](https://github.com/SciTools/iris) - Met Office library for analyzing and visualizing Earth system data.
- [pyproj](https://github.com/pyproj4/pyproj) - Python interface to the PROJ library for coordinate reference system transformations.
- [xclim](https://github.com/Ouranosinc/xclim) - Library of climate indices and bias-correction utilities built on xarray.
- [WeatherBench 2](https://github.com/google-research/weatherbench2) - Benchmark and leaderboard for data-driven, AI-based global weather forecasting models.

## Datasets

*Curated, well-documented environmental datasets with official public sources.*

- [ERA5](https://cds.climate.copernicus.eu) - ECMWF's fifth-generation global atmospheric reanalysis from 1940 to present, the standard for climate and weather research.
- [CMIP6](https://esgf-node.llnl.gov/projects/cmip6/) - Coupled Model Intercomparison Project Phase 6, coordinated global climate-model projections used in IPCC AR6.
- [Copernicus Sentinel](https://dataspace.copernicus.eu) - Free and open radar and optical satellite imagery from the European Copernicus programme.
- [Landsat](https://landsat.gsfc.nasa.gov/) - The longest-running satellite record of Earth's land surface, at 30 m resolution.
- [MODIS](https://modis.gsfc.nasa.gov/) - Moderate Resolution Imaging Spectroradiometer products for land, atmosphere, and ocean monitoring.
- [WorldClim](https://www.worldclim.org/) - Gridded climate and bioclimatic variables widely used for species distribution and ecological modeling.
- [GBIF](https://www.gbif.org/) - Global Biodiversity Information Facility, the largest aggregator of species occurrence records.
- [Global Carbon Budget](https://globalcarbonbudget.org/) - Annual assessment of global carbon sources and sinks from the Global Carbon Project.
- [NOAA GML](https://gml.noaa.gov/) - Long-term greenhouse gas and ozone measurements, including the Mauna Loa CO₂ record.
- [OpenAQ](https://openaq.org/) - Open, real-time air-quality measurements aggregated from sources worldwide.
- [Argo](https://argo.ucsd.edu/) - Global array of profiling floats measuring temperature and salinity in the upper ocean.
- [World Ocean Atlas](https://www.ncei.noaa.gov/products/world-ocean-atlas) - NOAA's gridded climatology of ocean temperature, salinity, and other variables.
- [NSIDC](https://nsidc.org/) - National Snow and Ice Data Center, the authoritative archive for cryospheric data.
- [GLIMS](https://www.glims.org/) - Global Land Ice Measurements from Space, a database of glacier outlines and change.
- [ISIMIP](https://www.isimip.org/) - Inter-Sectoral Impact Model Intercomparison Project, providing climate-impact projections.

## Papers and Journals

*Landmark papers, influential reviews, and leading journals.*

**Landmark papers**

- [A safe operating space for humanity](https://doi.org/10.1038/461472a) (Rockström et al., 2009, *Nature*) - Introduces the planetary boundaries framework defining a safe operating space for humanity.
- [Planetary boundaries: Guiding human development on a changing planet](https://doi.org/10.1126/science.1259855) (Steffen et al., 2015, *Science*) - Updated assessment of the planetary boundaries.
- [Tipping elements in the Earth's climate system](https://doi.org/10.1073/pnas.0705414105) (Lenton et al., 2008, *PNAS*) - Identifies critical tipping points in the climate system.
- [Deep learning and process understanding for data-driven Earth system science](https://doi.org/10.1038/s41586-019-0912-1) (Reichstein et al., 2019, *Nature*) - Landmark review on machine learning in the Earth sciences.
- [Global Carbon Budget 2023](https://doi.org/10.5194/essd-15-5301-2023) (Friedlingstein et al., 2023, *ESSD*) - The annual authoritative accounting of global carbon sources and sinks.
- [Climate Change 2021: The Physical Science Basis](https://www.ipcc.ch/report/ar6/wg1/) (IPCC AR6 WGI, 2021) - The IPCC's definitive assessment of the physical science of climate change.

**Journals**

- [Nature Climate Change](https://www.nature.com/nclimate/) - High-impact journal on climate and its social and ecological implications.
- [Nature Sustainability](https://www.nature.com/natsustain/) - Interdisciplinary journal on sustainability science.
- [One Earth](https://www.cell.com/one-earth/home) - Cell Press journal on global environmental change and sustainability.
- [Environmental Science & Technology](https://pubs.acs.org/journal/esthag) - Leading journal for environmental chemistry, pollution, and remediation.
- [Global Change Biology](https://onlinelibrary.wiley.com/journal/13652486) - Journal at the interface of biology and global change.
- [Water Resources Research](https://agupubs.onlinelibrary.wiley.com/journal/19447973) - AGU journal for hydrology and water resources.
- [Remote Sensing of Environment](https://www.sciencedirect.com/journal/remote-sensing-of-environment) - Leading journal for Earth observation science.
- [Journal of Climate](https://journals.ametsoc.org/view/journals/clim/clim-overview.xml) - AMS journal for climate dynamics and variability.

## Courses, Books, and Communities

*Courses, books, and communities for learning and connecting.*

**Courses**

- [Earth Data Science](https://www.earthdatascience.org/) - Free, open courses on Earth data science, GIS, and remote sensing from Earth Lab.
- [Project Pythia](https://projectpythia.org/) - Community educational portal for learning the Python geoscience stack.
- [Google Earth Engine Training](https://developers.google.com/earth-engine/training) - Official training resources for the Earth Engine platform.

**Books**

- [An Introduction to Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro.html) - Open textbook on Python for Earth and environmental data science.
- [Geocomputation with R](https://r.geocompx.org/) - Free, open book on geographic data analysis and modeling in R.
- [Practical Meteorology](https://www.eoas.ubc.ca/books/Practical_Meteorology/) - Open textbook on meteorology by Roland Stull.

**Communities**

- [ESIP](https://www.esipfed.org/) - Earth Science Information Partners, a community for Earth data and informatics.
- [Climate Change AI](https://www.climatechange.ai/) - Community of researchers and practitioners applying machine learning to climate action.
- [rOpenSci](https://ropensci.org/) - Community for open, reproducible science in R.
- [Openscapes](https://www.openscapes.org/) - Community championing open data science for environmental teams.

## Contributing

Contributions are welcome! Please read the
[contribution guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md)
first, then open a pull request. A few rules of thumb:

- One entry per line, in the format `[Project Name](URL) - one-line description.`
- Keep descriptions short, factual, and neutral.
- Add new entries to the most specific section, keeping items alphabetically
  sorted where sensible.
- Verify the link resolves and the project is still actively maintained.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers of this list have waived all
copyright and related or neighboring rights to this work. See
[LICENSE](LICENSE).
