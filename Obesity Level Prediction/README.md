# Obesity Level Prediction

## Introduction
This project aims to predict the obesity level of individuals based on various features such as age, gender, height, weight, and lifestyle habits. The prediction task is treated as a classification problem, where the goal is to classify individuals into different obesity levels.

## Dataset
The dataset used in this project contains information about individuals' demographics, lifestyle habits, and obesity levels. It includes features such as age, gender, height, weight, frequency of physical activity, consumption of water and vegetables, family history of overweight, and mode of transportation. The target variable is the obesity level, which is categorized into several classes such as Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III.

## Data Preprocessing
- Categorical columns were label-encoded.
- Continuous columns were standardized using StandardScaler.

##Data Visulisation
- One key aspect of the analysis was visualizing the distribution of ages.
- The analysis focused on whether there was a family history of being overweight.
- A violin plot was used to illustrate the age distribution.
- The plot shows how age distribution differs between individuals with and without a family history of being overweight.
- The shape of each violin plot indicates the density of individuals at different age ranges.
- Wider sections in the plot represent a higher density of individuals at that age range.
  ![image](https://github.com/user-attachments/assets/bbaf74f2-a277-4785-b21c-7cbd075d2985)

-Here is an analysis of the correlation heatmap based on the image provided:
![image](https://github.com/user-attachments/assets/c2921b1a-fa1d-4e63-a8fd-8ef06f471628)


- **Diagonal Values**: Each variable perfectly correlates with itself, indicated by a correlation value of `1.0` (deep red along the diagonal).
- **Age**:
  - Shows a moderate negative correlation with `TUE` (Time using technology) at `-0.30`.
  - Has slight negative correlations with `FAF` (Physical activity frequency) and `CH2O` (Consumption of water).
- **Height and Weight**:
  - Have a moderate positive correlation with each other (`0.46`), suggesting that taller individuals tend to weigh more.
- **FCVC (Frequency of consumption of vegetables)**:
  - Displays low correlations with most variables.
- **NCP (Number of main meals)**:
  - Has a weak positive correlation with `Height` (`0.23`).
- **CH2O (Consumption of water)**:
  - Has a weak positive correlation with `Height` and `Weight` (around `0.20`).
- **FAF (Physical activity frequency)**:
  - Shows a moderate positive correlation with `Height` (`0.29`), suggesting taller individuals may engage in more physical activities.
- **TUE (Time using technology)**:
  - Negatively correlated with `Age` (`-0.30`), indicating that older individuals may spend less time using technology.

Overall, most variables show weak or no significant correlation with each other, except for a few moderate relationships (e.g., between `Height` and `Weight`).


## Algorithms Used
Several classification algorithms were evaluated to predict the obesity level:
- Logistic Regression
- Decision Tree
- Random Forest (Best Performing)
- Gradient Boosting
- Support Vector Machine

## Evaluation
The Random Forest algorithm achieved the highest accuracy of 96.4%. It was selected as the best performing algorithm for this classification task.

## Files Included
- `ObesityDataSet_raw_and_data_sinthetic.csv`: The dataset used for training and testing.
- `Obesity Level Prediction.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: This file providing an overview of the project.

## Instructions
To run the project:
1. Clone the repository: `git clone https://github.com/manushukla2/obesity-level-prediction.git`
2. Navigate to the project directory: `cd obesity-level-prediction`
3. Open the `obesity_prediction.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions in the notebook to execute the code and reproduce the results.

## Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)



