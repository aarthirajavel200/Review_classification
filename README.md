# Review_classification
This is a simple task pf classifying the reviews which are predefined which are first split into  token by importing the regular expression librar from python and then defining the positive and negative words extracted from that passage and count the positive words and negative words and  also count the no of positive nad negative words and also cout the pronouns and check about the punctuations and also calculated the no of words nad the averaage words in the passage.

The next task is of doing the process of applying all these parameters to the  given the passage and it is done by using the function called extracted features and then output is stored in  a variable which is further used to calcculate the vaue of z in order to find the best weight nad bias l have utilized the concept called gradient descent and which actually provides the effective bias and weights which is then calculated nad then it iis provided as an input to the sigmoid function  and which finds a value between the range of 0 and 1 

The final task of defining whether the review is positive or neegative 
 It is has been done by using the predefined function threshold which is passed with a argument that is the outtput of the sigmoid function and by setting a threshold value we can make decision like 
   if value is greater than 0.5 then it actually says it is positive 
   esle the review is negative
