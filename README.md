<h1>Mental Health Prediction Using<br />Machine Learning</h1>

This project aims to use machine learning techniques to predict mental health conditions in individuals based on their demographic and socio-economic information. The dataset used for this project is taken from Kaggle and contains survey responses from individuals working in the technology industry.

**Table of Contents**<br />
Background<br />
Dataset Description<br />
Methodology<br />
Installation and Usage<br />
Results<br />
Conclusion<br />
<br />
Mental health issues are a growing concern in our society. According to the World Health Organization, approximately 1 in 4 people in the world will be affected by mental or neurological disorders at some point in their lives. However, despite the prevalence of these issues, there is still a significant lack of understanding and awareness surrounding them. This project aims to contribute to the effort to improve mental health outcomes by creating a model that can predict mental health conditions in individuals based on their demographic and socio-economic information.

**Dataset Description**<br />
The dataset used in this project is taken from Kaggle and contains survey responses from individuals working in the technology industry. It contains information on the respondents' demographics, employment details, and mental health status. The dataset has 27 columns and 1259 rows.

**Methodology**<br />
The project is implemented using the following steps:

Data Preparation: In this step, we preprocessed the data by performing cleaning, handling missing values, and encoding categorical variables.

Exploratory Data Analysis (EDA): In this step, we analyzed the data to understand its distribution, correlation, and patterns.

Feature Selection: We selected the most relevant features to train the model and eliminate the irrelevant ones using various feature selection techniques.

Model Selection: We selected a machine learning model that can best fit our problem statement. We used multiple algorithms like logistic regression, decision trees, and random forests, KNN Classifier, AdaBoost Classifier, Gradient Boosting Classifier, XGB Classifier to evaluate their performance.

Model Evaluation: In this step, we evaluated the performance of the model using various evaluation metrics like accuracy, precision, recall, and F1-score.

**Installation and Usage**<br />
Clone the repository to your local machine.<br />
Install the required packages using pip install -r requirements.txt<br />
Run the main.py file to start the program.<br />
Follow the instructions on the console to input the necessary information for the model.<br />
Results<br />
After evaluating multiple machine learning models, we found that the AdaBoost Classifier performs the best in terms of accuracy, precision, recall, and F1-score. The model achieves an accuracy of 86.93% in predicting whether an individual has a mental health condition or not.

**Conclusion**<br />
In conclusion, the model developed in this project can be a useful tool for predicting mental health conditions in individuals based on their demographic and socio-economic information. With further improvements, this model can be integrated into mental health screening tools to provide early intervention and treatment for individuals who may be at risk.
