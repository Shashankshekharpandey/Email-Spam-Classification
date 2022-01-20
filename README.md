# Email-Spam-Classification
<h2>Workflow</h2>
Mail Data -> Data pre processing -> Train Test Split-> Logistic regression model
New mail --Trained Logistic Regression model --Spam or notspam.
<h4>Dependencies i used</h4>
<br>
  
import numpy as np<br>
import pandas as pd<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.feature_extraction.text import TfidfVectorizer<br>
from sklearn.linear_model import LogisticRegression<br>
from sklearn.metrics import accuracy_score<br>
