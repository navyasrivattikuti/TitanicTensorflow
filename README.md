# TitanicTensorflow

## Analysis of Titanic Survivors Data

## The aim of this report is to analyze the attributes of the passengers on the Titanic and to determine which factors contributed to their survival after the disaster. The data was imported from a titanic.csv file which contains 14 columns describing the attributes of each of the 1310 passengers, with 264 null values for the age column and 1015 for the cabin column.

## Several columns including boat, body, and home_dest were ignored for analysis. From the "describe" function, it was observed that most passengers were young, with an average age of around 30. The pclass mean value suggests that there were more passengers in the 3rd class. The majority of passengers lost their lives, with more than 60% of the passengers being male.

## The data was visualized with plots, and it was observed that most women survived, with only 20% of men surviving. Higher class passengers had better survival rates than those in the other 2 classes. Passengers from Cherbourg had a higher survival rate, and those with known cabins also had a higher survival rate. Children (<16) had a greater chance of survival, and a new column was created to differentiate between children and adults.

## After cleaning the data, 1045 passengers were left for machine learning. Age and sex had high correlation values with survival. The data was split into training and testing data in an 80-20% ratio. Seven models were run, with Decision Tree and Random Forest models achieving the highest accuracy of 85.40% and 85.28%, respectively. The SVC-rbf model had the highest accuracy for the testing model at 81.81%.

## Four layers of neural network using TensorFlow were created, with a training accuracy of 83.25% for 30 Epochs. Testing accuracy was also 83.25%. Predictions were made for Jack and Rose, with a predicted survival rate of approximately 12% for Jack and over 90% for Rose.

## In summary, young girls traveling in higher class had a higher chance of surviving the Titanic sinking.
