# CADM: Cluster-customized Adaptive Distance Metric for Categorical Data Clustering
You can find our paper in [Arxiv](https://arxiv.org/abs/2511.05826).

---

## All the functions are introduced below:

Preparation: A set of functions to analyze the attribute order table.

CADM: CADM distance metric with K-modes algorithm for categorical data clustering.

CADM-m: CADM distance metric with K-modes algorithm for mixed data clustering.

---
 
## How to execute the experiment are introduced below:
1. Import the dataset and its labels in the example running cell.
2. Input the end location of numerical attribute of the mixed data set (e.g., intloc=6 for HF data set).
3. Input the start location of the ordinal attributes of the target data set (e.g., od=2 for HR data set, od=0 for ordinal data, od = attribute_number +1 for all nominal data).
4. Execute the cell .
5. Experimental results will be displayed automatically.

Example running cells (including mixed, ordinal, and nominal data sets) have been demonstrated under a set of functions.    
Please note that this paper assumes that the former part of the attributes of a data set are numerical attributes and the latter part are ordinal attributes and nominal attributes. 
When using data sets not provided here, it may be necessary to pre-process the data sets to ensure that the ordinal attributes are latter than nominal attributes, and delete all null rows.

---
For convenience, we have provided the running cell and results of our used datasets in the notebook. You can change the algorithm only for comparisons.
