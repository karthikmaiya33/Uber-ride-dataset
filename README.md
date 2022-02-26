# Data-Analysis-Uber ride dataset

Uber is a platform where those who drive and deliver can connect with riders, eaters, and restaurants. In cities where Uber is available, you can use the Uber app to request a ride. When a nearby driver accepts your request, the app displays an estimated time of arrival for the driver heading to your pickup location. We are considering the dataset involving the details of Uber ride details having location details and number of ride details.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Uber ride dataset taken from the Kaggle website [Click here](https://www.kaggle.com/).

-------------------------------
## Project Walk-through

### Data Collection

Uber ride dataset taken from the Kaggle website consisted of 4 attributes and 56K tuples, the attributes are:
'Date'
'Lat'
'Lon'
'Base'

------------------------------


## Data Cleaning

After collecting the data, checked for the null and duplicate values present in the dataset to provide better accuracy of the result by removing it. Changes I made and what all variables & scripts I wrote:

    * Changed Date/time to the Datetime format using pandas function.
    * Parsed time and date from Date/time column. 
    * Parsed hour, weekday, and Date of the month column
 from Date/time column. 
   
-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various numerical and categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.


![image](https://user-images.githubusercontent.com/98012611/155850494-42dbc998-4bd6-417f-8db1-53a88c9404d3.png)

![image](https://user-images.githubusercontent.com/98012611/155850504-a04fea3c-1ee4-430b-9119-9d0d9aef6118.png)

-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, Seaborn, and Wordckoud.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)
* Datetime Documentation: [Click here](https://www.programiz.com/python-programming/datetime/current-time)

-----------------------------
