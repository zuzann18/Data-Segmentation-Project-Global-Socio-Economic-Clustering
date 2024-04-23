
# Data Segmentation Project: 
## Global Socio-Economic Clustering

## Project Overview
This project undertakes a comprehensive socio-economic segmentation analysis to identify global development patterns. Utilizing Python and several data science libraries, we analyze key indicators: child mortality, income, and GDP per capita. Our analysis employs data cleaning, exploratory analysis, Box-Cox transformation for normalization, and KMeans clustering to segment countries into developmental categories, offering insights into socio-economic disparities.

## Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning tools for KMeans clustering
- **Seaborn & Matplotlib**: Data visualization
- **NumPy & SciPy**: Numerical computing and scientific computing

## Methodology
- **Data Cleaning**: Standardized the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Identified patterns and relationships.
- **Normalization**: Used Box-Cox transformation to normalize distributions.
- **Clustering**: Applied KMeans with the elbow criterion method to identify the optimal number of clusters.
- **Visualization**: Generated scatter plots and heatmaps to visualize the findings.

## Key Findings
The analysis delineated countries into under-developed, developing, and developed clusters, highlighting stark contrasts in development levels. Our predictive model emphasized the impact of economic indicators on development, revealing:
- A strong correlation between GDP per capita and child mortality rates.
- Distinct patterns of socio-economic development across clusters.

## Visualizations
Include screenshots or links to visualizations here. For example:
- Scatter plots showing GDP per capita vs. child mortality.
- Heatmaps of correlation between different socio-economic indicators.

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


