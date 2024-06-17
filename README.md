# Dengue Cases Analysis and Clustering

## Introduction
This project analyzes and visualizes dengue case data in the Philippines from 2016 to 2020. By applying K-Means clustering techniques, the project aims to identify patterns and trends in dengue cases and deaths across different regions. Understanding these patterns is crucial for preventing the spread of dengue and addressing the healthcare needs of the community effectively.

## Project Structure
- `final.ipynb`: The main Jupyter notebook containing all steps of the analysis, including data loading, preprocessing, exploratory data analysis (EDA), clustering, and evaluation.
- `data/ph_dengue_cases2016-2020.csv`: The dataset used for the analysis (ensure to include this file if sharing the dataset is permissible).

## Steps and Analysis
1. **Data Loading and Initial Inspection:**
   - Load the dataset and inspect its structure and contents.

2. **Data Formatting and Cleaning:**
   - Check for null values and data types of each column.
   - Convert the 'Month' column to a categorical datatype and encode the 'Region' column.

3. **Descriptive Statistics:**
   - Generate summary statistics to understand the dataset's distribution.

4. **Trend Visualization:**
   - Visualize trends in dengue cases and deaths over the years to identify patterns and anomalies.

5. **Clustering Analysis:**
   - Apply K-Means clustering to group regions based on dengue cases and deaths.
   - Use the Elbow Method to determine the optimal number of clusters.

6. **Cluster Visualization:**
   - Visualize the clusters to identify regional patterns.

7. **Model Evaluation:**
   - Evaluate the performance of the clustering using the Calinski-Harabasz Index.

## Results
The analysis revealed distinct groupings of regions based on dengue cases and deaths. Regions with the highest cases and deaths were identified, indicating the need for extensive public health measures in these areas. The clustering results provide valuable insights for designing targeted interventions to combat dengue.

![Main Interface].(images/regional_clusterin.png)

## Conclusion
This project demonstrates the application of data analysis and clustering techniques to understand the distribution and impact of dengue cases in the Philippines. The insights derived from the analysis can help public health officials allocate resources more effectively and design targeted interventions to reduce the incidence of dengue.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/dengue-cases-analysis.git
