## Hi there 👋
**About the Project**

**Stroke Prediction Using Machine Learning**

According to the World Health Organization (WHO), stroke is the second leading cause of death globally, accounting for approximately 11% of all deaths. This project utilizes a dataset to predict whether a patient is likely to experience a stroke based on various input parameters such as gender, age, medical history, and smoking status. Each row in the dataset provides relevant information about a patient.

**Libraries and Tools Used**

The following libraries and tools were used in this project:

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Scikit-learn: For machine learning algorithms and preprocessing.

Matplotlib: For data visualization.

Seaborn: For statistical data visualization.

Warnings: To handle warnings in the code.

MLxtend: For feature selection.

MPL Toolkits: For 3D plotting.

**Dataset Information**

The dataset used in this project is the "Healthcare-dataset-stroke-data". It includes the following attributes:

id: Unique identifier

gender: "Male", "Female", or "Other"

age: Age of the patient

hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension

heart_disease: 0 if the patient doesn't have any heart disease, 1 if the patient has a heart disease

ever_married: "No" or "Yes"

work_type: "children", "Govt_job", "Never_worked", "Private", or "Self-employed"

Residence_type: "Rural" or "Urban"

avg_glucose_level: Average glucose level in blood

bmi: Body Mass Index

smoking_status: "formerly smoked", "never smoked", "smokes", or "Unknown"

stroke: 1 if the patient had a stroke, 0 otherwise

**Data Preprocessing**

Loading and Cleaning Data: The dataset was loaded and unnecessary columns (like id) were removed. Missing values in the bmi column were filled with the mean value of that column.

Correlation Analysis: A heatmap was used to visualize the correlation between features and the target variable
.
Data Visualization: Count plots and box plots were used to review the distribution and relationships in the data.

**Models and Evaluation**

The project involves fitting several machine learning models to the dataset:

Decision Tree Classifier

Accuracy on testing set: ~95%

Logistic Regression

Accuracy on testing set: ~95%

K-Nearest Neighbors (KNN)

Optimal K value: 8

Accuracy on testing set: ~96%

**Feature Selection and Dimensionality Reduction**

Backward and Forward Feature Selection: Implemented using MLxtend's SequentialFeatureSelector.

Principal Component Analysis (PCA): Used to reduce dimensionality and visualize data in 2D and 3D plots.

**Advanced Techniques**

K-Fold Cross-Validation: To ensure the model's reliability.

Bootstrap Method: To enhance the model's robustness by resampling the dataset.

**Results**

The project demonstrates the use of various machine learning techniques and preprocessing steps to predict stroke occurrence with high accuracy. It highlights the importance of data cleaning, feature selection, and model evaluation in building reliable predictive models.

**Conclusion**

This project provides a comprehensive approach to predicting stroke using machine learning, offering insights into the preprocessing and modeling steps required for achieving high accuracy. The use of different models and evaluation techniques ensures the robustness and reliability of the predictions.
#ML #KNN #Data_Preprocessing #Decision_Tree #Logistic_Regression #Cross_Validation #Bootstrap_Method
