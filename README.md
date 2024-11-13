

## Introduction

This repository contains a comprehensive set of Exploratory Data Analysis (EDA) projects focusing on various predictive modeling tasks across different domains. The projects aim to explore, visualize, and analyze datasets to uncover patterns, correlations, and insights that inform the predictive capabilities of machine learning models. The repository is structured into the following sections:

1. **Obesity Level Prediction**: Analyzing individual demographics and lifestyle factors to predict obesity levels and assess contributing features.
2. **Heart Failure Survival Prediction**: Investigating clinical data to determine key factors influencing survival rates in heart failure patients.
3. **Car Sales Prediction**: Examining car sales data to identify trends, influential variables, and patterns to enhance sales forecasting models.
4. **Online Education Adaptability**: Understanding the factors that affect adaptability in online education, focusing on student engagement and learning outcomes.

Each section includes EDA, data preprocessing, and visualizations to provide a solid foundation for building predictive models and making data-driven decisions.

---

Make sure that the headings for each section in your README file are formatted exactly as listed above (e.g., `## Obesity Level Prediction`) so that the links navigate correctly.

## Obesity Level Prediction

![image](https://github.com/user-attachments/assets/6ecfab0f-3a47-44c4-9dc8-535623c5fb1b)


### Introduction
This project aims to predict the obesity level of individuals based on various features such as age, gender, height, weight, and lifestyle habits. The prediction task is treated as a classification problem.

### Dataset
The dataset contains information about individuals' demographics, lifestyle habits, and obesity levels. It includes features such as age, gender, height, weight, frequency of physical activity, and water consumption.

### Data Preprocessing
- Categorical columns were label-encoded.
- Continuous columns were standardized using StandardScaler.

### Data Visualization
- Visualized the distribution of ages and the relationship with family history of being overweight using violin plots.
- Created a correlation heatmap to analyze relationships between features.

### Algorithms Used
Several classification algorithms were evaluated:
- Logistic Regression
- Decision Tree
- Random Forest (Best Performing)
- Gradient Boosting
- Support Vector Machine

### Evaluation
The Random Forest algorithm achieved the highest accuracy of 96.4%.

### Files Included
- `ObesityDataSet_raw_and_data_sinthetic.csv`: The dataset used for training and testing.
- `Obesity Level Prediction.ipynb`: Jupyter Notebook for data preprocessing, model training, and evaluation.
- `README.md`: This file.

### Instructions
1. Clone the repository: `git clone https://github.com/manushukla2/obesity-level-prediction.git`
2. Navigate to the project directory: `cd obesity-level-prediction`
3. Open the `obesity_prediction.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions to execute the code and reproduce the results.

### Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)


## Car Sales Prediction

![image](https://github.com/user-attachments/assets/6377ec1b-9fd8-4374-bc91-83b765a6b414)


### Introduction
This project aims to predict car sales based on various features such as manufacturer, model, year, and other attributes. The prediction task is treated as a regression problem.

### Dataset
The dataset contains information about car sales, including features such as manufacturer, model, year, price, and other relevant attributes.

### Data Preprocessing
- Categorical columns were encoded.
- Continuous columns were standardized.

### Data Visualization
- Visualized sales trends over the years.
- Created correlation heatmaps to analyze relationships between features.

### Algorithms Used
Several regression algorithms were evaluated:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (Best Performing)
- Gradient Boosting Regressor

### Evaluation
The Random Forest Regressor achieved the highest accuracy in predicting car sales.

### Files Included
- `CarSalesData.csv`: The dataset used for training and testing.
- `Car Sales Prediction.ipynb`: Jupyter Notebook for data preprocessing, model training, and evaluation.


### Instructions
1. Clone the repository: `git clone https://github.com/manushukla2/car-sales-prediction.git`
2. Navigate to the project directory: `cd car-sales-prediction`
3. Open the `car_sales_prediction.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions to execute the code and reproduce the results.

### Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)


## Heart Failure Prediction

![image](https://github.com/user-attachments/assets/d2e7fc4c-3334-489d-b67e-4f7a151cad73)


### Introduction
This project aims to predict heart failure based on various features such as age, gender, blood pressure, cholesterol levels, and other medical attributes. The prediction task is treated as a classification problem.

## Dataset
The dataset contains medical information about patients, including features such as age, gender, blood pressure, cholesterol levels, and other relevant attributes.

### Data Preprocessing
- Categorical columns were encoded.
- Continuous columns were standardized.

### Data Visualization
- Visualized the distribution of medical attributes.
- Created correlation heatmaps to analyze relationships between features.

### Algorithms Used
Several classification algorithms were evaluated:
- Logistic Regression
- Decision Tree
- Random Forest (Best Performing)
- Gradient Boosting
- Support Vector Machine

### Evaluation
The Random Forest algorithm achieved the highest accuracy in predicting heart failure.

### Files Included
- `HeartFailureData.csv`: The dataset used for training and testing.
- `Heart Failure Prediction.ipynb`: Jupyter Notebook for data preprocessing, model training, and evaluation.
- `README.md`: This file.

### Instructions
1. Clone the repository: `git clone https://github.com/manushukla2/heart-failure-prediction.git`
2. Navigate to the project directory: `cd heart-failure-prediction`
3. Open the `heart_failure_prediction.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions to execute the code and reproduce the results.

### Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)


## Online Education Adaptability

![image](https://github.com/user-attachments/assets/88896fa6-ed3d-4eca-9dc3-8a335918049c)


### Introduction
This project aims to predict the adaptability of students to online education based on various features such as age, gender, internet access, and other attributes. The prediction task is treated as a classification problem.

### Dataset
The dataset contains information about students' demographics and their adaptability to online education, including features such as age, gender, internet access, and other relevant attributes.

### Data Preprocessing
- Categorical columns were encoded.
- Continuous columns were standardized.

### Data Visualization
- Visualized the distribution of adaptability scores.
- Created correlation heatmaps to analyze relationships between features.

### Algorithms Used
Several classification algorithms were evaluated:
- Logistic Regression
- Decision Tree
- Random Forest (Best Performing)
- Gradient Boosting
- Support Vector Machine

### Evaluation
The Random Forest algorithm achieved the highest accuracy in predicting online education adaptability.

### Files Included
- `OnlineEducationData.csv`: The dataset used for training and testing.
- `Online Education Adaptability.ipynb`: Jupyter Notebook for data preprocessing, model training, and evaluation.
- `README.md`: This file.

### Instructions
1. Clone the repository: `git clone https://github.com/manushukla2/online-education-adaptability.git`
2. Navigate to the project directory: `cd online-education-adaptability`
3. Open the `online_education_adaptability.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions to execute the code and reproduce the results.

### Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)

---

