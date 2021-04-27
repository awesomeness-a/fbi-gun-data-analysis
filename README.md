
# FBI Gun Data Analysis 
This repository contains a project in which we analyze data from the FBI's National Instant Criminal Background Check System.
The NICS is used by to determine whether a prospective buyer is eligible to buy firearms 
or explosives. 
Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. 
The data has been supplemented with state level data from [census.gov](https://www.google.com/url?q=https://www.census.gov/&sa=D&ust=1532469042127000).

The [NICS](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a4db8_gun-data/gun-data.xlsx&sa=D&ust=1532469042127000) data is found in a `nics_data.csv file`. 
It contains the number of firearm checks by month, state, and type.

The [U.S. census data](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a554c_u.s.-census-data/u.s.-census-data.csv&sa=D&ust=1532469042128000) is found in a `us_census.csv file`. 
It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.

## `gun_data_analysis.ipynb` 
This `Jupyter Notebook` file contains Python code of our data analysis process, step-by-step. The Python libraries used in the process are:
* Pandas
* NumPy
* Matplotlib
* Seaborn

During the data analysis process, we will try to answer the following questions:
* What is the estimated number of gun registration per capita by states (2010 vs 2016)?
* Which states had the highest number of gun registrations (2010 vs 2016)?
* Which states have had the highest growth in gun registrations over the period of 2010 to 2016?
