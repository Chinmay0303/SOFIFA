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

<img width="362" alt="TeamContract" src="https://github.com/user-attachments/assets/1da7f4c8-820b-4bd8-b3de-964eaa869c51"><img width="481" alt="TeamContr2" src="https://github.com/user-attachments/assets/c763a9e3-cd29-489f-9d32-c0fdd7071898">



### Feature Datatypes: Corrected the datatype for each feature.
### Missing Values: Addressed any missing values by applying appropriate techniques such as imputation or removing incomplete entries.

## 2. EDA

### Distribution of Continuous Features

![image](https://github.com/user-attachments/assets/c97a9c25-cc47-4c5c-952a-014f0f1ff9db)

![image](https://github.com/user-attachments/assets/a0c6fbc7-f6af-4f95-8199-0786e0e06afb)

![image](https://github.com/user-attachments/assets/80004b38-913b-4c94-b618-89ec514b37a0)

### Relation b/w Continuous Features and Value_Mill

![image](https://github.com/user-attachments/assets/631a871d-9422-4f77-b1d2-7ab6c3968dda)

![image](https://github.com/user-attachments/assets/efd93371-66a2-43df-adc9-8af16db11aa8)

![image](https://github.com/user-attachments/assets/7b4779c5-da05-4da8-98d5-0a6fad88aede)

![image](https://github.com/user-attachments/assets/de0fdd60-54ac-40b1-900c-df0a78aba0ea)

### Distribution of Discrete Features

![image](https://github.com/user-attachments/assets/2d63d192-2568-49b0-ad02-6910f282ad52)

![image](https://github.com/user-attachments/assets/5cf432de-8b61-4a85-892e-b83a68b1e505)

### Relation b/w Discrete Features and Value_Mill

![image](https://github.com/user-attachments/assets/d66a8c30-86a7-4e15-9fef-4bc891aafc49)

![image](https://github.com/user-attachments/assets/97555e98-9b31-4051-a7ac-753fee1de4cd)

### Strip Plot

![image](https://github.com/user-attachments/assets/1725e1ee-424e-4c17-9e16-f8596fb71a24)

![image](https://github.com/user-attachments/assets/a4f1f6a9-1fad-482d-93b3-9612b95ed2fd)




## Model Prediction:

<img width="383" alt="ModelPred1" src="https://github.com/user-attachments/assets/593834c1-4702-442b-96b1-65779dec5446">

<img width="564" alt="ModelPred2" src="https://github.com/user-attachments/assets/f80a4c47-c456-47f4-9691-ef75083fc49b">
