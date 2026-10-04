# Machine Learning Algorithms in Python

A collection of Jupyter notebooks where I implement and practise core machine learning algorithms with scikit-learn, as part of my self-directed data analytics and ML curriculum.

Each notebook works through one algorithm or technique: loading data, preparing it, fitting a model, evaluating it and, where it matters, tuning it.

## Contents

### Supervised learning: classification

| Notebook | What it covers |
|---|---|
| [Classification](Classification.ipynb) | End-to-end classification workflow |
| [LogisticRegression](LogisticRegression.ipynb) | Logistic regression |
| [KNearestNeighbours](KNearestNeighbours.ipynb) | K-Nearest Neighbors classifier |
| [decision_tree](decision_tree.ipynb) | Decision trees |
| [Gaussian_naive_based_Algorithm](Gaussian_naive_based_Algorithm.ipynb) | Gaussian Naive Bayes |
| [RandomForestClassifer](RandomForestClassifer.ipynb) | Random forest classifier |
| [AdaBoost](AdaBoost.ipynb) | AdaBoost |
| [GradientBoosting](GradientBoosting.ipynb) | Gradient boosting |
| [SVC_Pipeline_Parameter_Tuning](SVC_Pipeline_Parameter_Tuning.ipynb) | Support vector classifier with pipelines and parameter tuning |

### Supervised learning: regression

| Notebook | What it covers |
|---|---|
| [LinearRegressioner](LinearRegressioner.ipynb) | Linear regression |
| [KNeighborsRegressor](KNeighborsRegressor.ipynb) | K-Neighbors regressor on the Iris data (predicting petal width): train/test split, scaling, tuning k, R² and RMSE |

### Unsupervised learning: clustering

| Notebook | What it covers |
|---|---|
| [Kmeans](Kmeans.ipynb) | K-Means clustering |
| [DBSCAN](DBSCAN.ipynb) | Density-based clustering on synthetic ring data with noise, compared with K-Means and Agglomerative clustering |
| [Mean_Shift_Clustering](Mean_Shift_Clustering.ipynb) | Mean shift clustering |

### Data preparation, tuning and analysis

| Notebook | What it covers |
|---|---|
| [DataPreprocessing](DataPreprocessing.ipynb) | Preparing data for modelling |
| [GridSearch](GridSearch.ipynb) | Hyperparameter tuning with grid search |
| [Target](Target.ipynb) | Target analysis |

### Customer segmentation experiment

| Notebook | What it covers |
|---|---|
| [RFA](RFA.ipynb) | An attempt to predict customer segments (New, Regular, VIP) with random forest, XGBoost and SMOTE |

This one is a **negative result**, kept on purpose. The best model reached about 59.5% accuracy against a 55.5% majority-class baseline, with a macro F1 of about 0.34 and almost no VIP predictions. The features available did not separate the segments, and the notebook shows how I tested that, including checking for data leakage.

## Tools

Python, pandas, NumPy, scikit-learn, matplotlib, imbalanced-learn, XGBoost, Jupyter Notebook

## How to run

1. Clone the repository.
2. Install the dependencies:
   ```
   pip install pandas numpy scikit-learn matplotlib jupyter imbalanced-learn xgboost
   ```
3. Open any notebook in Jupyter or VS Code and run the cells.

## Datasets

The data files are in the [Datasets](Datasets) folder.

<!-- TODO: add one line on where the datasets came from (Kaggle, UCI, etc.) and check each licence. For very large files such as OnlineRetail.csv, link to the source instead of uploading it. -->

## Also learning

SQL (MySQL): joins, CTEs, window functions and a data-cleaning project, plus regular practice problems on LeetCode.

## About

I'm Bethuel Kiprono, an Electrical and Telecommunications Engineering graduate based in Nairobi, learning data science and machine learning.

GitHub: [sabhsTM](https://github.com/sabhsTM)
