# Decision_Tree-Random_Forest
Decision Tree &amp; Random Forest
Annual Rainfall Prediction


[Question.pdf](https://github.com/SD-IITKGP/Decision_Tree-Random_Forest/files/9043154/Assignment4.1.pdf)


Loaded the dataset in Python using “loadmat” function and accessed its fields which contains a single matrix called XR that is 357x118. 

Each row refers to a location in India and each column refers to a year.

For each year, calculated the total rainfall over all the locations. 

Calculated the mean (m) and standard deviation (s) of this quantity over all the years (columns).

Assigned labels to each year according to the rule: if the total rainfall in any year is more than m+s, the label is +1, if the total rainfall in any year is below m-s, the label is -1, else the label is 0.

For each year tried to predict the label of each year from rainfall values at different locations, using a Decision Tree of depth 10. 

Used the first 100 years for training using 5-fold cross validation, and the remaining 18 years for testing.

Ploted both training and testing errors.

Repeated the same analysis using a Random Forest and improved the results.

Then Attached a label +1/0/-1 to each location, for each year, according to the rule in above.

Used a Decision Tree of depth 10 to predict the label at each location on any given year, using the labels at the remaining locations in the same year.

For each location, identified the top 10 predictor regions. Once again, use the first 100 years for training with 5-fold cross-validation, and the remaining years for testing.

Repeated the above with random forest.
