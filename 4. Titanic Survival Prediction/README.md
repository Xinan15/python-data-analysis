## Titanic Survival Prediction

### Overview
- This project uses machine learning to predict the survival of passengers aboard the Titanic. 
- It involves exploratory data analysis, data cleaning, feature engineering, and building a logistic regression model.

### Technologies Used
- Python
- Pandas
- Scikit-learn

## Dataset Description
### Overview
- The data has been split into two groups:

- training set (train.csv)
  - The training set should be used to build your machine learning models. 
  - For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. 
  - Your model will be based on “features” like passengers’ gender and class. 
  - You can also use feature engineering to create new features.

- test set (test.csv)
  - The test set should be used to see how well your model performs on unseen data. 
  - For the test set, we do not provide the ground truth for each passenger. 
  - It is your job to predict these outcomes. 
  - For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

- We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

### Data Dictionary
**Variable: Definition: Key**
survival: Survival: 0 = No, 1 = Yes<br>
pclass: Ticket class: 1 = 1st, 2 = 2nd, 3 = 3rd<br>
sex: Sex	<br>
Age: Age in years<br>	
sibsp: # of siblings / spouses aboard the Titanic	<br>
parch: # of parents / children aboard the Titanic	<br>
ticket: Ticket number	<br>
fare: Passenger fare	<br>
cabin: Cabin number	<br>
embarked: Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton<br><br>
**Variable Notes**
pclass: A proxy for socio-economic status (SES)<br>
1st = Upper<br>
2nd = Middle<br>
3rd = Lower<br>
age: Age is fractional if less than 1.<br> If the age is estimated, is it in the form of xx.5<br>
sibsp: The dataset defines family relations in this way...<br>
Sibling = brother, sister, stepbrother, stepsister<br>
Spouse = husband, wife (mistresses and fiancés were ignored)<br>
parch: The dataset defines family relations in this way...<br>
Parent = mother, father<br>
Child = daughter, son, stepdaughter, stepson<br>
Some children travelled only with a nanny, therefore parch=0 for them.<br>

***Data Source: Kaggle***<br>
https://www.kaggle.com/competitions/titanic/data?select=train.csv