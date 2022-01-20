# Email-Spam-Classification
Workflow
Mail Data -> Data pre processing -> Train Test Split-> Logistic regression model
New mail --Trained Logistic Regression model --Spam or notspam.
<h1>Dependencies i used<h1><br>
  
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
