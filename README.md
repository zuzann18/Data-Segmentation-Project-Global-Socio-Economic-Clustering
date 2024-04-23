
# Data Segmentation Project: 
## Global Socio-Economic Clustering

## Project Overview
This project undertakes a comprehensive socio-economic segmentation analysis to identify global development patterns. We analyze key indicators: child mortality, income, and GDP per capita. Our analysis employs data cleaning, exploratory analysis, Box-Cox transformation for normalization, and KMeans clustering to segment countries into developmental categories, offering insights into socio-economic disparities.

## Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning tools for KMeans clustering
- **Seaborn & Matplotlib**: Data visualization
- **NumPy & SciPy**: Numerical computing and scientific computing

## Methodology
- **Data Cleaning**: Standardized the dataset for analysis,
- **Normalization**: Used Box-Cox transformation to normalize distributions
- **Exploratory Data Analysis (EDA)**: Identified patterns and relationships
- **Clustering**: Applied KMeans with the elbow criterion method to identify the optimal number of clusters.
- **Visualization**: Generated scatter plots and heatmaps to visualize the findings.

## Key Findings
The analysis delineated countries into under-developed, developing, and developed clusters, highlighting stark contrasts in development levels. Our predictive model emphasized the impact of economic indicators on development, revealing:
- A strong correlation between GDP per capita and child mortality rates.
- Distinct patterns of socio-economic development across clusters.

## Scaling the data
Uniform Scaling:
After addressing skewness and making the data distribution more normal with the Box-Cox transformation, StandardScaler ensures that all features contribute equally to the analysis by bringing them onto the same scale. This is done by subtracting the mean and dividing by the standard deviation of each feature, resulting in features centered around zero with a standard deviation of one.
This step is crucial because KMeans clustering relies on Euclidean distance to form clusters. Without scaling, features with larger scales dominate the distance metric, potentially leading to biased clusters.
Scaling works by first subtracting the column average from each individual entry. This step ensures the column average is adjusted to zero. Then we divide the result by each column's standard deviation. This step makes the column's standard deviation equal to 1. We transform the unskewed dataset to the same scale, meaning all columns have a mean of zero, and standard deviation of 1. The Box-Cox transformation and StandardScaler are employed to prepare the dataset for KMeans clustering.

## Heatmap

![image](https://github.com/zuzann18/Data-Segmentation-Project-Global-Socio-Economic-Clustering/assets/62249691/b108c79d-bb82-47a4-8179-c26dc446d458)
Above we can see a heatmap with correlations between variables. The most important insights from it are as follows: child_mort is having high negative correlation with life_expec
health, exports, income,imports are highly correlated with gdpp. 
## Cluster visualization
On the charts below we can observe the differences between 'gdpp', 'child_mort' and 'income' in presented clusters of countries. Analisys of those clusters can allow us to distinguish clusters of developed countries from the clusters of under-developed countries.
![image](https://github.com/zuzann18/Data-Segmentation-Project-Global-Socio-Economic-Clustering/assets/62249691/439dbd80-b221-42bd-863a-ab7db7b7eb0d)

## How to Run the Project
1. Clone the repository to your local machine.
2. Ensure you have Python and all required libraries installed.
3. Run the Python script (`analysis.py`) to perform the analysis.


### Requirements
- Python 3.8+
- Pandas
- Scikit-learn
- Seaborn
- NumPy
- SciPy

## Dataset
The analysis is based on data available on Kaggle: [Unsupervised Learning on Country Data] (https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)

## License
This project is made available under the MIT License.


