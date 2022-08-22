# surfs_up
Creating a tool to provide weather analysis for a new venture.  We will be using Jupiter Notebooks, along with SQLite db


## Overview of Project

### Summary ### 
The objective of this project is to utilize SQLAlchemy to produce an analysis of the temperature and precipitation in Oahu, Hawaii for the period of 2010-2017.  There is a great deal of interest from a potential investor to open up a shop that is highly dependent on weather factors. The venture is for an ice cream shop along with surf gear, called "Surf n' Shake Shop."
This project provides analysis of the following data:
* June temperature data
* December temperature data
* Precipitation comparisons (additional information)

### Data Sources
The data sources to complete this project are outlined below:
* hawaii.sqlite (database)

The statistical analysis was performed using the following Python Library:
* sqlalchemy

### Software Used
* Python 3.7.13, 
* Pandas Library 1.3.5
* Matplotlib 3.5.1
* Jupyter Notebook:
  * IPython          : 7.31.1
  * ipykernel        : 6.9.1
  * ipywidgets       : 7.6.5
  * jupyter_client   : 6.1.12
  * jupyter_core     : 4.9.2
  * jupyter_server   : 1.13.5
  * jupyterlab       : 3.3.2
  * nbclient         : 0.5.13
  * nbconvert        : 6.4.4
  * nbformat         : 5.3.0
  * notebook         : 6.4.8
  * qtconsole        : 5.3.0
  * traitlets        : 5.1.1



## Results 

### June Temperature Statistics
The analysis provided the following statistics for the month of June:

| ![Figure 1](https://github.com/mrmarken/surfs_up/blob/main/Resources/june_temps.png) |
| :---: |
| **Figure 1.** June Temperatures |

### December Temperature Statistics
The analysis provided the following statistics for the month of December:

| ![Figure 2](https://github.com/mrmarken/surfs_up/blob/main/Resources/dec_temps.png) |
| :---: |
| **Figure 2.** December Temperatures |

 ### Analysis
Below are some key differences in weather between June and December: Oahu, Hawaii
1. The average recorded temperature in June is approximately 75 degrees F, which is ~4 degrees higher than the average temperature in December.
2. The temperature readings in December appear to have more variability than those in June.  When comparing the max vs min temp of each month, December has a much wider range (~27 deg. F).
3. There are 183 more temperature data points for June than December for the period examined.  One thing to note however is that the standard deviation for each is relatively close: June = 3.26 vs. December = 3.75.
 
### Summary
When looking at the temperature readings, one can surmise that opening the Surf n' Shake Shop has a high likelihood of succeeding. The temperature readings do not have a great deal of variability in the peak months of June and December.  These two months were analyzed to provide a high-level of confidence that throughout the year the temperature in Oahu is fairly consistent and the weather should not prove to be an obstacle in this endeavor. 
Additionally, further analysis was performed to view precipitation data for the two months.  The following image provides an overview:

| ![Figure 3](https://github.com/mrmarken/surfs_up/blob/main/Resources/jun_dec_prcp_temp.png) |
| :---: |
| **Figure 3.** June and December Temperatures and Precipitation|

Looking through the data, it can be further summarized that precipitation averages for each month of June (0.14 in.) and December (0.22 in.) should not affect a decision of opening up this shop.

