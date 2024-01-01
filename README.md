# Machine Learning Project 1

### This is my first ML project so bear with me

## Some ML Concepts

confusion matrix with respect to Machine 
Learning algorithms:

• A Confusion matrix is an n * n matrix used for evaluating the performance of a 
classification model, here N is the number of target classes. This matrix compares 
the actual target values with values that are predicted by the machine learning 
model. This model provides us with a better view of the model and the errors that 
it has been making.

• Example for a binary classification model we have predicted values and the 
actual values on the that are represented in the 2*2 matrix, and the target 
variables have two values that are either positive or negative.

• The actual values of the target variables are represented as columns in the 
matrix and the rows are represented by the predicted values.

• The main reason to use the confusion matrix is to counter and check If the 
model’s classification accuracy is biased on the particular class, which might be 
contributing to the accuracy of the model. This is the time when the Confusion 
matrix comes in to play. Hence confusion matrix can find the inner details and 
errors of the classification accuracy of the model.



Precision and Recall:

Recall is the ratio of number of events we can correctly recall to all correct events, 
for example suppose if we have 100 events and we can recall 90 events correctly 
then the recall ratio is 90%. And to associate precision with recall, suppose we 
have 100 events(again!), and we can recall all of them but in these 50 events are 
correct and 50 events are wrong that means we can recall all events but they are 
not precise, precision is the ratio of number of events we can correctly recall, and 
number of events we can recall including both correct and incorrect. Because we 
cannot solely rely on precision and recall as the algorithm can be good at recall but 
it may not have great precision, here the F1 score comes into play, F1 score is a
harmonic mean of precision and recall which is used to evaluate the algorithm.


Precision/Recall trade-off:

precision and recall are metrics of performance for classification algorithms. 
Consider a classification task with two classes. Precision is how many times an 
accurate prediction of a particular class occurs per false prediction of that class. 
Recall is the percentage of the data belonging to a particular class which the model 
properly predicts as belonging to that class. Another way to think of this is to first 
define true positives, false positives, and false negatives (see the table below¹). A 
true positive is a prediction that was correct and the data point belongs to the 
positive class. A false negative is a prediction that was incorrect where the actual 
value is positive and the predicted value was negative. A false negative is a 
prediction that was incorrect because the prediction was positive but the actual 
value was negative. Precision can then be defined as the number of true positives 
divided by the sum of true positives and false positives. Recall can be defined as 
the number of true positives divided by the sum of true positives and false 
negatives.

The Idea behind the precision-recall trade-off is that when a person changes the 
threshold for determining if a class is positive or negative it will tilt the scales. 
What I mean by that is that it will cause precision to increase and recall to 
decrease, or vice versa. Thereby it depends on the person to give importance to 
either precision or recall, based on the problem we are working. 


ROC curve:

An ROC curve is abbreviated as receiver operating characteristic curve is a graph 
showing the performance of a classification model at all classification thresholds. 
This curve plots two parameters:

• True Positive Rate TPR = TP/(TP+FN)

• False Positive Rate FPR=FP/(FP+TN)


The ROC curve shows the trade-off between sensitivity TPR) and specificity (1 –
FPR). Classifiers that give curves closer to the top-left corner indicate a better 
performance. ROC curve plots TPR vs. FPR at different classification thresholds. 
Lowering the classification threshold classifies more items as positive, thus 
increasing both False Positives and True Positives. The ROC curve is a useful tool 
for a few reasons: 

• The curves of different models can be compared directly in general or for 
different thresholds.
• The shape of the curve contains a lot of information, including what we might 
care about most for a problem, the expected false positive rate, and the false 
negative rate.



























## NoteBook Requirements






I have imported the dataset to the jupyter notebook as the dataset is small and I started the coding 
process, I have commented using the markdown lines in you can remove them if the code does not 
execute.
The libraries that I have used are:

Sklearn

Random

Keras

Pandas

Matplotlib

Collections

To perform prediction I have choose the concept of linear regression as the linear regression concept 
is very simple and can predict the values and I have achieved an accuracy of 98 percent, apart from 
that I got 393/400 predictions right and I had evaluated the metrics using the concept of precision
and recall. I have observed around 98 percent precision and recall with about 100 epochs in the 
model











































