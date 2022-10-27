# AI_project: Clustering and classification of environnemental datas from divers countries.

The goal of this project is to use AI tools from python's sklearn and spicy packages to classify and cluster data.
The report is a jupyter notebook that combine codes, graphes and explanation of each technical choices. 

We chose environmental data from WorldBank database. We download them in "Environment_datas.txt".
We have a matrix of data from 266 countries (objects) regarding 142 parameters (attributes).
Each parameter (attribute) is defined in the "Environment_defintions.txt" file. 
Through those data we want to examine the correlation between the wealth of a country and its environmental scores. 

For that we go through different steps: 
1. Selection of attributes: remove missing values, correlations and less pertinent attributes. 
2. Selection of a subset of data to focus our analysis on specific points: PCA, standardization.
3. Selection of object (countries) of interest: remove missing values, identify ouliers, DBSCAN.
4. Clustering: look for clusters of globular shapes and of arbitrary shapes, using particular K-means, hierarchical clustering and DBSCAN.
5. Classification: decision tree classifier and cross validation.
