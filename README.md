# facial_expression
i take the data from fer2013 in kaggle https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge

i build two model:
- fisrt, i use CNN networks, the accuracy is approximated 53%. You can see in file data_analysis
- Second, i extract the facial landmarks, then i determine the center point and consider the original cordinate
  Next, i compute the distance each point to this point, and direction to point
  The accuracy is approximated 55%
 
 i saw the model that the accuracy of this can obtain 71% if use the deep CNN + facial landmarks, but my computer's opacity is limited
 This is basic the model to detect emotion
