# STATEMENT OF RESEARCH
Elliot Cohen, Ph.D. | <elliot.cohen@columbia.edu> | [github](https://github.com/Ecohen4) | [Earth Institute](http://www.earth.columbia.edu/articles/view/58) | [SEL](http://sel.columbia.edu/about/) | [QMSS](http://qmss.columbia.edu/faculty-and-staff/)   
***

## Research Philosophy
The best descriptor for my area of expertise is Sustainable Energy Systems. It is truly interdisciplinary -- part environmental engineering, part mechanical engineering, part sustainability science, part data analysis and part statistics. My work calls upon:

* **High impact** project-lead experience at the Sustainable Engineering Lab (Columbia, Current)
* **Reproducible and scalable** research design for the United Nations (Columbia, Current)
* **High-level audiences** with strong funding potential (UN, World Bank, DoE, NREL, ECREEE) 
* **Fluency with quantitative methods** in environmental engineering (Ph.D. 2014, Colorado Denver)
* **Extensive fieldwork** (Fulbright Scholar to India, 2013)
* **Interdisciplinary training** in sustainable urban infrastructure (M.S. 2011, Colorado Denver)
* **Solid foundation** in mechanical engineering (B.S. 2009, University of Maryland)

In terms of impact, my research extends beyond peer-reviewed journals and onto the desks of policy-makers. Notably, I have contributed research and analysis to:

* World Bank [Cities and Climate Change: Responding to an Urgent Agenda](https://openknowledge.worldbank.org/handle/10986/2312)
* National Renewable Energy Laboratory [Life Cycle Assessment Harmonization Project](http://onlinelibrary.wiley.com/store/10.1111/j.1530-9290.2012.00474.x/asset/j.1530-9290.2012.00474.x.pdf?v=1&t=i4g0ctd7&s=3f642884c2f19f5fe640f41220f1296f2c777366)
* IPCC [Special Report on Renewable Energy Sources and Climate Change Mitigation](http://srren.ipcc-wg3.de/report/IPCC_SRREN_Ch03.pdf)
* Presidential Climate Action Project [Addressing Climate Change Under Executive Authority](http://www.climateactionproject.com/docs/PCAP_Report_2012.pdf)

## Current ResearchContinuing in the tradition of policy-relevant and impactful externally-funded research, I am currently working with the United Nations Industrial Development Organization (UNIDO) to train energy professionals in West Africa in [data analytics and grid-integration of renewable energy](http://ecohen4.github.io/ECREEE/).More broadly, I am lead author or project-lead in six active research areas:

* [Spatial Analysis of Energy Access, Consumption and Reliability in Emerging Megacities](http://sel.columbia.edu/delhi-energy-project/)   
with Sou Min Sonia Lee (Columbia)* [Global Trends in Urban Energy Use](http://ecohen4.github.io/Energy/Global_Trends_v4.html)  
with Vijay Modi, Henri Torbey, Michael Piccirelli and Yu-Tian (Columbia)* [Temporal Downscaling of Global Energy Demand Forecasts](https://github.com/Ecohen4/Energy)  
with Vijay Modi, Henri Torbey and Yu-Tian (Columbia)* [The Water Footprint of Urban Energy Systems](http://onlinelibrary.wiley.com/doi/10.1111/jiec.12086/abstract)  
with Anu Ramaswami (Minnesota)* [The Effect of Climate on Grid-Scale Electricity Supply Reliability (see Ch. 6)](http://gradworks.umi.com/36/21/3621820.html)  
with Anu Ramaswami and Balaji Rajagopalan (Minnesota; Colorado)
* [Weather Data Pipeline for R](http://ecohen4.github.io/Cohen-McCreight/weatheR.html)  
with Michael Piccirilli and James McCreight (Columbia, NCAR)

The following sections describe five of my current projects. Links are provided (above) for further details.

### Spatial Analysis of Energy Access, Consumption & Reliability in Emerging Megacities
In 2006, the United Nations Development Programme, the UN Millennium Project, and the World Bank issued a joint statement:

> The world has an unprecedented opportunity to improve the lives of billions of people
> by meeting the Millennium Development Goals (MDGs), the international community’s time-bound 
> and quantified targets for addressing extreme poverty in its many forms. [...]
> A common finding of the ten Task Forces of the UN Millennium Project has been the urgent need
> to improve access to energy services as essential inputs for meeting each MDG. 
> Without increased investment in the energy sector, the MDGs will not be achieved in the poorest countries (Modi et al. 2006).

Today, significant progress has been made in improving energy access globally. Yet disparities persist. Two areas of persistent disparity are the urban-rural divide and the intra-urban divide. The urban-rural divide is well known -- with multiple studies citing that urban residents have, on average, higher per-capita energy use than their rural counterparts (Pachauri 2004, Pauchauri and Spreng 2004, Chavez et al. 2012). But averages do not tell the full story. Pachauri (2004) reveals large within-group variation in per capita energy requirements for urban and rural households using micro-survey data. He demonstrates similar levels of total direct energy use for the bottom 40 percentile of urban and rural households, but finds that similarities dissipate at higher expenditure levels. The top 10 percentile of urban households consume on average 38% more end-use energy than the top 10 percentile of rural households. This suggests larger within-group variation and higher skew in the distribution of energy services in urban compared to rural areas. Which brings us to what I call intra-urban disparities in energy access. 

This work builds on Pachauri's findings by drilling deeper for one city using high resolution observational data (as opposed to survey data). We expect to find much larger disparities between high-income and low-income urban neighborhoods than previously documented in the literature.

We hypothesize that intra-urban disparities will be highly significant in developing-world mega-cities, which bear the weight of massive--and growing--populations. Public infrastructure and essential city services are often lacking to begin with, and are further overwhelmed by the influx of rural-to-urban migration.


### Global Trends in Urban Energy Use
Many of the world's largest and fastest growing cities--from Karachi to Delhi, Dhaka, Jakarta, Bangkok, Lagos and Kinshasa--are located in South Asia and Sub-Saharan Africa with tropical to sub-tropical climates unlike those of most OECD-member cities in the global North. As the tropics/sub-tropics become increasingly urban, industrial and affluent, it is important to consider how energy demand--particularly for thermal comfort--will evolve differently than it has historically across the OECD. 

To illustrate the potential for vast differences in energy demand for thermal comfort between cities in the global North and cities in the Tropics/Sub-Tropics, consider Delhi, India. Delhi with its massive population and very hot climate is an outlier compared to most OECD cities but typical of South Asia: Peak summer temperatures routinely exceed 40 deg C. (104 F.), and intense heatwaves can approach 50 deg C. (122 F.). Given the huge temperature differential between outdoor (say 104 F.) and desired indoor air temperature (say 72 F), and the thermodynamic fact that energy for cooling scales linearly with the temperature differential, cooling a building in Delhi requires twice as much energy as cooling a building in New York where the summer indoor-outdoor temperature differential is typically half that. 

In addition to higher temperatures, the summer season is also much longer: in the past year, Delhi had over six times as many cooling-degree days as New York City (again assuming a desired indoor air temperature of 72 deg F). Compounded by leaky building envelopes in developing world cities (designed for natural ventilation, not air conditioning), intense heat-island effects (typically less green space), and massive population growth, peak electricity demand in cities throughout the developing world could one day surpass that of their neighbors to the north--not just in aggregate terms because of their size, but also *per-capita* due to climate, building design and thermodynamics. 

This will have huge implications for capacity expansion, technology deployment, grid planning, demand-side management, pricing mechanisms, and overall system reliability. More broadly, it will influence the global transition to renewable energy given the limitations of meeting such large and 'peaky' demand with non-dispatchable resources such as wind and solar.

To address this issue, I am compiling a global database of high-resolution electricity demand data for a large number of cities in the tropics/sub-tropics. Using this database (which will be the first of its kind), I am analyzing demand elasticity, climate effects, cooling/heating thresholds, and how all of these evolve over time along the development spectrum.


### Temporal Downscaling of Long-Range Energy Forecasts
Global energy forecasts such as the annual IEA World Energy Outlook inform energy planning at the highest levels of government and industry. These reports directly influence investment decisions today that will lock-in carbon emissions and environmental impacts for decades to come. However, such mid- to long-range demand forecasts are typically reported as annual totals and provide little insight to the temporal distribution throughout the year. This leaves a huge gap in investment decisions, particularly in the power sector where demand is non-uniform, growth is non-linear, and cost is driven by capital expenditures, which in turn are driven by peak demand, not integral energy consumption. 

Peak electrical demand for a given grid-region may represent just a few days of the year, meaning that capital utilization is low and return on investment is long. Thus accurate long-range peak demand forecasts are essential for proper investment decisions today. This is particularly true for renewable energy, where utilization rates are already low due to non-dispatchability. 

To address this shortcoming, I am leading a study of diurnal and seasonal patterns of energy demand for a large number of global cities. This requires more and better data than is typically available to researchers, which I have cultivated through a diverse network of electricity grid operators across the developing world. Data continues to pour in, strengthening our analyses. This will be a key area of my research in 2016 and beyond.


### Water-Energy-Climate Nexus
For my PhD, I co-developed with my advisor (Anu Ramaswami, Chair Professor of Science, Technology and Public-Policy at the University of Minnesota) an infrastructure-based water footprint for city energy systems. The footprint serves to identify and quantify key flows of real and embodied water in urban energy systems. Our methodology addresses the fact that provision of energy services to a city are made possible by the use of water elsewhere (often outside jurisdictional and hydrological boundaries of the city and watershed, respectively). 

Traditionally defined water footprints (e.g Gerbens-Leenes et al 2008, Hoekstra and Chapagain 2007a/b, Hoekstra and Hung 2002/2005) allocate consumptive water use due to evapotranspiration and pollution assimilation to final economic consumption of agricultural and commercial goods. This consumption-based perspective informs consumers of the impact of their consumption patterns, but does not address production constraints. For example, insufficient streamflow (supply) could inhibit water withdrawals (demand) in the production of goods in the first place.

Acknowledging the importance of a production-based perspective, Blackhurst et al. (2009) demonstrated that for 93% of U.S. industrial sectors, supply chain water withdrawals exceed direct withdrawals. Building on their insights, and to address the challenge of downscaling (e.g. for city- or regional-scale analysis where national-average water withdrawal factors often do no hold true due to infrastructural and/or climatic differences), we proposed an infrastructure-based supply chain water footprint specifically designed for estimating the water withdrawal needs of city energy systems. 

Coupled water-energy footprints make it possible to translate water resource constraints at multiple spatial and temporal scales to measurable impacts on urban populations. 

For example, the July 2012 cascading power failure in Northern India that left 600 million people without electricity for two days was a prime example of how cities, their populations and economies are at risk to multiple and multi-scale water-energy-climate interactions. In this case, reports suggest that hot, dry conditions characteristic of the pre-monsoon season persisted further into summer than usual and remained unabated due to late arrival of the annual monsoon. This induced electricity demand for groundwater pumping and air conditioning (adaptive responses to hot, dry conditions) exacerbated by reductions in hydropower capacity (also linked to the delayed monsoon), resulting in grid imbalance, and ultimately, the largest blackout in human history (Mukherji et al. 2012, Yardley and Harris 2012). At present, seldom few city governments, policy actors or infrastructure designer/operators consider these types of trans-boundary resource constraints to critical urban infrastructure. Filling that gap is a key goal of this research.

### Weather Data Pipeline for R
Long observational records of high-resolution weather data are instrumental to a wide range of research and development applications. Such data are essential to energy demand forecasts (Segal et al. 1992; Sailor 2001; Crowley et al. 2003; Thatcher 2007), building energy models (Deru et al. 2011), renewable energy feasibility studies and site assessments (Lambert et al. 2005), crop insurance programs (Helmath et al. 2009), emergency preparedness and early warning systems (Rogers and Tsirkunov 2011), and much more. However, many scientists, engineers and practitioners that rely on such data hail from diverse fields of study uninitiated to the particularities of meteorological archives. Indeed there is a steep learning curve to finding, accessing, subsetting, filtering and cleaning the available troves of data.

Globally, national weather services and climate information centers such as the U.S. National Oceanic and Atmospheric Administration (NOAA), Britain's Met Office, and India's Institute for Tropical Meteorology (IITM), collect, curate, analyze and publish meteorological data from thousands of weather stations. NOAA's National Climatic Data Center (NCDC) is the world's largest such archive. 

To make meteorological data more accessible to a wide range of scientists, engineers and practitioners, we created the `weatheR` library built for the statistical computing language R. It is intended to facilitate geo-referenced and quality-control batch query of NOAA's National Climatic Data Center (NCDC)--the world's largest active archive of weather data. Our work builds on _Downloading and processing NOAA hourly weather station data_ by Delameter et al (2013). The `weatheR` library introduces new functionality and automation previously unavailable:

* Identification and selection of nearest-neighbor weather stations for virtually any place on Earth. Locations of interest are geo-referenced via the Google Maps API.
* Batch query with a simple character string of location names (e.g. "New York City", "Tiennamen Square", "Abuja, Nigeria")
* Built-in quality controls for "best" data selection based on the geographic proximity and completeness of the observational record.
* On-demand interpolation for missing data.
* Quick visual inspection to make sure you're getting what you expect.

The `weatheR` library is free, open-source and available now on [Github](https://github.com/mpiccirilli/weatheR). To start using it, all you need are the following three lines of R code:
	
	require(devtools)
	install_github("mpiccirilli/weatheR")
	require(weatheR)
