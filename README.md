## Diabetes Detection System

### Abstract
In today’s world, we can see many incurable diseases, such as cancer, diabetes etc., and according to one study
of WHO, these all diseases contain mostly genetic nature. Diabetes will become the most prominent disease in
future as today people’s life cycle, work patterns, food are changed, which directly or indirectly cause diabetes.
So, this project aims to analyze the diabetes dataset and find contributing factors such as heredity, daily activity
of a person, education level, gender. Then by using the machine learning model, we predict a person has diabetes
or not and predict the chance of diabetes.

### Introduction
According to many research papers, incurable diseases are mostly 80% genetic, and diabetes is one of the most
widespread fatal diseases. And after this disease, patients face many problems which might affect their organs
like kidneys, eyes, heart. Also, they suffer from other conditions such as high blood pressure, diabetic retinopathy,
hearing loss, vision loss, foot damage, depression, etc. Moreover, suppose they cannot control their sugar level
after diabetes. Therefore, this system has helped them to identify the chance of diabetes so that they can prevent
this by taking some steps or consulting an endocrinologist. In this system, we have considered datasets from all
over the world. It contains 23 features, including genetic nature, gender, sugar level, physical activity, questions
about their current and past month lifestyle and so on. We have pre-processed the data first and then normalized
the data. And we used a pie chart, bar chart, heat matrix, and histogram to visualize and identify the hidden
patterns. After this, we built machine learning models such as logistic regression, linear regression, decision tree,
KNN, and Neural Network models.

### Model
We pre-process and normalize the dataset by splitting the dataset into five unique tables. And then, for predicting
the chance of diabetes, we used different machine learning models. Here we consider the genetic features and
sugar level of the patient. After that, we predict the probability of diabetes occurring in future in a particular
patient, and for that, we used a linear regression model.

### Data
In this system, we used a dataset that contained details of patients from all over the world. This dataset we get is
from Kaggle. Unfortunately, this dataset is not in normalized form and has null values. So firstly, we cleaned all
the datasets, and then we pre-processed the data. In pre-processing, we convert all the categorical features into
numerical values. And some of the columns contain multiple values, so we split those columns and corrected
them to possess unique values. Then, we divide the original dataset into five unique tables and do normalization.
Therefore, after this process, we have processed data.

### Analysis
Our system recognizes the hidden pattern through a pie chart, histogram, bar chart, and heat map. We developed
complex SQL queries for retrieving the data from tables. Then run those queries using the query execution
function of pandas’ library, which provides the data frame resulting from the question. From the graph, we deduct
that among all patients, if we divide patients according to gender, then in the male patient, we got a high risk of
diabetes compared with a female patient. Also, this disease is primarily seen in uneducated or very less educated
persons compared to knowledgeable persons; this might be because an educated person’s lifestyle and work
strategy are different from uneducated people, and educated people get information from social media and other
platforms. Therefore, they become more aware of this disease. And found that this disease is directly related to
genetic features and hypertension. Because many patients with hypertension and their parents got diabetes, they
also have more diabetes. We can also say that this disease relates to the region because this disease is primarily
found in Asian and African people. In contrast, American and pacific people have less chance of diabetes.

### Results
We built a machine learning model using the sklearn library. We develop different four machine learning models,
logistic regression, KNN model, neural network model, decision tree model. We consider only genetic features
and sugar levels to classify the patients. Then we split the dataset into training and testing datasets and trained the
model using the training dataset. And predict the value of the response variable on the test dataset. We calculated
the confusion matrix, and from that, we got accuracy. We got the accuracy of the logistic model, KNN model,
and neural network model, decision model as 0.9087, 0.9023, 0.898, and 0.910033, respectively. So, we got the
decision tree as the best model, developed a decision tree using Graphviz library, and saved a .svg file. We also
create a linear regression model for predicting the probability of occurring diabetes inpatient.

### Conclusion
We can say that by using this system, we can diagnose the chances of diabetes to prevent diabetes by taking
regular steps at an earlier stage. This disease is incurable, so we can only control this disease by doing regular
exercise, taking medicine, maintaining the food cycle. By machine learning model, we got an accuracy of nearly
90%, so we can say that among 90 patients out of 100, we correctly diagnosed the diabetes disease.
Future research directions
We will decide to use a random forest algorithm that is better than a decision tree in the future. And xwe will try
to make our model more effective and efficient so that it gives better results, and for that, we try to pre-process
the dataset. We also want to focus on developing countries from the analysis. For example, we can say that
diabetes is higher in Asian and African people and this continent; many developing countries have. And, these
countries have very little medical equipment, and general awareness is significantly less among the people. Also,
we will detect another disease that occurs after diabetes, or we can say that those diseases happen after diabetes,
such as diabetic retinopathy, heart attack, stroke, vision loss, hearing loss, foot damage, depression, and skin
disease bacterial and fungal infections.

### Reference
We used the sklearn library for implementing the machine learning model. And used pandas’ library for handling
the dataset in a better way.
https://scikit-learn.org/stable/supervised_learning.html#supervised-learning
https://www.sciencedirect.com/science/article/pii/S2405959518304624
