# Cannabis-Analysis

## Subject 

Cannabis strains exist for a long time.
The goal is to develop a Machine Learning model that can predict whether a strain is of Hybrid, Indica or Sativa type.

## Data Acquisition

Crawling is used to get the data.
* Leafly - https://www.leafly.com/
* Strain Of Weed - https://www.strainofweed.com/

## Data Arrangement

Once the data was acquired, we coverted nested dictionaries to columns. 

## Data Cleaning
After reviewing the data, it was found some of the data was faulty

* Missing data
* Data type was wrong (float instead of integer)

To complete missing values for ['Feelings','Flavors'] - For each column of 'Feeling'/'Flavor' - found the most frequent feeling for each strain that is a "sibling" or "parent".

To complete missing values for ['Cannbinoids'] - For each column of 'Cannbinoids' - got the mean value for each strain that is a "sibling" or "parent".

## Data Visualisation

Visualisation technics such as scatter plot, bar plot and pie plot were used

## Machine Learning

* Predict strain type 
* Predict strain type without data of "Hybrid" strains

