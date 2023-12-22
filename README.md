# Diabetes Prediction Project
This data science project is dedicated to predicting diabetes using classification data. The heart of the project lies in training the model with labeled data to effectively distinguish between individuals with and without diabetes. Utilizing a Shiny web application, users can conveniently input their data, prompting the model to generate predictions and offering valuable insights into diabetes risk assessment.

# Steps Taken
Here's an overview of the key steps involved in processing the data:

Data Cleaning:
Removed duplicate rows and checked for any missing data.

Data Randomization:
Randomized the dataset to avoid biases and created a subset for analysis.

Data Splitting:
Divided the data into training and testing sets.

Model Training:
Trained multiple models, including LDA, KNN, CART, and RF.

Model Testing:
Evaluated the performance of the trained models.

# Results
In summary, all models demonstrate similar overall accuracy, but there are trade-offs between sensitivity and specificity. Notably, the SVM model boasts the highest sensitivity while having the lowest specificity. The choice of the optimal machine learning model hinges on the specific goals and requirements of the application. If sensitivity is of paramount importance, the SVM model might be the preferred choice. However, for a balance between sensitivity and specificity, models like CART or Random Forest could prove more suitable.
