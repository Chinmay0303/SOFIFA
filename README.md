# Football Player Market Value Prediction
This project focuses on predicting the market values of football players. It is based on data scraped from the SOFIFA website and involves multiple stages including data collection, cleaning, feature engineering, and model creation.

## Project Overview
#### Data Collection: Scraped player data from the SOFIFA website using Beautiful Soup.
#### Data Cleaning & EDA: Used Pandas and NumPy for data manipulation and performed exploratory data analysis (EDA) with Matplotlib and Seaborn.
#### Feature Engineering: Applied feature scaling and selection to prepare the data for the model.
#### Model Creation: Built a Multiple Linear Regression model to predict football player market values.

## 1. Data Collection

### SOFIFA Website Data:

<img width="903" alt="Sofifa" src="https://github.com/user-attachments/assets/352a4c89-166b-4f1a-844d-440adffb8267">

### Scraped Data:

<img width="755" alt="Scraped_Data" src="https://github.com/user-attachments/assets/69686b01-dec5-41a2-8322-4c6f9976b6f2">

## 2. Data Cleaning

### Value: Converted player market values to millions.

<img width="275" alt="Val" src="https://github.com/user-attachments/assets/7b30f3a9-9448-40b2-865b-be1ef75df473">

### Wage: Standardized wages to thousands.

<img width="284" alt="Wage" src="https://github.com/user-attachments/assets/9000aa38-79b4-4e9b-b393-5afc864f4732">


### Release Clause: Standardized release clauses to millions.

<img width="364" alt="newValWageRelea" src="https://github.com/user-attachments/assets/e6d22551-f276-41c4-ac7f-d4d5d94d20c3">


### Height and Weight: Converted player height to centimeters and weight to kilograms.

<img width="212" alt="HeightandWeight" src="https://github.com/user-attachments/assets/40418a64-6546-4e61-8232-c9859c6a6cf3">


<img width="332" alt="HandW2" src="https://github.com/user-attachments/assets/342ef8a8-4377-4228-8e5c-69b6fa70a403">


### Team & Contract: Split the combined column into two separate columns for better clarity.

<img width="362" alt="TeamContract" src="https://github.com/user-attachments/assets/1da7f4c8-820b-4bd8-b3de-964eaa869c51">

<img width="481" alt="TeamContr2" src="https://github.com/user-attachments/assets/c763a9e3-cd29-489f-9d32-c0fdd7071898">



### Feature Datatypes: Corrected the datatype for each feature.
### Missing Values: Addressed any missing values by applying appropriate techniques such as imputation or removing incomplete entries.


