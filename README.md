# Image-Classification-Using-Decision-Tree
Image Classification Using Decision Tree Model

##Flow Diagram

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/Document%201%20(1).jpg)





## Process Followed

###1. The input is divided into 60% and 40% Training and Testing Data respectively.

###2. Using the Training Data Key Descriptors are generated for the each Image

![Keydescriptors](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/2.PNG)
***
###3. Feature Vectors are generated and by using K means clusters are generated.

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/3-1.PNG)

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/4.PNG)

***

###4. Using Bag of Words, Histograms are generated 

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/5.PNG)

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/6.PNG)

***
###5. The histograms input is fed to decision tree and a model is generated from the training data.
Confusion matrix for each image

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/7.PNG)
![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/8.PNG)
![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/9.PNG)

***
###6. The decision tree model is used on the test data and prediction is done.

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/10.PNG)

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/11.PNG)

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/12.PNG)

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/13.PNG)

***
##Results:

###Accuracy of the model is:

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/15.PNG)

###Confusion matrix of the model is:

![image](https://github.com/nandanamudi/Bigdata-Spring2017-Lab_Assignments/blob/master/Lab4/Documentation/Images/16.PNG)
