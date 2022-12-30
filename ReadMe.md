# **CO2 Emission** 

## A reliable End to End Machine Learning Model to predict CO2 Emissions. ##

## **Description:** ##

The task is to build a machine learning model to predict CO2 emissions by countries based on features such as:
 trade_co2
 cement_co2
 population

     
This Project also aims at testing the influence of different independent features on the emission of CO2 using statistical methods.


## **DataSet**:
- The dataset has been taken from the Canada Government 
     official open data website and is available in kaggle
- Cleaned and processed version of the data can be accessed 
     from my project.
- Dataset contains 7385 datapoints and 58 columns.

We experimented with different methods for model building

    Linear Regression
    Ridge Regression
    Knn Regression
    DT Regression

![Imagelink](https://github.com/leeladhar449/challenges/blob/main/Screenshot%202022-12-30%20202854.png)


# **Techstack** #

Python version : 3.7

Packages: pandas, numpy, seaborn, sklearn

Usage [running locally]:

git clone https://github.com/d0r1h/CO2-Emission-by-Cars.git

cd CO2-Emission
pip install -r requirements.txt
python app.py

Results
---

- Ridge Regression (with alpha = 0.5) has been the most effective in reducing RMSE.
-   The exact combination of features responsible for high CO2 emissions cannot be predicted Since all the features are highly correlated.
- Following image shows score table for different models

![imagelink](https://github.com/leeladhar449/challenges/blob/main/Screenshot%202022-12-30%20204334.png)

Inference Demo:

Application is deployed using streamlit and can be accessed in our github page and following data can be used to test the application.
![Imagelink](https://github.com/leeladhar449/challenges/blob/main/Screenshot%202022-12-30%20205213.png)