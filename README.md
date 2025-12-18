# Dots Glasses Customer Analysis

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This project performs comprehensive customer segmentation and data-driven analysis for Dots Glasses eyewear company. Using demographic, lifestyle, and behavioral data from a survey of potential customers across multiple countries (Canada, India, Japan, South Korea), we identify target market segments and provide actionable insights for product positioning and marketing strategies.

## Dataset

**Source:** Dots Glasses Potential Customer Survey Data (3,220 respondents)

**Countries Covered:**
- Canada (881 respondents)
- India (989 respondents)
- Japan (363 respondents)
- South Korea (987 respondents)

**Key Features (29 columns):**
- **Demographics:** Age, Gender, Country, Education Status, Family Income
- **Lifestyle:** Time spent on various activities (TV, sports, screen time, sleep)
- **Health:** Diabetes status, OTT subscriptions, Gym membership
- **Social:** Number of friends, Marital status, Migration status
- **Behavioral:** Preferences (spicy food, desserts), Career change interest, Alcohol consumption, Smoking
- **Product Affinity:** Wears Specs (target variable)

## Project Objectives

1. **Exploratory Data Analysis (EDA)** - Understand data structure, distributions, and relationships
2. **Data Cleaning** - Handle missing values and outliers
3. **Descriptive Statistics** - Generate insights on demographic and behavioral patterns
4. **Customer Segmentation** - Identify distinct customer groups using clustering
5. **Visualization** - Create compelling visualizations for stakeholder communication

## Analysis Highlights

### Data Quality
- **Total Records:** 3,220
- **Missing Values:** None detected
- **Data Types:** Mix of numerical and categorical features

### Key Findings
- **Specs Wearer Rate:** 54.8% of respondents wear glasses
- **Age Distribution:** 13-91 years (Mean: 44.8 years)
- **Income Range:** \$10 - \$59,858 (Mean: \$20,579)
- **TV Watching:** Average 4.3 hours/day
- **Sleep:** Average 7.6 hours/day

## Technologies & Libraries

```python
Python 3.8+
pandas          # Data manipulation and analysis
numpy           # Numerical computing
scikit-learn    # Machine learning and clustering
matplotlib      # Data visualization
seaborn         # Statistical data visualization
jupyter         # Interactive notebook environment
```

## Project Structure

```
dots-glasses-customer-analysis/
├── README.md                                    # Project documentation
├── requirements.txt                             # Python dependencies
├── Untitled1.ipynb                              # Main analysis notebook
├── data/
│   └── Dots Glasses Potential Customer Survey Data.xlsx  # Raw data
└── outputs/
    ├── histograms.png
    ├── barcharts.png
    ├── heatmap.png
    ├── boxplots_income_gender.png
    ├── boxplots_iq_spicy.png
    └── scatter_income_age.png
```

## How to Run

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/Karthik214005/dots-glasses-customer-analysis.git
cd dots-glasses-customer-analysis

# Install dependencies
pip install -r requirements.txt
```

### Running the Analysis

```bash
# Launch Jupyter Notebook
jupyter notebook Untitled1.ipynb
```

Then execute cells in order to:
1. Load and explore the dataset
2. Perform data quality checks
3. Generate summary statistics
4. Create visualizations
5. Analyze customer segments

## Key Insights by Country

### Canada
- Largest average family income ($20,423)
- Highest education completion rate
- Growing market for premium eyewear

### India
- Largest respondent pool
- Younger demographic (avg age < 50)
- High price sensitivity

### Japan
- Smallest segment (363 respondents)
- High tech adoption
- Premium product preference

### South Korea
- Tech-savvy population
- High OTT subscription rate
- Strong digital marketing potential

## Analysis Sections

### 1. Data Loading & Exploration
- Load Excel file into Pandas DataFrame
- Display basic information (shape, dtypes, first 5 rows)
- Generate descriptive statistics

### 2. Data Validation
- Check for missing values
- Identify outliers using IQR method
- Validate data types and ranges

### 3. Univariate Analysis
- Histograms for numerical features
- Bar charts for categorical features
- Distribution analysis

### 4. Bivariate Analysis
- Box plots (Income by Gender, IQ by Food Preference)
- Scatter plots (Income vs Age)
- Correlation matrix heatmap

### 5. Customer Segmentation
- Identify segments based on demographics and behavior
- Profile each segment
- Recommend targeting strategies

## Visualizations

The project generates several publication-ready visualizations:
- Distribution histograms for key numerical variables
- Category bar charts showing frequency distributions
- Heatmap of feature correlations
- Box plots revealing relationships between variables
- Scatter plots with color coding by demographics

## Future Enhancements

- [ ] Implement clustering algorithms (K-means, Hierarchical Clustering)
- [ ] Develop predictive models for specs-wearing propensity
- [ ] Create interactive dashboards with Plotly/Dash
- [ ] Perform A/B testing framework for marketing campaigns
- [ ] Add statistical significance testing
- [ ] Develop customer lifetime value predictions

## Key Metrics

| Metric | Value |
|--------|-------|
| Total Customers | 3,220 |
| Specs Wearers | 1,765 (54.8%) |
| Non-Wearers | 1,455 (45.2%) |
| Countries | 4 |
| Features | 29 |
| Missing Values | 0 |

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

**Author:** Karthik  
**GitHub:** [Karthik214005](https://github.com/Karthik214005)  
**Email:** Contact via GitHub

## Acknowledgments

- Dots Glasses for the survey data
- Python data science community for excellent libraries
- Contributors and reviewers

---

**Last Updated:** December 2025  
**Status:** Active Development
