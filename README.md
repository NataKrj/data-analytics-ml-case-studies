# data-analytics-ml-case-studies
Applied data analytics and machine learning case studies using Python, covering exploratory analysis, clustering, regression and classification.

# Data Analytics & Machine Learning Case Studies

A collection of applied data analytics and machine learning projects developed in Python.

The case studies demonstrate an end-to-end analytical workflow, including data exploration, statistical analysis, clustering, predictive modelling, model evaluation and interpretation.

The repository focuses on practical analytical methods that can be transferred to business, risk and decision-support problems.

## Projects

### 1. Vehicle Fuel Efficiency Analysis

Exploratory analysis of vehicle characteristics and their relationship with fuel efficiency and performance.

The analysis examines how engine size, horsepower, vehicle weight and acceleration are associated with fuel consumption.

**Methods used:**
- Data preparation
- Descriptive statistics
- Exploratory Data Analysis (EDA)
- Histograms and box plots
- Correlation analysis
- Scatter plots
- Cross-tabulation
- Data visualization

**Selected findings:**
- Vehicle weight and fuel efficiency show a strong negative relationship.
- Engine displacement is negatively associated with MPG.
- Horsepower and engine displacement show a strong positive relationship.

---

### 2. California Housing Market Segmentation

Unsupervised learning analysis designed to identify meaningful segments within housing data based on property, demographic and economic characteristics.

Several clustering approaches are compared to understand how different preprocessing and modelling choices affect the resulting segments.

**Methods used:**
- Data standardization
- Hierarchical clustering
- Single, complete, average and Ward linkage
- K-Means clustering
- Cluster profiling
- ANOVA
- Elbow method
- Silhouette analysis

**Analytical objective:**

To determine whether housing observations can be grouped into meaningful segments and identify the characteristics that distinguish these groups.

---

### 3. House Price Prediction & Feature Analysis

Predictive modelling of residential property prices using housing characteristics such as living area, number of bathrooms, property grade, condition, renovation information and other features.

The project combines statistical modelling with model diagnostics and feature interpretation.

**Methods used:**
- Exploratory Data Analysis
- Correlation analysis
- Linear regression
- Variable significance analysis
- Stepwise feature selection
- Residual analysis
- Outlier detection and treatment
- Polynomial regression
- Prediction intervals
- XGBoost
- SHAP feature interpretation

**Selected result:**

Removing influential outliers improved the regression model from approximately **R² = 0.654 to R² = 0.688**, demonstrating the effect of data quality and extreme observations on predictive performance.

Important predictors included living area, property grade, bathrooms, waterfront location and other property characteristics.

---

### 4. Housing Segment Classification

Classification modelling based on data-driven housing segments.

The project explores whether previously identified housing groups can be predicted using supervised learning methods and compares alternative classification approaches.

**Methods used:**
- K-Means based segment creation
- Train/test split
- Feature scaling
- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Confusion matrix
- Precision
- Recall
- F1-score
- Accuracy

**Selected result:**

The final classification models achieved approximately **95% accuracy**, with Logistic Regression and Discriminant Analysis showing similar overall performance.

---

## Analytical Workflow

The projects collectively demonstrate the following workflow:

`Data → Preparation → Exploration → Statistical Analysis → Modelling → Evaluation → Interpretation`

The repository includes examples of both:

- **Unsupervised learning** — clustering and segmentation
- **Supervised learning** — regression and classification

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn
- XGBoost
- SHAP
- Jupyter Notebook

## Skills Demonstrated

- Data cleaning and preparation
- Exploratory data analysis
- Statistical analysis
- Feature analysis
- Data visualization
- Clustering and segmentation
- Regression modelling
- Classification
- Model evaluation
- Model interpretation
- Translating analytical results into practical findings

## Repository Structure

```text
data-analytics-ml-case-studies/
│
├── README.md
│
├── 01_vehicle_fuel_efficiency/
│   └── vehicle_fuel_efficiency_analysis.ipynb
│
├── 02_housing_market_segmentation/
│   └── housing_market_segmentation.ipynb
│
├── 03_house_price_prediction/
│   └── house_price_prediction.ipynb
│
└── 04_housing_segment_classification/
    └── housing_segment_classification.ipynb
