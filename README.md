# **r**<span style="color:#C0C0C0">**e**</span>newable <span style="color:#C0C0C0">**e**</span>nergy <span style="color:#C0C0C0">**e**</span>**valuation**
#### Kickstarting model with a set of unified scenarios for the [open decarbonization](https://www.opendecarbonization.org/) initiative.  

### About  
The project aims to develop a generic capacity expansion model which can be *(relatively)* easily applied to any territory (country/region) to evaluate intermittent renewable energy potential and electric power system design with a high to 100% share of renewables. The initial "kickstarting" model will not consider any existing generating capacity, evaluating the potential of renewables, based on 40-years of hourly meteorological data from NASA's [MERRA-2 project](https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/). As a result, the project will assemble, adopt, or develop:   

* Scripts to formulate multi-region capacity expansion model with 1-hour resolution (8760 sub-annual time-slices in total);  
* Scripts to process MERRA-2 data and acquire (up to 40-years) time series of wind- and solar- energy;  
* Scripts to run the model and scenarios;  
* Scripts for processing the modeling results, generic reporting, and sharing under the [open decarbonization](www.opendecarbonization.org) project. The modeling language of the project is *R* with *energyRt*. The model can be solved with one of the popular mathematical programming languages (see [www.energyRt.org](www.energyRt.org) for details).

### Targeted model structure  
* multiple regions (minimum two, recommended 30+, will be used as nodes for UHVDC grid);  
* one year of optimization with one-hour time resolution, full-year (8760 time-slices);  
* solar PV and wind turbines technologies;  
* (optional) fossil-fuels-fired generating technologies, hydro-, and nuclear-energy;  
* energy storage technologies;  
* several levels of the final demand (fixed or variable in time, exogenous or optimized location).    

As the starting point, the project will adopt a model initially developed under *Feasibility study of China’s electric power sector transition to zero emissions by 2050* (by Oleg Lugovoy, Shuo Gao, Ji Gao, Kejun Jiang, under review), and currently being applied to [USA](https://www.usensys.org/), [India](https://github.com/olugovoy/indem), and several other countries. 

### The pilot project timeline    
The *pilot* project is a short-term project, starting now in May 2020 and is expected to conclude at the end of Summer 2020, delivering the generic kick-start model, open models for the participating countries, and the set of unified scenarios. The project will include up to 7 countries/regions.  

### <span style="color:red">**Call for collaboration**</span>  
The project can provide support in developing the model for up to two 2 additional teams. Researchers/modelers who are interested in developing/applying the model for a particular country or region, please contact: opendecarbonization@gmail.com, olugovoy@edf.org. 
