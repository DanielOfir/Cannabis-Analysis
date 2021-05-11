# Cannabis-Analysis

## Data Acquisition

To obtain the data, we use crawling on the website https://www.leafly.com/.
The data is loaded dynamically, therefore we use selenium to acquire the html files.

## Data Arrangement

Once the data was acquired, we coverted nested dictionaries to columns. 

## Data Cleaning
After reviewing the data, we found some of the data was faulty

* Missing data
* Data type was float instead of integer

To complete missing values for ['Feelings] - For each column of 'Feeling' we found the most frequent feeling for each strain that is a "sibling" or "parent".

To complete missing values for ['Cannbinoids'] - For each column of 'Cannbinoids' we got the mean value for each strain that is a "sibling" or "parent".

## Data Visualisation
