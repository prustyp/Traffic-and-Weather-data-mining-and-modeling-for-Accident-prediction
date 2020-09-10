# “ARE YOU DRIVING SAFE TODAY?" 
## A Data Mining Way of Answering the Question
. Road safety is one of the top most priority of every government and individual. 

. Government spends billions of dollars on making great roadway infrastructure and safety certification of the vehicles, 
so that the lives of the people on the road will be safer. 

. However, there are still a large number of fatal accidents occurring on the road. 

. In the year 2018 alone, the number of fatalities on the road has increased upto 1.28 million. 

. Predicting accidents have thus become one of the widely researched topics which could be used by different agencies for optimizing 
traffic conditions (e.g. adding more lanes in one direction and reversing it when the condition changes), 
provide a dynamic route to riders using GPS and improving overall transportation infrastructure. 

. There are a variety of dataset publicly available for this cause such as accident data, 
traffic event data and weather data. 

. These datasets could be used to prepare useful classification models to predict whether a 
particular condition is more prone to accidents and drivers must drive with precaution.

## Tools
1. Jupyter notebook : 
I have used Jupyter Notebooks as it is a powerful, versatile and shareable tool which provide the ability to perform data visualization in the same environment.
2. Apache Spark : 
Because the data size was very large to be accommodate in my system memory and it required to store the data in multiple dimension, I have used Apache Spark.
PySpark ML libraries : DecisionTreeClassifier, LogisticRegression
3. Pandas Data Frame : 
After merging traffic and weather dataset and removing the null values the dataset became smaller to fit in to memory, so I have used libraries for model preparation on Pandas data frame, which is relatively faster.
Sklearn ML libraries : KNeighborsClassifier, GaussianNB
4. Matplotlib : 
For data visualization and accuracy plots I have used Matplotlib library.
5. sklearn metrics : 
To evaluate the model using accuracy_score, f1_score, precision_score and recall_score.

## Method Explored
1. Data cleaning:
Missing values
Binning
Categorical data handling
2. Data Integration:
Data blending
Feature selection
3. Data Imbalance:
Under sample
4. Data Transformation:
Standard scalar normalization
5. Classification:
KNN, Decision Tree, Naive Bayes, Logistic Regression
6. Visualization:
Bar plot, Line plot

## Result and Lessions
1. I found 85% accuracy in severity prediction and 86% accuracy in predicting a chance of accident.
2. I learned that, using different data mining techniques we could find patterns and correlations within weather and traffic data to predict accident by which, 
we can increase roadway safety and reduce accident risks.
3. knowledge discovery in databases is the key component of datamining which discover hidden connections in weather and accident data and predict future risks.
4. By using different statistics i.e. numeric study of data relationships we could visualize the data.
5. Machine learning algorithms can learn from data to make predictions.
6. I found that different weather condition, road type and temperature could be the cause of an accident.
7. Also, there are some hours of a day and some particular states that are more prone to accident.
8. We could predict an accident with accuracy of 86%, by looking at the pattern and thus could take percussion before head.

