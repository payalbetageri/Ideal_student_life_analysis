We have used 2 datasets “survey_questions_meta” and “survey_responses” on which we have worked for the whole project. 
Our Project has two parts in it, EDA visualization part and modelling part.

EDA Visualization:

The project file “EDA_Visualization_DA_Part_1.ipynb” contains the cleaning of the datasets and EDA . 

Modelling part:

Coming to the modelling(model.ipynb), we have used a Decision Tree Classifier, Random Forest classifier and Logistic Regression to classify the level of stress, which is the dependent column. This is predicted using Career, nationality, department, housing type, year of study, levels of stress on the scale of 1-10, reasons behind stress etc. 
The accuracy for these models aren’t that high due to bias and some faults in the dataset hence hindering the predictions.
We tried predicting the types of stresses using single-label classifier but it gave 100% accuracy as people do have more than one type of stress and hence any stress it predicts would match with the y_test values. Thus we tried shifting from single-label to multi-label classification but the accuracy score went below 30%, hence couldn’t be considered as a useful model.
Most of the data in our dataset is categorical and had string value which had to be converted to integer and create another dataset with the rectified values. 
The code is read to use, hence there won’t be any modifications required to do from your end.

