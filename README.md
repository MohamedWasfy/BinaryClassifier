# BinaryClassifier
the problem is to build a model that works best in the data provided here http://bit.ly/widebot-new-binclf-data

# Notes and Describtion of Data

the is mixed between categorical and continous data.
it has some problems 
  1- it follows different distribution between training and validation which causes high variance obvious in the huge difference between val-acc and train-acc for both models 
  either SVM and Decision Tree
  
  2- the 'variable19' feature colum is highly correlated to class label in training set but not in validation which causes a severe difficaulty for the model to generalize (overfittin) it is a must to drop it
  
  3- the "variable19" feature column mostly NAN so it does not has any considerable information (it is dropped as well as the left rows with NAN values)>
  
  4- some of the numeric feature columns has non-numeric char such as commas it had to be cleaned
  
  5- tarining data is not balanced as it severly skewd to "yes." class almost 93% of the data
  
  
  
  
  
  
  
