Energy Data Sources
===================

This repository contains URL links & descriptions to a collection of energy-related data sources for Ireland.  

All data listed here is either: 
- [open access](https://en.wikipedia.org/wiki/Open_access) (the default)   
- `Available upon request`
  - i.e. is accessible via an application process with the relevant body
- `Available upon purchase`

__Have a new data source to add or found a broken data source URL?__ Great! Please email us at `energy-modelling-ireland-admin@googlegroups.com` with:

```
Name of source:  Irish Social Science Data Archive (ISSDA)

Short description:  "The Irish Social Science Data Archive (ISSDA) is Ireland’s leading centre for quantitative data acquisition, preservation, and dissemination. Based at UCD Library, its mission is to ensure wide access to quantitative datasets in the social sciences, and to advance the promotion of international comparative studies of the Irish economy and Irish society."

URL link to source:  https://www.ucd.ie/issda/data/

The Raw Data file (if there is currently no URL to the data source)
```

> See the [Data Wishlist](#data-wishlist) for a list of data sources that we would love but do not yet have!

__Want to contribute through Github instead?__ Please follow the [`how-to-contribute`](#how-to-contribute) guide below.  All changes will be reviewed prior to being published on this website so don't worry about breaking anything with your edits :smiley: 


---
---


Table of Contents
=================

<!--ts-->
* [Table of Contents](#table-of-contents)
* [Data Catalogues](#data-catalogues)
* [Energy Consumption](#energy-consumption)
* [Building Fabric](#building-fabric)
* [Appliance Usage](#appliance-usage)
* [Geodata](#geodata)
* [Benchmarks](#benchmarks)
* [Emissions](#emissions)
* [Waste and Landfill](#waste-and-landfill)
* [Weather](#weather)
* [Data Wishlist](#data-wishlist)
* [How to Contribute?](#how-to-contribute)
<!--te-->

---
---


Data Catalogues
===============

Irish Social Science Data Archive (ISSDA)
-----------------------------------------
- "The Irish Social Science Data Archive (ISSDA) is Ireland’s leading centre for quantitative data acquisition, preservation, and dissemination. Based at UCD Library, its mission is to ensure wide access to quantitative datasets in the social sciences, and to advance the promotion of international comparative studies of the Irish economy and Irish society."
- https://www.ucd.ie/issda/data/

UK Energy Research Centre (UKERC) Data Catalogue   
------------------------------------------------
- Compilation of energy related publications for the United Kingdom
- https://ukerc.rl.ac.uk/DC/cgi-bin/edc_search.pl?GoButton=Related&WantComp=40


---
---


Energy Consumption
==================

Commission for Regulation of Utilities (CRU) Smart Meter Trials
---------------------------------------------------------------
- `Available upon request`
- Electricity meter data at 15-minute resolution for a sample of 5,000 Irish homes and businesses between 2009-10
- Gas meter data at 15-minute resolution for a representative sample of nearly 2,000 Irish homes between 2010-11
- https://www.ucd.ie/issda/data/commissionforenergyregulationcer/

Carbon Trust Advanced Metering Trial (2004-2006)
------------------------------------------------
- `Available upon request`
- Half hourly gas and electricity (and water) consumption data (not all utilities were monitored at every site) gathered during the Carbon Trusts Advanced Metering for SMEs project (2004-2006) in United Kingdom Regions of England, Wales and Scotland.  
- Meter readings are available for small and medium-sized enterprises (SMEs).  The sectors covered are:
  - Community, social and personal activities
  - Education
  - Financial and business services
  - Government
  - Health and social work
  - Manufacturing
  - Other sectors
  - Wholesale and retail trade
- https://ukerc.rl.ac.uk/DC/cgi-bin/edc_search.pl/?WantComp=30

Gas Network's Ireland Networked Gas Consumption
-----------------------------------------------
- Annual Gas consumption data for all Irish Power Plants, Residential & Non-Residential
- https://www.cso.ie/en/statistics/climateandenergy/networkedgasconsumption/

Environmental Protection Agency (EPA) Annual Energy Use
-------------------------------------------------------
- Annual Gas & Electricity data for Emissions Trading System (ETS) industrial buildings.  
- As part of their licencing and permits companies have to submit an annual environmental report
- http://epa.ie/licensing/
- Rebecca Cachia (Codema - Dublin's Energy Agency) extracted all energy data for 47 industrial buildings in Dublin (November, 2019).
- https://zenodo.org/record/4048377

Mortar
------
- "The goal of Mortar is to provide a large, diverse and consistently updated testbed of buildings and building data to facilitate reproducible evaluation of building analytics.  At this time, Mortar contains 107 buildings, spanning over 10 billion data points and 26,000 data streams."
- https://mortardata.org/

Energy Performance of Buildings Data: England and Wales
-------------------------------------------------------
- The domestic and non-domestic Energy Performance of Buildings Registers (the registers) are the official place for all Energy Performance Certificates (EPCs), Display Energy Certificates (DECs) and Air Conditioning Inspection Reports (ACIRs).
- https://epc.opendatacommunities.org/

SEAI Measurement & Reporting Data (M&R)
---------------------------------------
- `Available upon request`
- Energy Demands for M&R Public Sector buildings.
- More information: https://www.seai.ie/business-and-public-sector/public-sector/monitoring-and-reporting/
- SEAI contact page: https://www.seai.ie/contact-us/


---
---


Building Fabric
===============

SEAI's 2016 Census Small Area Statistics
----------------------------------------
- Building data (period built, dwelling type, boiler type ...) for all households in Ireland who participated in the 2016 Census at Small Area level (i.e. areas of population generally comprising between 80 and 120 dwellings). 
- https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/
- Click `Small Areas (18,641) -` to download a `csv` file containing the Small Area Statistics.
- Click `SAPS 2016 Glossary (XLS 38KB)` to download an `xlsx` file containing the column name decodings (for example: from `T6_1_HB_H` decodes to `House/Bungalow (No. of households)`).
  - See [drem](https://github.com/codema-dev/drem) for more information on cleaning this data set for Dublin using Python.

SEAI's BER Public Search
------------------------
- Building data (type of heating, building geometry ...) for all households in Ireland who have had their household's BER rating evaluated.
- Updated nightly
- https://ndber.seai.ie/BERResearchTool/Register/Register.aspx

Valuation Office API
--------------------
- Building data (floor areas ...) for all Commercial buildings in Ireland
- __Note:__ Apply benchmarks to these floor areas to estimate commercial building energy usage
- https://opendata.valoff.ie/api/

Air Tightness Ireland Field Data houses 1944-2008 (2012)
--------------------------------------------------------
- Air-tightness field data for dwellings in Ireland.
  - "Air permeability test results of 28 houses built between 1944 and 2008 and at varying stages of retrofit."
- https://doi.org/10.1016/j.buildenv.2011.11.016

Air Tightness UK Field Data houses post-2006 (2010)
---------------------------------------------------
- Air-tightness field data for dwellings in the UK.
  - "This paper reports on the air permeability test results of 287 post-2006 new-build dwellings in the UK."
- https://doi.org/10.1016/j.buildenv.2010.04.011


---
---


Appliance Usage
===============

United Kingdom Time Use Survey, 2014-2015
-----------------------------------------
- "The United Kingdom Time Use Survey, 2014-2015 (UKTUS) is a large-scale household survey that provides data on how people aged 8 years and over in the UK spend their time. At the heart of the survey is a time diary instrument in which respondents record their daily activities. Time diaries record events sequences for prescribed periods, usually a single day."
- https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=8128

Commission for Regulation of Utilities (CRU) Smart Meter Trials
---------------------------------------------------------------
- `Available upon request`
- __Survey of participants links typical appliance usage to building IDs__ 
- https://www.ucd.ie/issda/data/commissionforenergyregulationcer/


---
---


Geodata
=======

SEAI's 2016 Census Small Area Geometries 
----------------------------------------
- Mappable (in QGIS) geometries for all Small Areas.
- https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/
- Click `Small Areas UG`

Shane McGuinness' (of Trinity College) Dublin Postcodes Geometries
------------------------------------------------------------------
- Mappable (in QGIS) shapefile geometries for all Dublin Postcodes.
- https://github.com/rdmolony/dublin-postcode-shapefiles) 

UCD Library of Spatial Datasets
------------------------------------------------------------------
- Collection of data organized by folder for all of Ireland.
- https://libguides.ucd.ie/gisguide/FindSpatialData

---
---


Benchmarks
==========

Chartered Institute of Building Services Engineers (CIBSE) TM46: Energy Benchmarks (2008)
-----------------------------------------------------------------------------------------
- `Available on purchase`
  - €55
- Commercial sector building fossil fuel and electricity benchmarks by building type from a CIBSE Study 'Energy & CO2 emissions benchmarks for non-domestic buildings' from 2007.
- __Note:__ CIBSE has updated these benchmarks in Guide F (2012)
  - "This platform [energy benchmarking tool] aims to gradually update and replace the energy benchmarks in table 20.1 of CIBSE Guide F: Energy Efficiency in Buildings."
- URL: https://www.cibse.org/Knowledge/knowledge-items/detail?id=a0q20000008I7evAAC
- Benchmarking tool: https://cibse.org/knowledge/energy-benchmarking-tool-beta-version

Chartered Institute of Building Services Engineers (CIBSE) Guide F: Energy Efficiency in Buildings (2012)
---------------------------------------------------------------------------------------------------------
- `Available on purchase`
  - €114
- Commercial sector building fossil fuel and electricity benchmarks by building type used by the CIBSE Energy Benchmarking Tool
- __Note:__ CIBSE is phasing out these benchmarks in favour of DEC-based benchmarks (see UK DEC above) 
  - "Revised benchmarks have been introduced for some building types (see below) which are based on the Display Energy Certificates (these covered more than 120k DECs – for details, see full report) analysed by UCL under a jointly sponsored project."
- URL: https://www.cibse.org/Knowledge/knowledge-items/detail?id=a0q20000008I7oTAAS
- Benchmarking tool: https://cibse.org/knowledge/energy-benchmarking-tool-beta-version


---
---


Emissions
=========

SEAI Conversion Factors
-----------------------
- Calorific values, Emission factors, Fuel densities, Primary energy conversion factors
- URL: https://www.seai.ie/data-and-insights/seai-statistics/conversion-factors/
- Derivation Methodology: https://www.seai.ie/publications/DEAP-Elec-Factors-2017.pdf

Environmental Protection Agency (EPA) Licensing and Permitting
------------------------------------------------------------
- Industrial Emissions
- As part of their licencing and permits Emissions Trading System (ETS) industrial buildings have to submit an annual environmental report.
- URL: http://epa.ie/licensing/


---
---


Waste and Landfill
==================

Environmental Protection Agency (EPA) Licensing and Permitting
------------------------------------------------------------
- Industrial Waste & Landfill
- As part of their licencing and permits Emissions Trading System (ETS) industrial buildings have to submit an annual environmental report.
- URL: http://epa.ie/licensing/


---
---


Weather
=======

Met Eireann Historical Data
---------------------------
- Historical Irish weather data
- URL: https://www.met.ie/climate/available-data/historical-data

ASHRAE International Weather for Energy Calculations v2 (IWEC2)
---------------------------------------------------------------
- `Available on purchase`
  - €94 for all-Ireland
  - €34 for an individual station
- The files are derived from Integrated Surface Hourly (ISH) weather data originally archived at the National Climatic Data Center. For these selected locations, the ISH database contains weather observations on average at least four times per day of wind speed and direction, sky cover, visibility, ceiling height, dry-bulb temperature, dew-point temperature, atmospheric pressure, liquid precipitation, and present weather for at least 12 years of records up to 25 years.
- URL: http://ashrae.whiteboxtechnologies.com/IWEC2

EnergyPLUS Weather Data
-----------------------
- Weather data for more than 2100 locations are now available in EnergyPlus weather format — 1042 locations in the USA, 71 locations in Canada, and more than 1000 locations in 100 other countries throughout the world.
- URL: https://energyplus.net/weather


---
---


Guides
======

CIBSE Guide A
-------------
- `Available on purchase`
  - €98
- A UK technical reference source for designers and installers of heating, ventilating and air conditionings services.
- URL: https://www.cibse.org/knowledge/knowledge-items/detail?id=a0q20000008I79JAAS
- Blog: https://www.cibsejournal.com/general/guide-a-cibses-essential-guide-to-environmental-design-explained/


---
---


Data Wishlist
=============
- Metered Electricity Consumption Data at as fine a spatial and temporal granularity as possible!
- Netork Gas Consumption data at a Small Area level (see [Energy Consumption](#energy-consumption) for a Postcode-level demand data source)


---
---


How to contribute?
==================

Here’s a quick guide to editing GitHub Markdown files on GitHub, if you’re new to this:

- Scroll up to the top of this page and Click on the `README.md` file

![Click README file](images/click-readme-file.PNG)

- You should now be able to see a pencil icon in the top-right corner of the page.  Click it!

![Click README pencil](images/click-readme-pencil.PNG)

- Scroll down and make changes ([here’s a lovely Markdown tutorial](https://commonmark.org/help/tutorial/) if you need it) in the following format:

```
Title of Data Source
--------------------
- `Available upon request` if have to contact the data owner for access
- Description of Data Source ...
- http://www.link-to-data.ie/thedata/

```

![Make changes](images/proposed-changes-to-readme.PNG)

- Scroll down to `Propose Changes`, summarise the changes & add a quick explanation on why the change should be made.

![Propose changes](images/propose-changes.PNG)

- Click `Create pull request`. Thank you! 🎉

![Create pull request](images/create-pull-request.PNG)

> Adapted from [`list-of-python-api-wrappers`](https://github.com/discdiver/list-of-python-api-wrappers/blob/master/readme.md) and this excellent [Medium.com article](https://towardsdatascience.com/how-to-get-data-from-apis-with-python-dfb83fdc5b5b)

