# World Happiness Report 2026 - Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the World Happiness Report 2026 dataset.

The analysis explores life evaluation scores across countries and years, identifies trends, examines statistical relationships, and investigates factors associated with life evaluation.

## Objectives

- Understand the structure and quality of the dataset
- Perform data cleaning and preprocessing
- Calculate descriptive statistics
- Analyze the distribution of life evaluation scores
- Identify yearly trends
- Compare countries based on life evaluation
- Analyze correlations between life evaluation and explanatory factors
- Create meaningful visualizations
- Extract key insights from the data

## Dataset

The dataset used in this project is:

**World Happiness Report 2026 - Figure 2.1**

The dataset contains:

- **2,116 records**
- **13 columns**
- **168 unique countries**
- Data covering **2011–2025**

### Main Variables

- Year
- Rank
- Country name
- Life evaluation (3-year average)
- Log GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Dystopia + residual

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Inspection

The dataset was examined for:

- Shape and dimensions
- Column names
- Data types
- Missing values
- Duplicate records
- Number of unique countries
- Year-wise data availability

### 2. Descriptive Statistics

Statistical measures such as:

- Mean
- Median
- Minimum
- Maximum
- Standard deviation

were calculated to understand the dataset.

### 3. Trend Analysis

The average life evaluation score was analyzed across the available years from 2011 to 2025.

The average score increased from approximately **5.39 in 2011** to **5.65 in 2025**, although the trend was not completely consistent every year.

### 4. Country Comparison

The analysis identified the countries with the highest and lowest life evaluation scores in 2025.

Finland had the highest life evaluation score in the 2025 data, with a score of **7.764**.

### 5. Correlation Analysis

Correlation analysis was performed using data from **2019–2025**, because explanatory variables were largely unavailable for earlier years.

The strongest correlations with life evaluation were:

| Factor | Correlation |
|---|---:|
| Social support | 0.701 |
| Log GDP per capita | 0.681 |
| Healthy life expectancy | 0.659 |
| Freedom to make life choices | 0.491 |
| Perceptions of corruption | 0.426 |
| Dystopia + residual | 0.378 |
| Generosity | 0.035 |

These values represent statistical associations and do not establish causation.

## Key Findings

- Average life evaluation shows an overall upward pattern from 2011 to 2025.
- Social support had the strongest correlation with life evaluation among the explanatory factors analyzed.
- Log GDP per capita and healthy life expectancy also showed relatively strong positive correlations.
- Freedom to make life choices showed a moderate positive correlation.
- Generosity showed very little linear correlation with life evaluation.
- Missing explanatory variables were concentrated in the earlier years, so they were not artificially imputed.

## Visualizations

The project includes visualizations for:

- Life evaluation distribution
- Average life evaluation by year
- Top 10 countries in 2025
- Bottom 10 countries in 2025
- Correlation matrix
- Factor correlation comparison
- Major factors over time
- Factor vs. life evaluation scatter plots
- Highest vs. lowest country comparison

## Project Structure

```text
World-Happiness-EDA/
│
├── EDA.ipynb
├── README.md
└── WHR26_Data_Figure_2.1.xlsx