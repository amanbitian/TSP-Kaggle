The dataset is used for this competition is **synthetic**, but based on a real dataset and generated using a CTGAN.   
The original dataset deals with **predicting identifying spam emails via various extracted features from the email.**   
Although the features are anonymized, they have properties relating to real-world features.  

## Submissions are evaluated on **area under the ROC curve** `between the predicted probability and the observed target.`  
The Receiver Operator Characteristic (ROC) curve is an evaluation metric for binary classification problems.   
It is a probability curve that plots the TPR against FPR at various threshold values and essentially separates the ‘signal’ from the ‘noise’.   
The Area Under the Curve (AUC) is the measure of the ability of a classifier to distinguish between classes and is used as a summary of the ROC curve.  

The **higher the AUC, the better the performance of the model** `at distinguishing between the positive and negative classes.`

![ROC in one picture 2](https://user-images.githubusercontent.com/86042628/139622962-19bd2817-6d01-4547-ac6c-4c7cbbcc5c22.png)

## How AUC-ROC curve works?
In a ROC curve, a higher X-axis value indicates a higher number of False positives than True negatives.   
While a **higher Y-axis value indicates** `a higher number of True positives than False negatives.`   
So, the **choice of the threshold depends on the ability to balance between False positives and False negatives.**  
