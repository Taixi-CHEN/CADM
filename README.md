# CADM
## All the functions are introduced below:

Pre-need: A set of functions to analyze the attribute order table.

CADM: The whole CADM distance metric with K-modes algorithm

NMI, CA, ARI: Three functions for three indicators to evaluate the cluster 
 
## How to execute the experiment are introduced below:
1. Import the dataset and its labels in the example running cell.
2. Input the start location of the ordinal attributes of the target data set (e.g., od=2 for Hayes Royth data set, od=0 for ordinal data, od = attribute_number +1 for all nominal data). 
3. Execute the cell .
4. Experimental results will be displayed automatically.

Example running cells (including mixed, ordinal, and nominal data sets) have been demonstrated under a set of functions.    
Please note that this paper assumes that the former part of the attributes of a data set are nomial attributes and the latter part are ordinal attributes. 
When using data sets not provided here, it may be necessary to pre-process the data sets to ensure that the ordinal attributes are latter than nominal attributes, and delete all null rows.
