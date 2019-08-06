# The Blood Transfusion Service Center Dataset

### Introduction 
Blood donation has been around for a long time. The first successful recorded transfusion was between two dogs in 1665, and the first medical use of human blood in a transfusion occurred in 1818. Even today, donated blood remains a critical resource during emergencies.

Our dataset is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. 

### Problem Statement
We want to predict whether or not a donor will give blood the next time the vehicle comes to campus.

### Approach
As we are asked to provide the probability that a particular donor will donate blood (a binary variable), we use 3 different types of classification models - Logistic Regression, Random Forest and Gradient Boosting (AdaBoost).

To decide on which model to use for the prediction of the test dataset, we use the logistic loss, or cross-entropy loss as our evaluation metric.

### Result
It turns out that the logistic model scored the best using the entropy loss metric. Using the simple logistic model, our entropy loss on the test dataset was 0.4440. This score was good enough to place us at rank 524 out of 5663 competitors (top 9th percentile).
