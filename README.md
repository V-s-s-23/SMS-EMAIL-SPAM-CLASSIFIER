# SMS-EMAIL-SPAM-CLASSIFIER

## About dataset :- The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

### DataSet link:- https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

### Task :- To build a prediction model that will accurately classify which texts are spam?

## Steps include in model buildiing-

### 1. Importing data
### 2. Data Analysis
### 3. Performing EDA
### 4. Data cleaning or Text Preprocessing-> Following steps are done in this stage-
#### (a.) Lowering the text
#### (b.) Removing stop words 
#### (c.) Removing punctuations
#### (d.) Applying lemmatization
#### (e.) Using TF-IDF to convert text into vectors

### Model building -> In model building i use various algorithms like- naive bais, multinomial naive bais, random forest classifier and extratree classifier and achive accuracy of 98% and precision score  100% and F1-score 93%

### Model evaluation-> In evaluatioin of model i used accuracy score, precision score, F1-score beacuse dataset was imbalanced and accuracy was not a good evaluation parameter. Among all the models extratree classifier giving good precision , good f1 score as well as good accuracy.
