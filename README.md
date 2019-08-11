# Write A Data Science Blog Post 

## Table of Contents:

1. [Motivation](#motivation)
2. [File description](#file)
3. [How to interact with your project](#interact)
4. [Authors](#author)
5. [Acknowledgements](#ack)


## Motivation <a name="motivation"></a>
This project is part of Udacity Data Scientist Nanodegree.

In this project, I'll work with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign.

## File description <a name="file"></a>

I needed REMOVE the files via the agreement with Arvato Bartlesmann after completing the project, as the data are proprietary.

The files available for the project are:

- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).

- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).

- Data_Dictionary.md: Information file about the features in the provided datasets.
 
 - AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.

 - Identify_Customer_Segments.ipynb: Jupyter Notebook divided into sections and guidelines for completing the project. The notebook provides more details and tips than the outline given here.

## How to interact with your project <a name="interact"></a>

This project uses Python 3 and Jupyter Notebook. The following libraries are used in this project:

- NumPy
- Pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)
- Seaborn (for data visualization)

## Authors <a name="author"></a>
Ricardo Coelho

## Acknowledgements <a name="ack"></a>
Step 1: Preprocessing
When you start an analysis, you must first explore and understand the data that you are working with. Create a cleaning procedure. 
-  Missing or unknown values
- Consider the level of measurement for each feature in the dataset (e.g. categorical, ordinal, numeric).
- Drop or re-encoded values

Step 2: Feature Transformation
Dimensionality reduction techniques to identify relationships between variables in the dataset.
- Feature scaling.
- Principal component analysis (PCA) to find the vectors of maximal variability. 

Sklearn library to create objects that implement feature scaling and PCA dimensionality reduction decisions.

Step 3: Clustering
Apply clustering techniques to identify groups.
- Use the k-means method to cluster
-  Data cleaning, feature scaling, PCA, and k-means clustering. 