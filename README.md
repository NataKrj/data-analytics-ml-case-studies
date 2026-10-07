# Data Analytics & Machine Learning Case Studies

A portfolio collection of applied analytics projects developed in Python. The repository demonstrates a progression from exploratory data analysis to unsupervised learning, regression, classification and model interpretation.

The projects use non-client datasets and are presented as independent analytical case studies. They do not contain confidential or proprietary information.

## Projects

### 1. Vehicle Fuel Efficiency Analysis

Explores how engine size, horsepower, vehicle weight, acceleration and other characteristics relate to fuel efficiency.

**Methods:** exploratory data analysis, descriptive statistics, visualisation, Pearson correlation, cross-tabulation and pairwise analysis.

**Selected findings:** MPG shows strong negative relationships with vehicle weight and engine displacement, while horsepower and displacement are strongly positively related.

[Open notebook](01_vehicle_fuel_efficiency/vehicle_fuel_efficiency_analysis.ipynb)

### 2. California Housing Market Segmentation

Uses unsupervised learning to explore whether housing observations can be grouped into meaningful segments based on housing, demographic and economic characteristics.

**Methods:** hierarchical clustering, standardisation, K-Means, ANOVA, silhouette analysis, elbow method and cluster profiling.

The project also illustrates an important modelling point: different cluster-validation methods can suggest different solutions, so statistical diagnostics should be considered together with interpretability and use case.

[Open notebook](02_housing_market_segmentation/housing_market_segmentation.ipynb)

### 3. House Price Prediction & Feature Analysis

Investigates property price drivers and develops regression-based prediction models using structural and quality characteristics of residential properties.

**Methods:** exploratory analysis, correlation analysis, OLS regression, residual diagnostics, outlier treatment, stepwise selection, prediction intervals, polynomial regression, XGBoost and SHAP.

**Selected result:** the original linear model reported R² of approximately **0.654**, increasing to approximately **0.688** after removal of large-residual outliers.

[Open notebook](03_house_price_prediction/house_price_prediction.ipynb)

### 4. Housing Segment Classification

Combines unsupervised and supervised learning. K-Means is used to create housing segments, after which Logistic Regression and Linear Discriminant Analysis are used to reproduce the segment assignment.

**Methods:** K-Means, standardisation, Logistic Regression, LDA, confusion matrices, precision, recall, F1-score and accuracy.

**Important limitation:** the target classes are generated from the same variables used for classification. The high reported accuracy therefore demonstrates recovery of the clustering structure rather than prediction of an independent real-world outcome.

[Open notebook](04_housing_segment_classification/housing_segment_classification.ipynb)

## Analytical workflow

`Data → Preparation → Exploration → Modelling → Evaluation → Interpretation`

## Technologies

Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy · scikit-learn · statsmodels · XGBoost · SHAP · Jupyter Notebook

## Repository structure

```text
data-analytics-ml-case-studies/
├── README.md
├── requirements.txt
├── data/
│   └── README.md
├── 01_vehicle_fuel_efficiency/
│   └── vehicle_fuel_efficiency_analysis.ipynb
├── 02_housing_market_segmentation/
│   └── housing_market_segmentation.ipynb
├── 03_house_price_prediction/
│   └── house_price_prediction.ipynb
└── 04_housing_segment_classification/
    └── housing_segment_classification.ipynb
```

## Portfolio note

These notebooks were reorganised for portfolio presentation. The analytical content and reported results are based on the original project work, while the public versions use clearer structure, neutral filenames and additional methodological notes where needed.
