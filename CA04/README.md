
***CA04 Assignment - Ensemble Methods -- Max Kaiser***


**Assignment Description:**

1. Data Source and Contents

The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. The following is a description of our dataset:

• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]

• Number of attributes (Columns): 7

• Number of instances (Rows): 48,842

The data is provided in a .csv file and you can downlaod it from the following GitHub link https://github.com/ArinB/MSBA-CA-03-Decision-Trees 

and save it on your local drive/folder. 

File: 

census_data.csv

______________________________________________________________________________________________________________________

**Packages to import:**

import pandas as pd 
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn import preprocessing 

from sklearn.preprocessing import LabelEncoder 
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier
from sklearn.ensemble import GradientBoostingClassifier
from xgboost import XGBClassifier
from sklearn.metrics import accuracy_score, roc_auc_score 
______________________________________________________________________________________________________________________


**Installation Instructions**


Please download the file on your computer and run the following code: 

from google.colab import files

uploaded = files.upload()


Next: choose census_data.csv file from your local computer 

______________________________________________________________________________________________________________________

Please feel free to reach out if you have any questions or issues with accessing or understanding any documents 

Contact me via email at mkaiser6@lion.lmu.edu or via Teams :) 
