# Energy-generation-in-Spain-using-Multi-Step-Time-Series-with-Stacked-LSTM-Recurrent-Neural-Networks.

## Energy Consumption in Spain
Spain is the sixth-largest energy consumer in Europe, after Germany, France, United Kingdom, Italy, and Turkey and has virtually no domestic production of liquid fuels or natural gas. Government regulation limits the share of total oil and natural gas that can be imported from any single country to ensure diversity of supply. [2]

The most important measure in the energy balance of Spain is the total consumption of
239.50 billion kWh of electric energy per year. Per capita this is an average of 5,058 kWh. Spain could provide itself completely with self-produced energy. The total production of all electric energy producing facilities is 259 bn kWh, which is 108% of the countries own usage. Despite this, Spain is trading energy with foreign countries. Along with pure consumptions the production, imports and exports play an important role. Other energy sources such as natural gas or crude oil are also used.[1]

### Petroleum and other liquids
Spain has a negligible amount of oil reserves and produces very small amounts of crude oil and condensate. Because Spain lacks domestic petroleum resources, it imports virtually all of the oil needed to meet its demand, which in 2016 was nearly 1.3 million b/d. Spain typically imports crude oil from all regions except Asia. Most of their crude oil in 2016 came from Mexico, Nigeria, Saudi Arabia, Russia, Iraq, and Angola.
Liquid fuels accounted for about 46% of Spain's total primary energy consumption in 2016, although this share has declined since the 1990s.
The country has nine refineries with a total crude oil refining capacity of more than 1.4 million b/d, the third highest in Europe after Germany and Italy, according to Oil & Gas Journal. [2]

### Natural gas
Spain, Europe's seventh-largest consumer of natural gas, burned about 1 trillion cubic feet (Tcf) in 2016. Natural gas accounted for about 19% of Spain's total energy consumption in 2016, according to BP Statistical Review of World Energy 2017. Until the 2008 financial crisis, Spain was one of the fastest-growing natural gas markets in Europe. Spain saw an approximate 142% increase in natural gas consumption, mostly from the power sector, between 2000 and 2008. Since then, consumption declined for several years because of the global financial crisis and competition from other fuel sources. As the Spanish economy began to recover, the country's natural gas consumption increased by 6% between 2014 and 2016.
Spain produces almost no natural gas and has an insignificant amount in reserves, which forces the country to import virtually all of its natural gas to meet demand.
Spain imports natural gas from Algeria through two undersea pipelines—the Maghreb-Europe gas pipeline and the Medgaz pipeline. In 2016, pipeline imports from Algeria accounted for 42% of total natural gas imports. The Iberian Peninsula (Spain and Portugal) has only limited natural gas pipeline connections to the rest of Europe (via a pipeline through France).
In 2016, almost half (466 Bcf) of Spain's natural gas imports were liquefied natural gas (LNG). Spain's three largest suppliers of LNG were Algeria, Qatar, and Nigeria. In 2016, Algeria supplied about 52% of Spain's total natural gas imports (LNG and pipeline), according to BP Statistical Review of World Energy 2017.
Spain has seven LNG import terminals, including El Musel import terminal in Gijon, which is awaiting government authorization to begin operations. Currently, Spain has ample regasification capacity of roughly 2.4 trillion cubic feet per year (Tcf/y), the largest amount in Europe. Utilization rates of regasification terminals have dropped over the past few years as a result of capacity additions and LNG import declines. The terminals have a combined LNG storage capacity of 134 million cubic feet (MMcf). The proposed Tenerife and Gran Canaria LNG terminals in the Canary Islands are under review by Spanish regulatory agencies, and each is expected to bring 45 Bcf/y of regasification capacity online by 2021. Although both terminals have reached the final investment decision, the owner, Gascan, is still waiting on local regulatory approvals before construction can begin. [2]

### Coal
In 2016, the total coal consumption in Spain accounted for almost 8% of total primary energy consumption, down from more than a 10% share the year before. Spain produced about 1.9 million short tons of coal in 2016, which accounted for less than 1% of total primary energy consumption. Spanish coal production has fallen precipitously since the 1980s because of more competitively priced imported coal, stricter environmental standards, and competition from other fuels such as natural gas and renewable energy. Spain imported 15 million short tons of coal in 2016.
Spain supports the domestic coal industry with production subsidies and domestic purchase requirements for electricity generators. However, subsidies are scheduled to be phased out by 2018. In 2015, the country had about 40 active coal mines, compared with 167 in 1990. Spain plans to close another 26 mines by 2018. [2]

### Electricity
Since the 2008 global recession, the amount of gross electricity Spain generated has decreased overall by 11% to 262 billion kilowatthours (Bkwh) in 2016.
Spain generated a significant amount of power from renewable sources in 2016, with 39% of gross electricity generation, but nonrenewable sources (including fossil fuels and nuclear energy) still held the largest share of generation at 61%.
Based on data from Red Eléctrica de España, Spain's electric grid operator, 18% of Spain's gross electricity generation came from wind energy, 14% from hydropower, 5% from solar, and 2% from other renewable sources in 2016.
Supported by government subsidies, renewable generation has grown quickly from roughly 20% of total electricity production in 2007 to an annual high of 41% in 2014. However, in 2014, the government reformed its renewable energy subsidy program to cap renewable energy producers' rate of return as a result of the rising costs of the subsidies. A drop in renewable generation occurred in 2015, most likely because of these reforms and the low-price environment of coal and natural gas. In 2016, the share of renewable sources rebounded to 39% of electricity generation, as the Spanish renewable energy sector remained attractive to investors and as higher water supply increased hydropower. Europe's massive heat wave in the summer of 2017 has negatively affected Spanish hydroelectricity and wind power generation, and it increased natural gas-fired generation.
Spain has seven operating nuclear reactors, which supplied 22% of the country's electricity generation in 2016, according to Red Eléctrica de España.
Fossil fuels, primarily natural gas and coal, generated almost 40% of the country's electricity in 2016.


#### Sources:
1. https://www.worlddata.info/europe/spain/energy-consumption.php
2. https://www.eia.gov/international/analysis/country/ESP
3. Dataset: https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather
4. Model used: https://www.relataly.com/stock-market-prediction-using-multivariate-time-series-in-python/1815/


## ANALYSIS OF THE SNS PLOT
1. The dependent variable (Price_actual) is positively correlated to generation of biomass, brown coal lignite, fossil gas, fossil hard coal, fossil oil, some categories of renewable energy sources, solar day ahead, solar energy and recycled waste.
2. It has infinite slope with fossil coal derived gas, fossil oil shale, fossil peat, geothermal, marine and offshore wind.
3. It has near zero correlation with hydro pumped storage, run of the river and poundage, nuclear generation, solar generation,  onshore wind and total load.


## ANALYSIS OF THE TIME PLOT
1. Biomass generation, Fossil hard coal lignite, marine sources, generatio of wind offshore, generation fossil peat, hydro water reservoir, nuclear generation, waste, onshore winds, offshore winds, other renewable energy sources, total forecast load and  actual price all seem seasonal in nature, as the patterns seem to repeat.
