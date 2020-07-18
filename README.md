# Airline-Passenger-Satisfaction
The dataset is available in kaggle. https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction

# Problem Statement
Like any service, Airlines depends entirely on customers, as they are the one paying for it. Airlines spend millions on understasnding customer satisfaction. This dataset uses various variables and to determine which variables contribute most to passengers satisfaction.
# Problem Type
Here the output is either 0(neutral or dissatisfied) or 1(satisfied). This is a classification problem - understaanding whether the customer is satisfied or dissatiisfied.
#Data processing
The dataset was collected from kaggle. It was a mostly pre cleaned dataset. However, there were some missing values in column "Arrival Delay in Minutes" which was then filled with median values
# Data Visualization
a few methods were used:
1. Boxplot for all the variables
2. Heatmap for correlations and variables with highest correlation
3. Kdeplot for age distribution for different genders
4. Violinplot and Catplot for Age distribution
5. Displot for Flight distance 

# Modeling

1.Data was already split between test and train.

2. Used correlation matrix to determine top 10 variables nd different classification modeles were applied. Top 10 variables were kept to  minimise the use of memory.

3. Different classification models such as Logistic regression, Random Forest Classifier, Gaussian Naive Bayes model, K Neighbors Classifier and at last Decision Tree Classifier.

4. Confusion matrix and accuracy was shown

5. Random Forest Classifie provided the best result wih 93%


