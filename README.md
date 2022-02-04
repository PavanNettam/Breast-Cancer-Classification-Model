# Breast-Cancer-Classification
Breast cancer is been classified into benign tumour and malignant tumour.
Logistic regression is applied in this model.

Data Set Information:

Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data. This grouping information appears immediately below, having been removed from the data itself: 

Group 1: 367 instances (January 1989) 
Group 2: 70 instances (October 1989) 
Group 3: 31 instances (February 1990) 
Group 4: 17 instances (April 1990) 
Group 5: 48 instances (August 1990) 
Group 6: 49 instances (Updated January 1991) 
Group 7: 31 instances (June 1991) 
Group 8: 86 instances (November 1991) 
----------------------------------------- 
Total: 699 points (as of the donated datbase on 15 July 1992) 

Attribute Information:

1. Sample code number: id number 
2. Clump Thickness: 1 - 10 
3. Uniformity of Cell Size: 1 - 10 
4. Uniformity of Cell Shape: 1 - 10 
5. Marginal Adhesion: 1 - 10 
6. Single Epithelial Cell Size: 1 - 10 
7. Bare Nuclei: 1 - 10 
8. Bland Chromatin: 1 - 10 
9. Normal Nucleoli: 1 - 10 
10. Mitoses: 1 - 10 
11. Class: (2 for benign, 4 for malignant)

Classfication results:

The dataset is divided into two parts,
Trainings set(80% of the dataset)
Testing set(20% of the dataset)

Logistic regression model is applied on the training dataset and when tested on the testing dataset the following results were obtained:

Confusion matrix:<br>
<img width="585" alt="Screenshot 2022-02-04 at 5 37 26 PM" src="https://user-images.githubusercontent.com/79460453/152526602-c34a340c-2cfd-4b99-895a-74d9a004915f.png">

Accuracy Score = 0.9562043795620438
and

K-Fold cross validation shows the following accuracy for the model:

Accuracy = 96.32%
Standard Deviation = 3.69%


