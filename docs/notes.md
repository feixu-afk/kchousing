# Project kchousing notes


# Data sources

Kaggle source: https://www.kaggle.com/harlfoxem/housesalesprediction

Basic data dictionary: https://geodacenter.github.io/data-and-lab//KingCounty-HouseSales2015/

Link to discussion item meaning of CONDITION and GRADE fields: https://www.kaggle.com/harlfoxem/housesalesprediction/discussion/141767

# Data prep

Check the hw1_sklearn_dataprep.ipynb file.

# Modeling and analysis

Model 0: The null model
Model 1: Ridge regression with C=1.0
Model 2: Lasso regression with C=1.0
Model 3: Lasso regression with C=0.01
Model 4: Lasso regression with optimal C value
Model 5: Simple decision tree
Exploration: Examine the prices of those wrongly classified ones with Model 2

Extra Two: Histogram-based Gradient Boosting Classifier & LassoCV

# Workflow
1. Creating a new project folder structure with the cookiecutter-datascience-simple template 
2. Put the project folder under version control using git.
3. Conduct EDA
4. Prepare for the Data Analysis (create lists of variables and partition the dataset)
5. Run Models
6. Commit my changes to version control

# Deliverables

- `kchousing.ipynb`: Jupyter notebook containing the complete analysis
- `kchousing.html`: HTML export of the notebook for easy viewing
- `pandas_profiling_report.html`: HTML export of the automated EDA using pandas-profiling
- `sweetviz_report.html`: HTML export of the automated EDA using sweetviz_report