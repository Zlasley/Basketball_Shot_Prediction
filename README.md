# Basketball_Shot_Prediction11

This dataset contains an NBA player's field goal attempts from October 2009 through June 2019 (regular season and playoffs). 

The dataset was collected with the nba_api Python library.

This covers over parsing dates, feature engineering, baseline accuracy, modeling, and confusion matric (prescision & recall).

# Imports

pandas

numpy

matplotlib.pyplot

sklearn.tree import DecisionTreeClassifier

sklearn.ensemble import RandomForestClassifier

sklearn.model_selection import train_test_split, KFold, GridSearchCV, cross_val_score , RandomizedSearchCV

sklearn.metrics import classification_report, ConfusionMatrixDisplay

category_encoders import OrdinalEncoder

sklearn.impute import SimpleImputer

sklearn.pipeline import make_pipeline

sklearn import datasets, metrics

sklearn.metrics import accuracy_scoreimport
