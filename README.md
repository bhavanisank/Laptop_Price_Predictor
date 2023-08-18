# Laptop_Price_Predictor

# Description

This is a complete Machine Learning Project with  an User Interface Provided to predict the price of a laptop based on the given inputs by the user.
Here the user enters details like Company Name,Type Name, Inches, Screen resolution, Cpu, Ram, Memory, Gpu, OS Type, and Weight and the model predicts the price of the laptop and  displays to the user.
The Stages that were performed in this project are:

*Data Cleaning

*EDA

*Feature Engineering

*Modelling

*Website Creation[Streamlite API]

# Feature Engineering
It is a Process where we create new Features form the existing data to improve the model perfomance.The Entire Project is based on feature Engineering which requires domain knowledge.
For example from the Screen Resolution :IPS Panel Retina Display 2560x1600   Label we created new Labels such as:-              
           
                        *IPS Label
                        
                        *Screen Resolution[x_val,y_val]
                        
                        *PPI[pixels per inch]
 Similarly Feature engineering is applied for several other columns such as CPU, Memory, GPU, OS  etc.

#  Modelling
Several Regression models were applied like Linear regression ,KNN , Decision tree out of which random Forest outperformed in terms of R2_Score and Mean Absolute Error.

# Dataset Link:
https://www.kaggle.com/datasets/ganeshmohane/laptop-datacsv

# Kaggle Notebook Link:
https://www.kaggle.com/code/bhavani124/laptop-price-predictor/edit/run/140302312

                        

                        
