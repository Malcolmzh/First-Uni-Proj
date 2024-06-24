# Airlines Flight data 
_A project done to fulfil a university course._<br />
The aim is to discover trends in delays and properties that may reduce the delays when travelling to the states!

## Data
This airline data reivew is obtain from (https://www.bts.gov/](https://doi.org/10.7910/DVN/HG7NV7).
This contains all the essential data related to airline punctuality for the North America.

## Cleaned Data
The dataset was cleaned using Python in Jupyter notebook and R in R studios. Both Py and R results are similiar as per project requirements.
* Renamed datasets for increased readability.

## Exploratory Data Analysis
* Exploring the relationship between delays against the age of the plane, day of the week, and cascading delays.
    * Using a 100% stacked bar, there is a positive but weak correlation between the age of the plane and delays.
    * Using a bar chart, saturday has the lowest amount of delays while thursday and friday has the greatest amount of delays.
    * A scatter plot with a regression lines indicates a positive but weak correlation between departure delays and arrival delays.
 
## Machine Learning
* Using gradient boosting and supprt vector machines to predict cascading delays.
