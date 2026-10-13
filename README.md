# Exploratory Data Analysis (EDA) on World Happiness Data

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the World Happiness dataset to understand the factors associated with happiness and life evaluation across different countries and years.

The analysis explores relationships between life evaluation and factors such as GDP per capita, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption. Data analysis and visualization are used to identify trends, patterns, and correlations within the dataset.

## Objectives

- Understand the structure and characteristics of the dataset.
- Explore changes in life evaluation over time.
- Identify countries with the highest life evaluation scores.
- Analyze relationships between happiness and its contributing factors.
- Examine correlations between numerical variables.
- Create meaningful visualizations to communicate findings.

## Dataset

**Dataset Name:** World Happiness Report Data

**File Name:** `WHR26_Data_Figure_2.1.xlsx`

The dataset contains information about countries, their rankings, life evaluation scores, and factors associated with happiness.

### Key Features

| Feature | Description |
|---|---|
| Year | Year of the observation |
| Rank | Country's happiness ranking |
| Country name | Name of the country |
| Life evaluation (3-year average) | Average life evaluation score over three years |
| Lower whisker | Lower bound of the uncertainty interval |
| Upper whisker | Upper bound of the uncertainty interval |
| Explained by: Log GDP per capita | Contribution associated with economic conditions |
| Explained by: Social support | Contribution associated with social support |
| Explained by: Healthy life expectancy | Contribution associated with life expectancy |
| Explained by: Freedom | Contribution associated with freedom |
| Explained by: Generosity | Contribution associated with generosity |
| Explained by: Perceptions of corruption | Contribution associated with perceived corruption |
| Dystopia + residual | Remaining contribution to the reported score |

## Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis and documentation

## Project Workflow

1. **Data Loading:** Imported the World Happiness dataset into a Pandas DataFrame.
2. **Data Inspection:** Examined the dataset's dimensions, column names, data types, and statistical summaries.
3. **Data Cleaning:** Checked for missing values and assessed data quality.
4. **Exploratory Data Analysis:** Investigated distributions, country rankings, yearly trends, and relationships between variables.
5. **Correlation Analysis:** Examined correlations between life evaluation and its associated factors.
6. **Data Visualization:** Created charts to communicate patterns and relationships.
7. **Insights and Conclusions:** Summarized the key findings from the analysis.

## Key Findings

The analysis produced the following observations:

- **Life evaluation over time:** The average life evaluation score was approximately 5.39 in 2011 and 5.65 in 2025.
- **Highest-scoring countries:** Finland recorded a life evaluation score of approximately 7.76, followed by Iceland at 7.54 and Denmark at 7.54 in the analyzed data.
- **Social support:** Social support showed a strong positive correlation with life evaluation, with a correlation coefficient of approximately 0.70.
- **Economic conditions:** Log GDP per capita showed a positive correlation with life evaluation, with a correlation coefficient of approximately 0.68.
- **Healthy life expectancy:** This factor also showed a positive correlation with life evaluation, with a coefficient of approximately 0.66.
- **Country rankings:** Happiness rank was strongly negatively correlated with life evaluation, with a correlation coefficient of approximately -0.98.

These findings indicate associations between life evaluation and several social and economic factors. Correlation does not necessarily imply causation.

## Repository Structure

```text
EDA_Project/
│
├── EDA.ipynb
├── README.md
└── WHR26_Data_Figure_2.1.xlsx
