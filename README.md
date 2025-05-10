from ast import Import
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

credit_card_data = pd.read_csv('creditcard.csv')

print(credit_card_data['Class'].value_counts())# my-first-repository
