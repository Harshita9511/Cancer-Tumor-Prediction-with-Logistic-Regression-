# Cancer-Tumor-Prediction-with-Logistic-Regression

<img src="/cancer_image.jpg" width="1000" height="300" />
<div align="justify">
  
## Logistic Regression Theory
Logistic Regression solves the classification problem, where the target variable is categorical in nature. It models the data using sigmoid function that takes in any value and outputs it to be between 0 and 1.<br />
Sigmoid function, f(z)= 1/(1+e^(-z))

<img src="/image_lr.png" align="center" width="400" height="400" />

## Model Evaluation
Confusion matrix is used to evaluate classification models performance on a set of test data for which the true values are already known.
<img src="/image.png" align="center" width="400" height="400" />

*True Positive (TP)*: Actual observation is positive and is predicted to be positive.<br />
*True Negative (TN)*: Actual observation is negative and is predicted to be negative.<br />
*False Positive (FP)*: Actual observation is negative but is predicted positive.<br />
*False Negative (FN)*: Actual observation is positive but is predicted negative.<br />

### Evaluation Parameters
**Accuracy**: Ratio of correctly predicted classes to all the classes.<br />
<div align="center">*Accuracy* = (TP+TN) / (TP+TN+FP+FN)</div><br /><br />
**Misclassification Rate (Error rate)**: Ratio of wrong predictions to the total number of classes.<br />
<div align="center">*Error rate* = (FP+FN) / (TP+TN+FP+FN)</div><br /><br />
**Recall**: Ratio of correctly predicted positive classes to all the actual positive classes.<br />
<div align="center">*Recall* = TP / (TP+FN)</div><br /><br />
**Precision**: Ratio of correctly predicted positive classes to all positive predicted classes.<br />
<div align="center">*Precision* = TP / (TP+FP)</div><br /><br />
**F-measure**: It is the harmonic mean of Recall and Precision.<br />
<div align="center">*F-measure* = (2 * Recall * Precision) / (Recall + Precision)</div><br />

## Dataset
The dataset has been taken from UCI machine learning repository. The main objective of the analysis is to perform classification of tumors i.e., benign(B) or malignant(M). A benign tumor is a tumor that does not invade its surrounding tissue or spread around the body. A malignant tumor is a tumor that may invade its surrounding tissue or spread around the body. This dataset consists of 569 rows and 33 columns.<br />
Data Source: [Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).<br />

*id*: ID number.<br />
*diagnosis*: The diagnosis of breast tissues (M = malignant, B = benign).<br />
*radius_mean*: mean of distances from center to points on the perimeter.<br />
*texture_mean*: standard deviation of gray-scale values.<br />
*perimeter_mean*: mean size of the core tumor.<br />
*area_mean*<br />
*smoothness_mean*: mean of local variation in radius lengths.<br />
*compactness_mean*: mean of perimeter² / area — 1.0.<br />
*concavity_mean*: mean of severity of concave portions of the contour.<br />
*concave points_mean*: mean for number of concave portions of the contour.<br />
*symmetry_mean*<br />
*fractal_dimension_mean*: mean for “coastline approximation” — 1.<br />
*radius_se*: standard error for the mean of distances from center to points on the perimeter.<br />
*texture_se*: standard error for standard deviation of gray-scale values.<br />
*perimeter_se*<br />
*area_se*<br />
*smoothness_se*: standard error for local variation in radius lengths.<br />
*compactness_se*: standard error for perimeter² / area — 1.0.<br />
*concavity_se*: standard error for severity of concave portions of the contour.<br />
*concave points_se*: standard error for number of concave portions of the contour.<br />
*symmetry_se*<br />
*fractal_dimension_se*: standard error for “coastline approximation” — 1.<br />
*radius_worst*: “worst” or largest mean value for mean of distances from center to points on the perimeter.<br />
*texture_worst*: “worst” or largest mean value for standard deviation of gray-scale values.<br />
*perimeter_worst*<br />
*area_worst*<br />
*smoothness_worst*: “worst” or largest mean value for local variation in radius lengths.<br />
*compactness_worst*: “worst” or largest mean value for perimeter² / area — 1.0.<br />
*concavity_worst*: “worst” or largest mean value for severity of concave portions of the contour.<br />
*concave points_worst*: “worst” or largest mean value for number of concave portions of the contour.<br />
*symmetry_worst*<br />
*fractal_dimension_worst*: “worst” or largest mean value for “coastline approximation” — 1.<br />

</div>


  
