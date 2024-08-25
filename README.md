# Customer-Churn-Project

Overview:- The objective of this project is to analyze customer data to identify patterns and predictors of customer churn, allowing the company to take proactive measures to retain customers. The project involves data manipulation, data visualization, and the development of predictive models using machine learning techniques to understand and predict customer churn.

Key Tasks:-

1. Data Manipulation:-

A. Demographic Analysis:-

a. Identified the total number of male customers to understand the gender distribution.

b. Determined the total number of customers whose Internet Service is ‘DSL’ to analyze service preferences.

c. Extracted a subset of data consisting of female senior citizens whose payment method is "Mailed check" and stored the result in a new dataset called ‘new_customer’.

d. Filtered customers with a tenure of less than 10 months or total charges less than $500, and stored the result in ‘new_customer’.

2. Data Visualization:-

A. Churn Distribution:- Created a pie chart to visualize the distribution of customers who are likely to churn, providing a clear picture of the churn rate within the customer base.

B. Internet Service Distribution:- Developed a bar plot to showcase the distribution of customers based on their Internet service type, highlighting the most and least popular services.

3. Model Building:-

Model 1:- Basic Churn Prediction Model

A. Built a sequential neural network model using Keras to predict whether a customer would churn based on their tenure.

B. Model Architecture:-

a. Input layer with 12 nodes and 'Relu' activation function.

b. One hidden layer with 8 nodes and 'Relu' activation function.

c. Used 'Adam' optimizer.

d. Trained the model for 150 epochs.

C. Evaluation:-

a. Predicted churn on the test set and built a confusion matrix.

b. Plotted an 'Accuracy vs Epochs' graph to visualize model performance over time.

Model 2: Churn Prediction with Dropout Layers

A. Enhanced the initial model by adding dropout layers to prevent overfitting.

B. Model Architecture:-

a. Input layer with 12 nodes and 'Relu' activation function, followed by a dropout layer with a dropout rate of 0.3.

b. Hidden layer with 8 nodes and 'Relu' activation function, followed by a dropout layer with a dropout rate of 0.2.

C. Evaluation:-

a. Predicted churn on the test set, built a confusion matrix, and plotted the 'Accuracy vs Epochs' graph.

Model 3: Extended Feature Set Churn Prediction Model

A. Developed a more complex model using 'Tenure,' 'Monthly Charges,' and 'Total Charges' as input features.

B. Model Architecture:-

a. Input layer with 12 nodes and 'Relu' activation function.

b. One hidden layer with 8 nodes and 'Relu' activation function.

c. Used 'Adam' optimizer.

d. Trained the model for 150 epochs.

C. Evaluation:- Predicted churn on the test set, built a confusion matrix, and plotted the 'Accuracy vs Epochs' graph.

Technologies Used:-

1. Jupyter Notebook
2. Keras (Sequential Model)
3. Matplotlib/Seaborn (for Data Visualization)
4. Pandas/Numpy (for Data Manipulation)

Skills Demonstrated:-

1. Data Manipulation and Filtering Techniques
2. Data Visualization and Exploratory Data Analysis (EDA)
3. Sequential Model Building with Keras
4. Use of Dropout Layers to Combat Overfitting
5. Model Evaluation and Interpretation
