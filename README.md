# Credit_Risk_Analysis



### Overview
The goal is to be able to predict the risk of a loan. The purpose of this machine learning exercise is to explore different machine learning algorithms that can make the most accurate loan predictions. Because we are aiming to predict the risk of a loan, precision is going to be favored over the recall when determining the best way to approach this problem. 


### [Results](https://github.com/markdown-it/markdown-it-deflist)

![Image_one](https://raw.githubusercontent.com/SavannahPosner/Credit_Risk_Analysis/main/images/1.png)

Naive Random Sampling

+ Balanced Accuracy: 64% 

+ Precision: 99%

+ Recall: 68%


SMOTE

+ Balanced Accuracy: 62%

+ Precision: 99% 

+ Recall: 64%


![Image_two](https://raw.githubusercontent.com/SavannahPosner/Credit_Risk_Analysis/main/images/2.png)

Random Under Sampler

+ Balanced Accuracy: 59%

+ Precision: 99%

+ Recall: 57%

SMOTEENN

+ Balanced Accuracy: 64%

+ Precision: 99%

+ Recall: 57%



![Image_three](https://raw.githubusercontent.com/SavannahPosner/Credit_Risk_Analysis/main/images/3.png)

Balanced Random Forest Classifier 

+ Balanced Accuracy: 79%

+ Precision: 99%

+ Recall: 91%

Easy Ensemble Classifier

+ Balanced Accuracy: 92%

+ Precision: 99%

+ Recall: 94%

### Summary 
Most of the machine learning models’ balanced accuracy score lies between 50% and 65%. These are not preferable numbers. However, most of them have decent precision scores at 99%. Except for the Balanced Random Forest and Easy Ensemble classifiers, the recall percentage remained under 70%. In terms of statistical benefit, the Easy Ensemble Classifier is a clear winner with a balance accuracy of 92%, a precision accuracy of 99%, and a recall accuracy of 94%. However, this algorithm needs to be tested on more data before implemented to verify the results of the algorithm.









