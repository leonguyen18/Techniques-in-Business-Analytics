# Assignment 2: Analysis of Koala Physical Characteristics

## Project Description
This project is Assignment 2 for the BUSA8000 Techniques in Business Analytics unit. The analysis focuses on understanding the physical characteristics of koalas and their relationships with various factors such as habitat and gender.

## Introduction
The effective conservation and management of koalas relies on understanding their physical traits. Our dataset contains morphological measurements from diverse koala populations, enabling analysis of their biological characteristics. This analysis investigates correlations between physical parameters, explores male-female differences, and assesses environmental influences on koala development. These insights will support evidence-based conservation practices.

## Tools and Libraries Used
- **Jupyter Notebook**
- **Python**
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `plotly`
  - `scipy`
  - `statsmodels`

## Project Tasks

### 1. Data Preparation and Exploration
#### Load Data and Initial Overview
- Load the dataset from `koalas_dataset.xlsx`
- Check the shape and structure of the data
- Identify data types and potential issues

#### Data Cleaning
- Handle inconsistent entries in categorical variables
- Address missing values using median imputation
- Check for and handle duplicate records
- Treat outliers in measurements

### 2. Exploratory Data Analysis
- Analyze distributions of numerical variables
- Examine categorical variable frequencies
- Create visualizations for key relationships
- Calculate and visualize correlations

### 3. Statistical Analysis
The analysis addressed six key questions:

1. Is the mean head length significantly different from 92.0 mm?
2. Do male and female koalas have significantly different mean head lengths?
3. Can we predict total length based on head length?
4. Can we predict total length based on multiple factors?
5. Do environmental factors affect koala's physical characteristics?
6. What factors correlate with koala total length?

## Key Findings

### Data Overview
- Dataset contains 104 records with 14 variables
- Variables include physical measurements and demographic information
- Two main habitats: Queensland (QLD) and Victoria (VIC)

### Physical Characteristics Analysis
- Head length shows strong correlation with total length (0.63)
- Significant differences found between QLD and VIC koalas in:
  - Foot length
  - Paw size
  - Chest circumference
  - Ear size

### Gender Differences
- No significant difference in mean head lengths between genders
- Females show greater variability in belly to chest circumference ratio
- Males and females have different body proportion patterns

### Predictive Models
- Simple linear regression model explains 40.3% of variance in total length
- Multiple regression model with selected features explains 71% of variance
- Key predictors: head length, skull width, foot length, and paw size

### Environmental Effects
- Habitat (QLD vs VIC) significantly affects certain physical characteristics
- Regional variations suggest possible adaptations to local environments

## Recommendations

1. Develop standardized health assessment tools based on correlated measurements
2. Implement habitat-specific conservation strategies
3. Consider gender differences in conservation planning
4. Establish connected wildlife reserves between QLD and VIC
5. Initiate long-term studies on climate change impacts

## Contributing
As this is an individual assignment, I am the main contributor. However, feedback and suggestions for improvement are welcome.

## License
This project is part of a university assignment and should be used for educational purposes only.
