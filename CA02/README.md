CA02 Assignment - Spam Email Detection using Naive Bayes -- Max Kaiser 


**Assignment Description:**

*Step 1:* Training the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. 

*Step 2:*  Test the model on 260 emails. Model will try to predict the category of the emails and compare the accuracy with correct classification that we already know

Assumptions: independence in features 

2 Files: 

train-mails --> 442 files
test-mails --> 260 files


**Packages to import:**

import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score


**Downloading & Accessing the Data**

Please find two zip files titled 'CA02_Data' to download the data files.

Download data and save in your desired google colab folder. Note the path to these folders as you will need it when reading the data in later

In order to access the data you have just saved to your google colab folder you need to add the following code before running the program. If you do not import the drive you will get an error saying that the file could not be found given the path you gave.

from google.colab import drive
drive.mount('/content/drive')
When reading in your data files from your selected google colab folder when downloaded please make adjustments to the file path as needed to access your selected folder. My folder paths are as follows:

TRAIN_DIR = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/train-mails"
TEST_DIR = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/test-mails"
Code Comments

Please feel free to reach out if you have any questions or issues with accessing or understanding any documents 

Contact me via email at mkaiser6@lion.lmu.edu or via Teams :) 
