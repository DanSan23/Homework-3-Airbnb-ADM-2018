# Homework-3-Airbnb-ADM-2018
--------------------

Repository for the third homework of the course ADM 2018 at the Sapienza University.
Repository authors: Joanna Broniarek, Alice Shirina, Daniele Sanna.

## Data Source
* Airbnb_Texas_Rentals.csv
```https://www.kaggle.com/PromptCloudHQ/airbnb-property-data-from-texas```

## Jupyter Notebooks Descriptions
1. **Homework_3_Main.ipyn** - This jupyter notebook contains the implementation of Search_Engine_1,  Search_Engine_2 and definition of new scoring functions. Some of the used functions are located in the function.py file. 

  For correct working or Search Engines there is necessary to run Creating_Files.ipyn notebook. 
  Search Engine 1 is using "vocabulary.txt", "inv_indx.txt" files.
  Search Engine 2 is using "vocabulary.txt", "inv_indx_tfidf.txt" files.

2. **Creating_Files.ipyn** - In this notebook we create and save the following files "vocabulary.txt", "inv_indx.txt", "inv_indx_tfidf.txt" according to the data. 

3. **GeoMap.ipyn**  - There is an implementation of the Geomap for searching documents according to their locations. Example of the map i in the file **Visualisation.html**

## Script Descriptions
 1. functions.py - external file with definitions of functions used in the Homework_3_Main notebook.
