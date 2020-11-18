Here we include the data used in the paper "The socio-economic determinants of the coronavirus disease (COVID-19) pandemic". 
The paper is available at https://arxiv.org/abs/2004.07947
The BMA model can be estimated in R using the package BMS (https://cran.r-project.org/web/packages/BMS/BMS.pdf)

The replication data is consisted of:

*** coronavirus_data.xlsx -- a file which contains data for the coronavirus induced variables for each country included in the sample. The variables are:

Country	- ISO3 Code for the country
Cases - accumulated number of cases per million population up to EndDate
Deaths - accumulated number of deaths per million population up to EndDate	GovResponse - magnitude of the government response index
Days - the number of days since FirstCase up to EndDate
Days_between - the number of days since the first registered coronavirus case in the world up to FirstCase
FirsCase - the date of the first registered coronavirus case in the country
EndDate - the last date at which the daily Government Response Index was at its maximum value

*** socio_economic_data.xlsx -- a file which contains data for the socio-economic variables for each country. The gathering procedure is described in the Supplementary Information

Country - ISO3 Code for the country
Death rate  - Death rate, crude  per capita (in logs)
Life expectancy - Life expectancy at birth, (years) (in logs)
Young population - Population ages 0-14 (\% of total) (in logs)
Elderly population - Population age 65+ (\% of total) (in logs)
Population size - Population, total (in logs)
Econ. development - GDP per capita, PPP \$ (in logs)
Population density - People per squared km (in logs)
Rural population - Rural population (\% of total) (in logs)
Income inequality - Income GINI index (in logs)
Int. tourism - Number of tourist arrivals (in logs)
Education - Human capital index (in logs)
Labor market - Employment to population ratio (\%) (in logs)
Health coverage - UHC service coverage index (in logs)
Migration - Int. migrant stock (\% of population) (in logs)
Air pollution - Yearly avg P.M. 2.5 (in logs)
Air transport - Yearly passengers carried (in logs)
Sus. development - Ecological Footprint (gha/person) (in logs)
Trade - Trade (\% of GDP), 10 year average (in logs)
Gov. spending - Gov. health spending p.c., PPP, 10 year average (in logs)
Household size - Avg. no. of persons in a household (in logs)
Overweight - Overweight prevalence (\% of adults) (in logs)
Catholic religion - Dummy variable indicating 60\%+ catholic population in the country
Christian religion - Dummy variable indicating 60\%+ christian population in the country
Muslim religion - Dummy variable indicating 60\%+ muslim population in the country
Gender -  Male population (\% of total) (in logs)
Governance - Governance index
Digitalization - Digitalization index
Medical resources - Medical resources index
Immunization - Immunization index
Mortality - Non-natural causes mortality index
Soc. connectedness - Social connectedness index (PageRank) (in logs)
