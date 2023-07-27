# Titanic: Machine Learning from Disaster


## The challenge:

The competition is simple: To use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die.


### (1) train.csv:
"train.csv" contains the details of a subset of the passengers on board (891 passengers, to be exact -- where each passenger gets a different row in the table).

The values in the second column ("Survived") can be used to determine whether each passenger survived or not:

if it's a "1", the passenger survived.
if it's a "0", the passenger died.
For instance, the first passenger listed in train.csv is Mr. Owen Harris Braund. He was 22 years old when he died on the Titanic.

### (2) test.csv:
Using the patterns in train.csv, you have to predict whether the other 418 passengers on board (in test.csv) survived.

### (3) gender_submission.csv:
The gender_submission.csv file is provided as an example that shows how should predictions be structure. It predicts that all female passengers survived, and all male passengers died. This hypotheses regarding survival will probably be different, which will lead to a different submission file. 

A "PassengerId" column containing the IDs of each passenger from test.csv.
A "Survived" column (that you will create!) with a "1" for the rows where you think the passenger survived, and
A "0" where you predict that the passenger died.

## Used Python Libraries:
* Pandas
* Numpy
* Scikit-learn
* Machine learning Library: Random Forest Classifier
