# Data-Science
#Prodigy Infotech Internship-Task1
#importing the matplot library in pandas
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
#upload a csv file
data=pd.read_csv('/content/sample_data/age1.csv')
data.head()
#command to create a histogram"
x=data['Country']
y=data['0-4 years']
plt.barh(x,y)
