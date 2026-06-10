# Time-Series Analysis of Global Temperature Data

A comprehensive data analysis project that combines time-series temperature analysis with machine learning clustering techniques.

## Project Overview

This project is part of the **IDEAS (Institute of Data Engineering, Analytics and Science Foundation) Summer Internship Program 2026**. It demonstrates key data science skills including:

- **Time-Series Analysis**: Processing and analyzing global temperature data spanning multiple decades
- **Data Preprocessing**: Cleaning, transforming, and aggregating large datasets
- **Statistical Analysis**: Computing moving averages, yearly trends, and seasonal patterns
- **Machine Learning**: Applying K-Means clustering to the MNIST dataset with evaluation metrics

### Created by
**Samyabrata Roy** - Associate Software Developer

## Dataset

### Temperature Data (`monthly_csv.csv`)
- **Source**: Global temperature measurements from multiple sources
- **Content**: Monthly temperature readings with mean values
- **Sources**: GCAG and GISTEMP datasets
- **Time Period**: Multi-decade historical data
- **Variables**: Date, Mean temperature, Source identifier

The dataset contains global climate data used to analyze temperature trends over time and identify seasonal patterns.

## Project Objectives

The notebook addresses 13 questions across two main domains:

### Part 1: Temperature Time-Series Analysis (Questions 1-10)
1. **Data Loading**: Import libraries and load the global temperature dataset
2. **Data Preprocessing**: Convert dates to datetime objects and sort chronologically
3. **Data Inspection**: Analyze dataset shape and identify missing values
4. **Feature Engineering**: Extract year and month components from dates
5. **Moving Averages**: Calculate 12-month rolling averages per data source
6. **Time Filtering**: Filter data for the last 20 years of records
7. **Source Comparison**: Compute average temperatures by data source
8. **Yearly Aggregation**: Calculate yearly average temperatures
9. **Seasonal Analysis**: Identify the hottest month on average across all years
10. **Pivot Table Creation**: Build multi-dimensional summaries of monthly temperatures by year

### Part 2: Machine Learning & Clustering (Questions 11-13)
11. **MNIST Loading**: Load the handwritten digit dataset from scikit-learn
12. **K-Means Clustering**: Cluster 10 digit categories using unsupervised learning
13. **Evaluation Metrics**: Evaluate clustering quality using F1-score with label mapping

## Repository Structure

```
.
├── README.md                    # This file
├── 07-Time-Series_Analysis_of_Global_Temperature_Data_Summer_2026.ipynb
│                                # Main Jupyter notebook with all analyses
└── monthly_csv.csv              # Global temperature dataset
```

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd project
```

2. Install dependencies:
```bash
pip install pandas numpy scikit-learn jupyter
```

3. Launch the notebook:
```bash
jupyter notebook 07-Time-Series_Analysis_of_Global_Temperature_Data_Summer_2026.ipynb
```

## Notebook Structure

The Jupyter notebook is organized into 13 sequential questions:

| Question | Topic | Marks | Key Concepts |
|----------|-------|-------|--------------|
| 1 | Import & Load Data | 2 | Data loading, library imports |
| 2 | DateTime Conversion & Sorting | 1 | Temporal data handling |
| 3 | Data Inspection | 2 | Shape analysis, null detection |
| 4 | Feature Engineering | 1 | Date decomposition |
| 5 | Moving Averages | 2 | Time-series smoothing, groupby |
| 6 | Time Window Filtering | 2 | Data subsetting, temporal filtering |
| 7 | Group Aggregation | 2 | Groupby operations, statistics |
| 8 | Yearly Aggregation | 1 | Time-based grouping |
| 9 | Seasonal Analysis | 2 | Monthly patterns identification |
| 10 | Pivot Tables | 2 | Multi-dimensional data reshaping |
| 11 | MNIST Data Loading | 3 | Feature-target separation |
| 12 | K-Means Clustering | 5 | Unsupervised learning |
| 13 | Clustering Evaluation | 5 | F1-score, label mapping |

**Total: 30 Marks**

## Key Analyses

### Temperature Trends
- Historical temperature patterns from multiple global sources
- Year-over-year temperature comparisons
- Seasonal temperature variations
- 12-month moving average trends for smoothing

### Data Processing Techniques
- Datetime handling and sorting
- Missing value detection
- Feature extraction from date columns
- Data aggregation using groupby and pivot tables

### Machine Learning
- Unsupervised clustering of handwritten digits
- Handling arbitrary cluster label assignments
- F1-score calculation with macro-averaging
- Label mapping from clusters to true classes

## Expected Outputs

Each question includes expected outputs such as:
- DataFrames showing processed data
- Statistical summaries (shapes, null counts, means)
- Pivot tables with temperature data
- Cluster labels and evaluation metrics

## Technologies Used

- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Notebook Environment**: Jupyter
- **Programming Language**: Python 3

## Notes

- The temperature data includes two sources: GCAG and GISTEMP
- The project focuses on the last 20 years for detailed trend analysis
- K-Means clustering is performed with 10 clusters (matching the 10 digit categories in MNIST)
- F1 scores are calculated using macro-averaging for balanced performance assessment

## Contributing

This is an educational project for the IDEAS Summer Internship Program 2026. For questions or suggestions, please reach out to the project creator.

## Learning Outcomes

Upon completing this project, you will have:
- ✅ Proficiency in pandas time-series operations
- ✅ Understanding of data preprocessing and cleaning techniques
- ✅ Experience with statistical analysis and aggregation
- ✅ Knowledge of unsupervised machine learning (K-Means)
- ✅ Ability to evaluate machine learning models with appropriate metrics

## License

This project is created as part of the IDEAS Summer Internship Program 2026.

---

**Last Updated**: Summer 2026  
**Notebook Version**: 1.0
